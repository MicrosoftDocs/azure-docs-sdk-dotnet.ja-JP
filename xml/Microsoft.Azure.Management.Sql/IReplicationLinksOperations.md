<Type Name="IReplicationLinksOperations" FullName="Microsoft.Azure.Management.Sql.IReplicationLinksOperations">
  <TypeSignature Language="C#" Value="public interface IReplicationLinksOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReplicationLinksOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IReplicationLinksOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReplicationLinksOperations" />
  <TypeSignature Language="F#" Value="type IReplicationLinksOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7965-101">ReplicationLinksOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f7965-101">ReplicationLinksOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginFailoverAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.BeginFailoverAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginFailoverAllowDataLossWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iReplicationLinksOperations.BeginFailoverAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-105">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-105">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-106">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="f7965-106">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-109">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7965-109">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="f7965-110">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f7965-110">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.BeginFailoverWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginFailoverWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iReplicationLinksOperations.BeginFailoverWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-115">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-115">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-116">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-116">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-117">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="f7965-117">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-120">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7965-120">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iReplicationLinksOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-123">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-123">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-124">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-124">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-125">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-125">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-126">削除するレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-126">The name of the database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-127">削除するレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="f7965-127">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-130">データベース レプリケーション リンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7965-130">Deletes a database replication link.</span></span> <span data-ttu-id="f7965-131">フェールオーバー中には実行できません。</span><span class="sxs-lookup"><span data-stu-id="f7965-131">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="FailoverAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.FailoverAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverAllowDataLossWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iReplicationLinksOperations.FailoverAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-134">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-135">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-136">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-136">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-137">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-137">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-138">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="f7965-138">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-141">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7965-141">Sets which replica database is primary by failing over from the current primary replica database.</span></span> <span data-ttu-id="f7965-142">この操作を行うとデータが失われる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f7965-142">This operation might result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-144">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-144">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="FailoverWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.FailoverWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iReplicationLinksOperations.FailoverWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
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
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-145">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-145">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-146">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-147">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-147">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-148">フェールオーバーを行うレプリケーション リンクがあるデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-148">The name of the database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-149">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="f7965-149">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-152">現在のプライマリ レプリカのデータベースからフェールオーバーして、どのレプリカのデータベースがプライマリかを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7965-152">Sets which replica database is primary by failing over from the current primary replica database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;" Usage="iReplicationLinksOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-155">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-155">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-156">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-156">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-157">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-157">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-158">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-158">The name of the database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="f7965-159">レプリケーション リンク ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7965-159">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-162">データベース レプリケーション リンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7965-162">Gets a database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f7965-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IReplicationLinksOperations.ListByDatabaseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatabaseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;&gt;" Usage="iReplicationLinksOperations.ListByDatabaseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationLink&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f7965-166">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="f7965-167">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="f7965-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="f7965-168">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-168">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="f7965-169">リンクを取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="f7965-169">The name of the database to retrieve links for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f7965-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f7965-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7965-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f7965-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7965-172">データベースのレプリケーション リンクを示します。</span><span class="sxs-lookup"><span data-stu-id="f7965-172">Lists a database's replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f7965-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f7965-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f7965-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f7965-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>