<Type Name="IOriginsOperations" FullName="Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations">
  <TypeSignature Language="C#" Value="public interface IOriginsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOriginsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOriginsOperations" />
  <TypeSignature Language="F#" Value="type IOriginsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ec8f7-101">OriginsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-101">OriginsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="iOriginsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, originName, originUpdateProperties, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec8f7-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="ec8f7-103">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-103">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="ec8f7-104">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-104">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="ec8f7-105">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-105">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="ec8f7-106">配信元のプロパティ</span><span class="sxs-lookup"><span data-stu-id="ec8f7-106">Origin properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ec8f7-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec8f7-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec8f7-109">エンドポイント内の既存の配信元を更新します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-109">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="ec8f7-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ec8f7-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec8f7-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string originName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string originName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="iOriginsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, originName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec8f7-113">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-113">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="ec8f7-114">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-114">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="ec8f7-115">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-115">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="ec8f7-116">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-116">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ec8f7-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec8f7-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec8f7-119">エンドポイント内の既存の原点を取得します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-119">Gets an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="ec8f7-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ec8f7-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec8f7-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt; ListByEndpointNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations.ListByEndpointNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt;" Usage="iOriginsOperations.ListByEndpointNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="ec8f7-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ec8f7-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec8f7-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec8f7-126">すべてのエンドポイント内の既存の origin の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-126">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="ec8f7-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ec8f7-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec8f7-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt; ListByEndpointWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations.ListByEndpointWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEndpointWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt;" Usage="iOriginsOperations.ListByEndpointWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="ec8f7-130">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-130">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="ec8f7-131">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-131">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="ec8f7-132">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-132">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ec8f7-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec8f7-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec8f7-135">すべてのエンドポイント内の既存の origin の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-135">Lists all of the existing origins within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="ec8f7-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ec8f7-137">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-137">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec8f7-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointName, string originName, Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointName, string originName, class Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner originUpdateProperties, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.IOriginsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;" Usage="iOriginsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointName, originName, originUpdateProperties, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.OriginInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originUpdateProperties" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.OriginUpdateParametersInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ec8f7-139">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-139">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="ec8f7-140">リソース グループ内で一意である CDN プロファイルの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-140">Name of the CDN profile which is unique within the resource group.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="ec8f7-141">グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-141">Name of the endpoint under the profile which is unique globally.</span></span>
            </param>
        <param name="originName">
            <span data-ttu-id="ec8f7-142">これは、エンドポイント内で一意で元の名前です。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-142">Name of the origin which is unique within the endpoint.</span></span>
            </param>
        <param name="originUpdateProperties">
            <span data-ttu-id="ec8f7-143">配信元のプロパティ</span><span class="sxs-lookup"><span data-stu-id="ec8f7-143">Origin properties</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ec8f7-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ec8f7-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ec8f7-146">エンドポイント内の既存の配信元を更新します。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-146">Updates an existing origin within an endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ErrorResponseException">
            <span data-ttu-id="ec8f7-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ec8f7-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ec8f7-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ec8f7-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>