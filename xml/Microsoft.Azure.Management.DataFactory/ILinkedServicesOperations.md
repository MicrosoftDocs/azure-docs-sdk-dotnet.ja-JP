<Type Name="ILinkedServicesOperations" FullName="Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations">
  <TypeSignature Language="C#" Value="public interface ILinkedServicesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILinkedServicesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILinkedServicesOperations" />
  <TypeSignature Language="F#" Value="type ILinkedServicesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2aa6-101">LinkedServicesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-101">LinkedServicesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string linkedServiceName, Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string linkedServiceName, class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource linkedService, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;" Usage="iLinkedServicesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, factoryName, linkedServiceName, linkedService, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="linkedService" Type="Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a2aa6-102">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="a2aa6-103">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-103">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="a2aa6-104">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-104">The linked service name.</span></span>
            </param>
        <param name="linkedService">
            <span data-ttu-id="a2aa6-105">リンクされたサービスのリソース定義します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-105">Linked service resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="a2aa6-106">LinkedService のエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-106">ETag of the linkedService entity.</span></span>  <span data-ttu-id="a2aa6-107">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-107">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a2aa6-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2aa6-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2aa6-110">作成またはリンクされたサービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-110">Creates or updates a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="a2aa6-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a2aa6-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2aa6-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string factoryName, string linkedServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string factoryName, string linkedServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iLinkedServicesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, factoryName, linkedServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a2aa6-114">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="a2aa6-115">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-115">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="a2aa6-116">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-116">The linked service name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a2aa6-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2aa6-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2aa6-119">リンクされたサービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-119">Deletes a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="a2aa6-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2aa6-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string linkedServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string linkedServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;" Usage="iLinkedServicesOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, linkedServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a2aa6-122">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-122">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="a2aa6-123">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-123">The factory name.</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="a2aa6-124">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-124">The linked service name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a2aa6-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2aa6-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2aa6-127">リンクされたサービスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-127">Gets a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="a2aa6-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a2aa6-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2aa6-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations.ListByFactoryNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt;" Usage="iLinkedServicesOperations.ListByFactoryNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="a2aa6-131">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-131">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a2aa6-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2aa6-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2aa6-134">リンクされたサービスのリスト。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-134">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="a2aa6-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a2aa6-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2aa6-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.ILinkedServicesOperations.ListByFactoryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt;" Usage="iLinkedServicesOperations.ListByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.LinkedServiceResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a2aa6-138">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-138">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="a2aa6-139">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-139">The factory name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a2aa6-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a2aa6-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a2aa6-142">リンクされたサービスのリスト。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-142">Lists linked services.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="a2aa6-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a2aa6-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a2aa6-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a2aa6-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>