<Type Name="IFailoverGroupsOperations" FullName="Microsoft.Azure.Management.Sql.IFailoverGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IFailoverGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFailoverGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFailoverGroupsOperations" />
  <TypeSignature Language="F#" Value="type IFailoverGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd456-101">FailoverGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="fd456-101">FailoverGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-104">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-104">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-105">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-105">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd456-106">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd456-106">The failover group parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-109">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fd456-109">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFailoverGroupsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-115">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-115">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-116">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-116">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-119">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="fd456-119">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginFailoverWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginFailoverWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.BeginFailoverWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginFailoverWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.BeginFailoverWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-122">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-123">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-124">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-124">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-125">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-125">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-128">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="fd456-128">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginForceFailoverAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginForceFailoverAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginForceFailoverAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.BeginForceFailoverAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginForceFailoverAllowDataLossWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.BeginForceFailoverAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-132">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-132">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-133">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-133">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-134">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-134">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-135">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-135">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-138">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="fd456-138">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="fd456-139">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fd456-139">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-143">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-144">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-145">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-145">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-146">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-146">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd456-147">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd456-147">The failover group parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-150">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fd456-150">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-154">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-155">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-156">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-156">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-157">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-157">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd456-158">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd456-158">The failover group parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-161">作成またはフェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fd456-161">Creates or updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-163">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-163">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-164">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-164">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFailoverGroupsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-165">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-166">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-167">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-167">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-168">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-168">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-171">グループのフェールオーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="fd456-171">Deletes a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="FailoverWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; FailoverWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; FailoverWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.FailoverWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.FailoverWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-174">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-175">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-176">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-176">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-177">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-177">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-178">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-178">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-179">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-180">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="fd456-180">Fails over from the current primary server to this server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ForceFailoverAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ForceFailoverAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; ForceFailoverAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.ForceFailoverAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ForceFailoverAllowDataLossWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.ForceFailoverAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-184">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-184">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-185">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-185">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-186">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-186">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-187">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-187">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-188">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-188">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-190">現在のプライマリ サーバーからこのサーバーにフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="fd456-190">Fails over from the current primary server to this server.</span></span> <span data-ttu-id="fd456-191">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fd456-191">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-195">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-196">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-197">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-197">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-198">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-198">The name of the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-199">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-199">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-201">フェールオーバー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="fd456-201">Gets a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-202">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-202">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-203">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-203">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-204">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-204">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt; ListByServerNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt; ListByServerNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.ListByServerNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt;" Usage="iFailoverGroupsOperations.ListByServerNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fd456-205">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fd456-205">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-206">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-206">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-207">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-208">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fd456-208">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt;" Usage="iFailoverGroupsOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-212">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-212">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-213">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-213">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-214">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-214">The name of the server containing the failover group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-215">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-215">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-216">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-217">サーバーにフェールオーバー グループが表示されます。</span><span class="sxs-lookup"><span data-stu-id="fd456-217">Lists the failover groups in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-218">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-218">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-219">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-219">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-220">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-220">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string failoverGroupName, Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string failoverGroupName, class Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IFailoverGroupsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;" Usage="iFailoverGroupsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, serverName, failoverGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.FailoverGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="failoverGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.FailoverGroupUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fd456-221">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-221">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd456-222">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fd456-222">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fd456-223">グループのフェールオーバーを含むサーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-223">The name of the server containing the failover group.</span></span>
            </param>
        <param name="failoverGroupName">
            <span data-ttu-id="fd456-224">フェールオーバー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fd456-224">The name of the failover group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fd456-225">フェールオーバー グループのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fd456-225">The failover group parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd456-226">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fd456-226">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd456-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fd456-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd456-228">フェールオーバー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fd456-228">Updates a failover group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fd456-229">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fd456-230">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fd456-231">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fd456-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>