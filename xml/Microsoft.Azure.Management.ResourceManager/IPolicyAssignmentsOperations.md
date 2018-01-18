<Type Name="IPolicyAssignmentsOperations" FullName="Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations">
  <TypeSignature Language="C#" Value="public interface IPolicyAssignmentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPolicyAssignmentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPolicyAssignmentsOperations" />
  <TypeSignature Language="F#" Value="type IPolicyAssignmentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="54404-101">PolicyAssignmentsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="54404-101">PolicyAssignmentsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; CreateByIdWithHttpMessagesAsync (string policyAssignmentId, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; CreateByIdWithHttpMessagesAsync(string policyAssignmentId, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.CreateByIdWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateByIdWithHttpMessagesAsync : string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.CreateByIdWithHttpMessagesAsync (policyAssignmentId, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policyAssignmentId">
            <span data-ttu-id="54404-102">作成するポリシー割り当ての ID。</span><span class="sxs-lookup"><span data-stu-id="54404-102">The ID of the policy assignment to create.</span></span> <span data-ttu-id="54404-103">形式を使用して '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'。</span><span class="sxs-lookup"><span data-stu-id="54404-103">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54404-104">ポリシー割り当てのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="54404-104">Parameters for policy assignment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-107">ID で、ポリシー割り当てを作成します。</span><span class="sxs-lookup"><span data-stu-id="54404-107">Creates a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="54404-108">ポリシーの割り当ては、子リソースによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="54404-108">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="54404-109">たとえば、リソース グループにポリシーを適用するときにそのポリシーがグループ内のすべてのリソースに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="54404-109">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span> <span data-ttu-id="54404-110">割り当てのスコープを提供するときに使用 'サブスクリプション/{サブスクリプション id}/' 'のサブスクリプション/{サブスクリプション id} 必要な {リソース グループ名}' のリソース グループのサブスクリプションの場合と' subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name/}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="54404-110">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-113">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; CreateWithHttpMessagesAsync (string scope, string policyAssignmentName, Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; CreateWithHttpMessagesAsync(string scope, string policyAssignmentName, class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.CreateWithHttpMessagesAsync (scope, policyAssignmentName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="54404-115">ポリシー割り当てのスコープです。</span><span class="sxs-lookup"><span data-stu-id="54404-115">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="54404-116">ポリシー割り当ての名前。</span><span class="sxs-lookup"><span data-stu-id="54404-116">The name of the policy assignment.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="54404-117">ポリシー割り当てのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="54404-117">Parameters for the policy assignment.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-120">ポリシー割り当てを作成します。</span><span class="sxs-lookup"><span data-stu-id="54404-120">Creates a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="54404-121">ポリシーの割り当ては、子リソースによって継承されます。</span><span class="sxs-lookup"><span data-stu-id="54404-121">Policy assignments are inherited by child resources.</span></span> <span data-ttu-id="54404-122">たとえば、リソース グループにポリシーを適用するときにそのポリシーがグループ内のすべてのリソースに割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="54404-122">For example, when you apply a policy to a resource group that policy is assigned to all resources in the group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-125">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; DeleteByIdWithHttpMessagesAsync (string policyAssignmentId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; DeleteByIdWithHttpMessagesAsync(string policyAssignmentId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.DeleteByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.DeleteByIdWithHttpMessagesAsync (policyAssignmentId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policyAssignmentId">
            <span data-ttu-id="54404-127">削除するポリシー割り当ての ID。</span><span class="sxs-lookup"><span data-stu-id="54404-127">The ID of the policy assignment to delete.</span></span> <span data-ttu-id="54404-128">形式を使用して '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'。</span><span class="sxs-lookup"><span data-stu-id="54404-128">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-131">ID でのポリシー割り当てを削除します。</span><span class="sxs-lookup"><span data-stu-id="54404-131">Deletes a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="54404-132">割り当てのスコープを提供するときに使用 'サブスクリプション/{サブスクリプション id}/' 'のサブスクリプション/{サブスクリプション id} 必要な {リソース グループ名}' のリソース グループのサブスクリプションの場合と' subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name/}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="54404-132">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-135">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; DeleteWithHttpMessagesAsync (string scope, string policyAssignmentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; DeleteWithHttpMessagesAsync(string scope, string policyAssignmentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.DeleteWithHttpMessagesAsync (scope, policyAssignmentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="54404-137">ポリシー割り当てのスコープです。</span><span class="sxs-lookup"><span data-stu-id="54404-137">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="54404-138">削除するポリシー割り当ての名前。</span><span class="sxs-lookup"><span data-stu-id="54404-138">The name of the policy assignment to delete.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-141">ポリシー割り当てを削除します。</span><span class="sxs-lookup"><span data-stu-id="54404-141">Deletes a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-142">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-142">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-143">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-143">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-144">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetByIdWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; GetByIdWithHttpMessagesAsync (string policyAssignmentId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; GetByIdWithHttpMessagesAsync(string policyAssignmentId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.GetByIdWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.GetByIdWithHttpMessagesAsync (policyAssignmentId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policyAssignmentId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="policyAssignmentId">
            <span data-ttu-id="54404-146">取得するポリシー割り当ての ID。</span><span class="sxs-lookup"><span data-stu-id="54404-146">The ID of the policy assignment to get.</span></span> <span data-ttu-id="54404-147">形式を使用して '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'。</span><span class="sxs-lookup"><span data-stu-id="54404-147">Use the format '/{scope}/providers/Microsoft.Authorization/policyAssignments/{policy-assignment-name}'.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-150">ポリシー割り当て id を取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-150">Gets a policy assignment by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="54404-151">割り当てのスコープを提供するときに使用 'サブスクリプション/{サブスクリプション id}/' 'のサブスクリプション/{サブスクリプション id} 必要な {リソース グループ名}' のリソース グループのサブスクリプションの場合と' subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name/}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="54404-151">When providing a scope for the assigment, use '/subscriptions/{subscription-id}/' for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}' for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}' for resources.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-152">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-152">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-153">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-153">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-154">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; GetWithHttpMessagesAsync (string scope, string policyAssignmentName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt; GetWithHttpMessagesAsync(string scope, string policyAssignmentName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;" Usage="iPolicyAssignmentsOperations.GetWithHttpMessagesAsync (scope, policyAssignmentName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="policyAssignmentName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="54404-156">ポリシー割り当てのスコープです。</span><span class="sxs-lookup"><span data-stu-id="54404-156">The scope of the policy assignment.</span></span>
            </param>
        <param name="policyAssignmentName">
            <span data-ttu-id="54404-157">取得するポリシー割り当ての名前。</span><span class="sxs-lookup"><span data-stu-id="54404-157">The name of the policy assignment to get.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-160">ポリシー割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-160">Gets a policy assignment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-163">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListForResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListForResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="54404-165">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="54404-165">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-168">リソース グループのポリシーの割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-168">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-171">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceGroupWithHttpMessagesAsync (string resourceGroupName, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceGroupWithHttpMessagesAsync(string resourceGroupName, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListForResourceGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListForResourceGroupWithHttpMessagesAsync (resourceGroupName, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54404-173">ポリシーの割り当てが含まれているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="54404-173">The name of the resource group that contains policy assignments.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="54404-174">操作に適用するフィルター。</span><span class="sxs-lookup"><span data-stu-id="54404-174">The filter to apply on the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-177">リソース グループのポリシーの割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-177">Gets policy assignments for the resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-180">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListForResourceNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListForResourceNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="54404-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="54404-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-185">リソースのポリシーの割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-185">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-188">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceWithHttpMessagesAsync (string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListForResourceWithHttpMessagesAsync(string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListForResourceWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListForResourceWithHttpMessagesAsync (resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="54404-190">リソースを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="54404-190">The name of the resource group containing the resource.</span></span> <span data-ttu-id="54404-191">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="54404-191">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="54404-192">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="54404-192">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="54404-193">親リソースのパス。</span><span class="sxs-lookup"><span data-stu-id="54404-193">The parent resource path.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="54404-194">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="54404-194">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="54404-195">ポリシーの割り当てを持つリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="54404-195">The name of the resource with policy assignments.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="54404-196">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="54404-196">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-199">リソースのポリシーの割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-199">Gets policy assignments for a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-200">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-200">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-201">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-201">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-202">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-202">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="54404-204">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="54404-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-207">サブスクリプションのすべてのポリシー割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-207">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-208">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-209">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-210">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-211">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-211">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.IPolicyAssignmentsOperations.ListWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;" Usage="iPolicyAssignmentsOperations.ListWithHttpMessagesAsync (odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.PolicyAssignment&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="54404-212">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="54404-212">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="54404-213">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="54404-213">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="54404-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="54404-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="54404-215">サブスクリプションのすべてのポリシー割り当てを取得します。</span><span class="sxs-lookup"><span data-stu-id="54404-215">Gets all the policy assignments for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="54404-216">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-216">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="54404-217">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-217">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54404-218">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-218">Thrown when a required parameter is null</span></span>
            </exception>
        <exception cref="T:Microsoft.Azure.Management.ResourceManager.Models.ErrorResponseException">
            <span data-ttu-id="54404-219">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="54404-219">Thrown when the operation returned an invalid status code</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>