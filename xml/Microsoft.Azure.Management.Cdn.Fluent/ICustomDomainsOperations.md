<Type Name="ICustomDomainsOperations" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations">
  <TypeSignature Language="C#" Value="public interface ICustomDomainsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICustomDomainsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICustomDomainsOperations" />
  <TypeSignature Language="F#" Value="type ICustomDomainsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7268d-101">CustomDomainsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="7268d-101">CustomDomainsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, hostName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-103">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-103">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-104">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-104">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-105">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-105">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="7268d-106">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="7268d-106">The host name of the custom domain.</span></span> <span data-ttu-id="7268d-107">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="7268d-107">Must be a domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-110">エンドポイント内の新しいカスタム ドメインを作成します。</span><span class="sxs-lookup"><span data-stu-id="7268d-110">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-114">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-114">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-115">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-115">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-116">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-116">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-117">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-117">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-120">エンドポイント内の既存のカスタム ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="7268d-120">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.CreateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, hostName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-124">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-125">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-125">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-126">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-126">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-127">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-127">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="hostName">
            <span data-ttu-id="7268d-128">カスタム ドメインのホスト名。</span><span class="sxs-lookup"><span data-stu-id="7268d-128">The host name of the custom domain.</span></span> <span data-ttu-id="7268d-129">ドメイン名である必要があります。</span><span class="sxs-lookup"><span data-stu-id="7268d-129">Must be a domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-132">エンドポイント内の新しいカスタム ドメインを作成します。</span><span class="sxs-lookup"><span data-stu-id="7268d-132">Creates a new custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-136">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-136">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-137">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-137">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-138">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-138">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-139">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-139">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-142">エンドポイント内の既存のカスタム ドメインを削除します。</span><span class="sxs-lookup"><span data-stu-id="7268d-142">Deletes an existing custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DisableCustomHttpsWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; DisableCustomHttpsWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.DisableCustomHttpsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableCustomHttpsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.DisableCustomHttpsWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-146">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-146">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-147">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-147">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-148">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-148">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-149">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-149">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-152">カスタム ドメインの https 配信を無効にします。</span><span class="sxs-lookup"><span data-stu-id="7268d-152">Disable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; EnableCustomHttpsWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; EnableCustomHttpsWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.EnableCustomHttpsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableCustomHttpsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.EnableCustomHttpsWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-156">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-156">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-157">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-157">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-158">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-158">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-159">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-159">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-162">カスタム ドメインの https 配信を有効にします。</span><span class="sxs-lookup"><span data-stu-id="7268d-162">Enable https delivery of the custom domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string customDomainName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="iCustomDomainsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customDomainName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-166">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-166">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-167">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-167">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-168">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-168">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customDomainName">
            <span data-ttu-id="7268d-169">エンドポイント内でカスタム ドメインの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-169">Name of the custom domain within an endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-172">エンドポイント内の既存のカスタム ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="7268d-172">Gets an exisitng custom domain within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.ListByEndpointNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;" Usage="iCustomDomainsOperations.ListByEndpointNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7268d-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7268d-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-179">すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7268d-179">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations.ListByEndpointWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;" Usage="iCustomDomainsOperations.ListByEndpointWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="7268d-183">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-183">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="7268d-184">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-184">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="7268d-185">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="7268d-185">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7268d-186">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="7268d-186">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7268d-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7268d-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7268d-188">すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="7268d-188">Lists all of the existing custom domains within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="7268d-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7268d-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7268d-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="7268d-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>