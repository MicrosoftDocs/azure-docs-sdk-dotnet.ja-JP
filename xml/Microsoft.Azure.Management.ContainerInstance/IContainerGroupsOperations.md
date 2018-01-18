<Type Name="IContainerGroupsOperations" FullName="Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IContainerGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerGroupsOperations" />
  <TypeSignature Language="F#" Value="type IContainerGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f596e-101">ContainerGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f596e-101">ContainerGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup containerGroup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="iContainerGroupsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, containerGroupName, containerGroup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerGroup" Type="Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f596e-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-102">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="f596e-103">コンテナーのグループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-103">The name of the container group.</span></span>
            </param>
        <param name="containerGroup">
            <span data-ttu-id="f596e-104">作成または更新するコンテナーのグループのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="f596e-104">The properties of the container group to be created or updated.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-107">作成またはコンテナーのグループを更新します。</span><span class="sxs-lookup"><span data-stu-id="f596e-107">Create or update container groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-108">作成または指定された構成でコンテナーのグループを更新します。</span><span class="sxs-lookup"><span data-stu-id="f596e-108">Create or update container groups with specified configurations.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="iContainerGroupsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, containerGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f596e-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-112">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="f596e-113">コンテナーのグループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-113">The name of the container group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-116">指定されたコンテナーのグループを削除します。</span><span class="sxs-lookup"><span data-stu-id="f596e-116">Delete the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-117">指定したサブスクリプションで指定されたコンテナーのグループとリソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="f596e-117">Delete the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="f596e-118">操作では、ボリュームなどのユーザーによって提供される他のリソースは削除されません。</span><span class="sxs-lookup"><span data-stu-id="f596e-118">The operation does not delete other resources provided by the user, such as volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;" Usage="iContainerGroupsOperations.GetWithHttpMessagesAsync (resourceGroupName, containerGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f596e-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-122">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="f596e-123">コンテナーのグループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-123">The name of the container group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-126">指定されたコンテナーのグループのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-126">Get the properties of the specified container group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-127">指定したサブスクリプションで指定されたコンテナーのグループおよびリソース グループのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-127">Gets the properties of the specified container group in the specified subscription and resource group.</span></span> <span data-ttu-id="f596e-128">操作は、ポリシー、IP アドレスの種類、OS の種類、状態、およびボリューム コンテナー、イメージ レジストリの資格情報を含む各コンテナー グループのプロパティが再起動を返します。</span><span class="sxs-lookup"><span data-stu-id="f596e-128">The operation returns the properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;" Usage="iContainerGroupsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f596e-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f596e-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-135">指定したサブスクリプションとリソース グループ内のコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-135">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-136">指定したサブスクリプションとリソース グループ内のコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-136">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="f596e-137">この操作は、コンテナー、イメージ レジストリの資格情報、再起動ポリシーによって、IP アドレスの種類、OS の種類、状態、およびボリュームを含む各コンテナーのグループのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f596e-137">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;" Usage="iContainerGroupsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f596e-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="f596e-141">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-144">指定したサブスクリプションとリソース グループ内のコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-144">Get a list of container groups in the specified subscription and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-145">指定したサブスクリプションとリソース グループ内のコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-145">Get a list of container groups in a specified subscription and resource group.</span></span> <span data-ttu-id="f596e-146">この操作は、コンテナー、イメージ レジストリの資格情報、再起動ポリシーによって、IP アドレスの種類、OS の種類、状態、およびボリュームを含む各コンテナーのグループのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f596e-146">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;" Usage="iContainerGroupsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f596e-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f596e-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f596e-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-153">指定されたサブスクリプションのコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-153">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-154">指定されたサブスクリプションのコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-154">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="f596e-155">この操作は、コンテナー、イメージ レジストリの資格情報、再起動ポリシーによって、IP アドレスの種類、OS の種類、状態、およびボリュームを含む各コンテナーのグループのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f596e-155">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerGroupsOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;" Usage="iContainerGroupsOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerInstance.Models.ContainerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="f596e-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f596e-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f596e-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f596e-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f596e-161">指定されたサブスクリプションのコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-161">Get a list of container groups in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="f596e-162">指定されたサブスクリプションのコンテナーのグループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f596e-162">Get a list of container groups in the specified subscription.</span></span> <span data-ttu-id="f596e-163">この操作は、コンテナー、イメージ レジストリの資格情報、再起動ポリシーによって、IP アドレスの種類、OS の種類、状態、およびボリュームを含む各コンテナーのグループのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="f596e-163">This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="f596e-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f596e-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f596e-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f596e-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>