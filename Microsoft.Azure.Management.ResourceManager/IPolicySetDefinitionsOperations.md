<Type Name="IPolicySetDefinitionsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations">
  <TypeSignature Language="C#" Value="public interface IPolicySetDefinitionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPolicySetDefinitionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPolicySetDefinitionsOperations" />
  <TypeSignature Language="F#" Value="type IPolicySetDefinitionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d8463-101">PolicySetDefinitionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d8463-101">PolicySetDefinitionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string policySetDefinitionName, Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string policySetDefinitionName, class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;" Usage="iPolicySetDefinitionsOperations.CreateOrUpdateWithHttpMessagesAsync (policySetDefinitionName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policySetDefinitionName">
            <span data-ttu-id="d8463-102">ポリシーの名前は、作成する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8463-102">The name of the policy set definition to create.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d8463-103">ポリシーは、定義のプロパティを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8463-103">The policy set definition properties.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d8463-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d8463-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d8463-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d8463-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8463-106">作成するか、ポリシーのセットの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="d8463-106">Creates or updates a policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="d8463-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d8463-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8463-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string policySetDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string policySetDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations.DeleteWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPolicySetDefinitionsOperations.DeleteWithHttpMessagesAsync (policySetDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policySetDefinitionName">
            <span data-ttu-id="d8463-110">ポリシーの名前は、削除する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8463-110">The name of the policy set definition to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d8463-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d8463-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d8463-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d8463-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8463-113">削除、ポリシーは、定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8463-113">Deletes a policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="d8463-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8463-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; GetWithHttpMessagesAsync (string policySetDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt; GetWithHttpMessagesAsync(string policySetDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;" Usage="iPolicySetDefinitionsOperations.GetWithHttpMessagesAsync (policySetDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policySetDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policySetDefinitionName">
            <span data-ttu-id="d8463-116">ポリシーの名前を取得する定義を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8463-116">The name of the policy set definition to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d8463-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d8463-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d8463-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d8463-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8463-119">ポリシーのセットの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8463-119">Gets the policy set definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="d8463-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d8463-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8463-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt;" Usage="iPolicySetDefinitionsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d8463-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d8463-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d8463-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d8463-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d8463-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d8463-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8463-126">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8463-126">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="d8463-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d8463-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8463-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicySetDefinitionsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt;" Usage="iPolicySetDefinitionsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicySetDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="d8463-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d8463-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d8463-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d8463-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8463-132">すべてのポリシー セットのサブスクリプションの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8463-132">Gets all the policy set definitions for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="d8463-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d8463-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d8463-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d8463-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>