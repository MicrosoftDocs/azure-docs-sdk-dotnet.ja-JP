<Type Name="IServerCommunicationLinksOperations" FullName="Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations">
  <TypeSignature Language="C#" Value="public interface IServerCommunicationLinksOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServerCommunicationLinksOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServerCommunicationLinksOperations" />
  <TypeSignature Language="F#" Value="type IServerCommunicationLinksOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf2d8-101">ServerCommunicationLinksOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-101">ServerCommunicationLinksOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;" Usage="iServerCommunicationLinksOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, communicationLinkName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bf2d8-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bf2d8-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bf2d8-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-104">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="bf2d8-105">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-105">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bf2d8-106">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-106">The required parameters for creating a server communication link.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf2d8-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf2d8-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf2d8-109">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-109">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bf2d8-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf2d8-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf2d8-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string communicationLinkName, Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string communicationLinkName, class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;" Usage="iServerCommunicationLinksOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, communicationLinkName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bf2d8-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bf2d8-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bf2d8-115">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-115">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="bf2d8-116">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-116">The name of the server communication link.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bf2d8-117">サーバーへの通信のリンクを作成するための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-117">The required parameters for creating a server communication link.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf2d8-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf2d8-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf2d8-120">サーバーへの通信のリンクを作成します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-120">Creates a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bf2d8-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf2d8-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf2d8-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string communicationLinkName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string communicationLinkName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iServerCommunicationLinksOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, communicationLinkName, customHeaders, cancellationToken)" />
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
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bf2d8-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bf2d8-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bf2d8-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-126">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="bf2d8-127">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-127">The name of the server communication link.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf2d8-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf2d8-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf2d8-130">サーバーへの通信のリンクを削除します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-130">Deletes a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bf2d8-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf2d8-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string communicationLinkName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string communicationLinkName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;" Usage="iServerCommunicationLinksOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, communicationLinkName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="communicationLinkName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bf2d8-133">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bf2d8-134">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bf2d8-135">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-135">The name of the server.</span></span>
            </param>
        <param name="communicationLinkName">
            <span data-ttu-id="bf2d8-136">サーバーの通信リンクの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-136">The name of the server communication link.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf2d8-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf2d8-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf2d8-139">サーバー通信リンクを返します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-139">Returns a server communication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bf2d8-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf2d8-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf2d8-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IServerCommunicationLinksOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;&gt;" Usage="iServerCommunicationLinksOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.ServerCommunicationLink&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bf2d8-143">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bf2d8-144">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bf2d8-145">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-145">The name of the server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bf2d8-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf2d8-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf2d8-148">サーバー通信リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-148">Gets a list of server communication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bf2d8-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bf2d8-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bf2d8-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bf2d8-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>