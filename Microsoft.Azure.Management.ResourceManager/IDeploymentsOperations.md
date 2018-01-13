<Type Name="IDeploymentsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations">
  <TypeSignature Language="C#" Value="public interface IDeploymentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeploymentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeploymentsOperations" />
  <TypeSignature Language="F#" Value="type IDeploymentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="be168-101">DeploymentsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="be168-101">DeploymentsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-102">リソースをデプロイするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-102">The name of the resource group to deploy the resources to.</span></span> <span data-ttu-id="be168-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-103">The name is case insensitive.</span></span> <span data-ttu-id="be168-104">リソース グループは既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="be168-104">The resource group must already exist.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-105">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-105">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="be168-106">追加のパラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="be168-106">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-109">リソース グループにリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="be168-109">Deploys resources to a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="be168-110">テンプレートと、要求または JSON ファイルへのリンクで直接パラメーターを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="be168-110">You can provide the template and parameters directly in the request or link to JSON files.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-114">削除する配置を使用してリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="be168-114">The name of the resource group with the deployment to delete.</span></span> <span data-ttu-id="be168-115">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-115">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-116">削除するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-116">The name of the deployment to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-119">デプロイ履歴から、展開を削除します。</span><span class="sxs-lookup"><span data-stu-id="be168-119">Deletes a deployment from the deployment history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="be168-120">現在実行されているテンプレートのデプロイを削除できません。</span><span class="sxs-lookup"><span data-stu-id="be168-120">A template deployment that is currently running cannot be deleted.</span></span>
            <span data-ttu-id="be168-121">テンプレート デプロイを削除すると、関連付けられている展開の操作が削除されます。</span><span class="sxs-lookup"><span data-stu-id="be168-121">Deleting a template deployment removes the associated deployment operations.</span></span> <span data-ttu-id="be168-122">テンプレート デプロイを削除しても、リソース グループの状態には影響しません。</span><span class="sxs-lookup"><span data-stu-id="be168-122">Deleting a template deployment does not affect the state of the resource group.</span></span> <span data-ttu-id="be168-123">これは、テンプレートのデプロイが正常に削除されるまで 202 の状態を返す非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="be168-123">This is an asynchronous operation that returns a status of 202 until the template deployment is successfully deleted.</span></span> <span data-ttu-id="be168-124">Location 応答ヘッダーには、プロセスの状態の取得に使用される URI が含まれています。</span><span class="sxs-lookup"><span data-stu-id="be168-124">The Location response header contains the URI that is used to obtain the status of the process.</span></span> <span data-ttu-id="be168-125">プロセスの実行中に、Location ヘッダーの URI への呼び出しは 202 の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="be168-125">While the process is running, a call to the URI in the Location header returns a status of 202.</span></span> <span data-ttu-id="be168-126">プロセスが終了すると、Location ヘッダーの URI は、成功すると 204 の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="be168-126">When the process finishes, the URI in the Location header returns a status of 204 on success.</span></span> <span data-ttu-id="be168-127">非同期の要求に失敗した場合、Location ヘッダーの URI は、エラー レベルの状態コードを返します。</span><span class="sxs-lookup"><span data-stu-id="be168-127">If the asynchronous request failed, the URI in the Location header returns an error-level status code.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CancelWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.CancelWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-130">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-130">The name of the resource group.</span></span> <span data-ttu-id="be168-131">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-131">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-132">キャンセルするデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-132">The name of the deployment to cancel.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-135">現在実行中のテンプレート デプロイをキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="be168-135">Cancels a currently running template deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="be168-136">ProvisioningState が承諾済みまたは実行中の場合にのみ、展開をキャンセルすることができます。</span><span class="sxs-lookup"><span data-stu-id="be168-136">You can cancel a deployment only if the provisioningState is Accepted or Running.</span></span> <span data-ttu-id="be168-137">配置が取り消された後、provisioningState が取り消し済みに設定されます。</span><span class="sxs-lookup"><span data-stu-id="be168-137">After the deployment is canceled, the provisioningState is set to Canceled.</span></span> <span data-ttu-id="be168-138">テンプレート デプロイをキャンセルでは、現在実行中のテンプレート デプロイを停止し、部分的にデプロイされたリソース グループのままにします。</span><span class="sxs-lookup"><span data-stu-id="be168-138">Canceling a template deployment stops the currently running template deployment and leaves the resource group partially deployed.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; CheckExistenceWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CheckExistenceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckExistenceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iDeploymentsOperations.CheckExistenceWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-141">確認する配置を使用してリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-141">The name of the resource group with the deployment to check.</span></span> <span data-ttu-id="be168-142">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-142">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-143">チェックするデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-143">The name of the deployment to check.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-146">展開が存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="be168-146">Checks whether the deployment exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-149">リソースをデプロイするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-149">The name of the resource group to deploy the resources to.</span></span> <span data-ttu-id="be168-150">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-150">The name is case insensitive.</span></span> <span data-ttu-id="be168-151">リソース グループは既に存在する必要があります。</span><span class="sxs-lookup"><span data-stu-id="be168-151">The resource group must already exist.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-152">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-152">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="be168-153">追加のパラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="be168-153">Additional parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-154">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-154">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-156">リソース グループにリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="be168-156">Deploys resources to a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="be168-157">テンプレートと、要求または JSON ファイルへのリンクで直接パラメーターを指定することができます。</span><span class="sxs-lookup"><span data-stu-id="be168-157">You can provide the template and parameters directly in the request or link to JSON files.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDeploymentsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-161">削除する配置を使用してリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="be168-161">The name of the resource group with the deployment to delete.</span></span> <span data-ttu-id="be168-162">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-162">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-163">削除するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-163">The name of the deployment to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-166">デプロイ履歴から、展開を削除します。</span><span class="sxs-lookup"><span data-stu-id="be168-166">Deletes a deployment from the deployment history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="be168-167">現在実行されているテンプレートのデプロイを削除できません。</span><span class="sxs-lookup"><span data-stu-id="be168-167">A template deployment that is currently running cannot be deleted.</span></span>
            <span data-ttu-id="be168-168">テンプレート デプロイを削除すると、関連付けられている展開の操作が削除されます。</span><span class="sxs-lookup"><span data-stu-id="be168-168">Deleting a template deployment removes the associated deployment operations.</span></span> <span data-ttu-id="be168-169">テンプレート デプロイを削除しても、リソース グループの状態には影響しません。</span><span class="sxs-lookup"><span data-stu-id="be168-169">Deleting a template deployment does not affect the state of the resource group.</span></span> <span data-ttu-id="be168-170">これは、テンプレートのデプロイが正常に削除されるまで 202 の状態を返す非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="be168-170">This is an asynchronous operation that returns a status of 202 until the template deployment is successfully deleted.</span></span> <span data-ttu-id="be168-171">Location 応答ヘッダーには、プロセスの状態の取得に使用される URI が含まれています。</span><span class="sxs-lookup"><span data-stu-id="be168-171">The Location response header contains the URI that is used to obtain the status of the process.</span></span> <span data-ttu-id="be168-172">プロセスの実行中に、Location ヘッダーの URI への呼び出しは 202 の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="be168-172">While the process is running, a call to the URI in the Location header returns a status of 202.</span></span> <span data-ttu-id="be168-173">プロセスが終了すると、Location ヘッダーの URI は、成功すると 204 の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="be168-173">When the process finishes, the URI in the Location header returns a status of 204 on success.</span></span> <span data-ttu-id="be168-174">非同期の要求に失敗した場合、Location ヘッダーの URI は、エラー レベルの状態コードを返します。</span><span class="sxs-lookup"><span data-stu-id="be168-174">If the asynchronous request failed, the URI in the Location header returns an error-level status code.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-176">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-176">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt; ExportTemplateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt; ExportTemplateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ExportTemplateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportTemplateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt;" Usage="iDeploymentsOperations.ExportTemplateWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExportResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-177">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-177">The name of the resource group.</span></span> <span data-ttu-id="be168-178">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-178">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-179">テンプレートを取得するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-179">The name of the deployment from which to get the template.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-182">指定した展開に使用するテンプレートをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="be168-182">Exports the template used for specified deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string deploymentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;" Usage="iDeploymentsOperations.GetWithHttpMessagesAsync (resourceGroupName, deploymentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-186">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-186">The name of the resource group.</span></span> <span data-ttu-id="be168-187">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-187">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-188">取得するデプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-188">The name of the deployment to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-191">展開を取得します。</span><span class="sxs-lookup"><span data-stu-id="be168-191">Gets a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;" Usage="iDeploymentsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="be168-195">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="be168-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-198">リソース グループのすべての展開を取得します。</span><span class="sxs-lookup"><span data-stu-id="be168-198">Get all the deployments for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;" Usage="iDeploymentsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtended&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentExtendedFilter&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-202">取得する、展開にリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-202">The name of the resource group with the deployments to get.</span></span> <span data-ttu-id="be168-203">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-203">The name is case insensitive.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="be168-204">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="be168-204">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-207">リソース グループのすべての展開を取得します。</span><span class="sxs-lookup"><span data-stu-id="be168-207">Get all the deployments for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-208">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-209">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-210">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt; ValidateWithHttpMessagesAsync (string resourceGroupName, string deploymentName, Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt; ValidateWithHttpMessagesAsync(string resourceGroupName, string deploymentName, class Microsoft.Azure.Management.ResourceManager.Models.Deployment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IDeploymentsOperations.ValidateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.Deployment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.Deployment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt;" Usage="iDeploymentsOperations.ValidateWithHttpMessagesAsync (resourceGroupName, deploymentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.Deployment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="be168-211">リソース グループの名前に、テンプレートが配置されます。</span><span class="sxs-lookup"><span data-stu-id="be168-211">The name of the resource group the template will be deployed to.</span></span>
            <span data-ttu-id="be168-212">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="be168-212">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="be168-213">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="be168-213">The name of the deployment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="be168-214">検証するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="be168-214">Parameters to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="be168-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="be168-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="be168-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="be168-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="be168-217">指定されたテンプレートの構文が正しいと Azure リソース マネージャーでを受け付けられるかどうかを検証するには.</span><span class="sxs-lookup"><span data-stu-id="be168-217">Validates whether the specified template is syntactically correct and will be accepted by Azure Resource Manager..</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="be168-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="be168-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="be168-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="be168-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>