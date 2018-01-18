<Type Name="ILinkedServicesOperations" FullName="Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations">
  <TypeSignature Language="C#" Value="public interface ILinkedServicesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILinkedServicesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILinkedServicesOperations" />
  <TypeSignature Language="F#" Value="type ILinkedServicesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c071-101">LinkedServicesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="1c071-101">LinkedServicesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string linkedServiceName, Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string linkedServiceName, class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.LinkedService,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.LinkedService * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;" Usage="iLinkedServicesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, linkedServiceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.LinkedService" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1c071-102">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-102">The name of the resource group to get.</span></span> <span data-ttu-id="1c071-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1c071-103">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1c071-104">LinkedServices リソースを格納する、ログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="1c071-104">Name of the Log Analytics Workspace that will contain the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="1c071-105">LinkedServices リソースの名前</span><span class="sxs-lookup"><span data-stu-id="1c071-105">Name of the linkedServices resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c071-106">作成またはリンクされたサービスの更新に必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="1c071-106">The parameters required to create or update a linked service.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1c071-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1c071-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c071-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c071-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c071-109">作成またはリンクされたサービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c071-109">Create or update a linked service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1c071-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1c071-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1c071-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string linkedServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string linkedServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iLinkedServicesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, workspaceName, linkedServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1c071-113">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-113">The name of the resource group to get.</span></span> <span data-ttu-id="1c071-114">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1c071-114">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1c071-115">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="1c071-115">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="1c071-116">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-116">Name of the linked service.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1c071-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1c071-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c071-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c071-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c071-119">リンクされたサービス インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c071-119">Deletes a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1c071-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1c071-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string linkedServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string linkedServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;" Usage="iLinkedServicesOperations.GetWithHttpMessagesAsync (resourceGroupName, workspaceName, linkedServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1c071-122">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-122">The name of the resource group to get.</span></span> <span data-ttu-id="1c071-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1c071-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1c071-124">LinkedServices リソースを含むログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="1c071-124">Name of the Log Analytics Workspace that contains the linkedServices resource</span></span>
            </param>
        <param name="linkedServiceName">
            <span data-ttu-id="1c071-125">リンクされたサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-125">Name of the linked service.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1c071-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1c071-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c071-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c071-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c071-128">リンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c071-128">Gets a linked service instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1c071-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1c071-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1c071-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.ILinkedServicesOperations.ListByWorkspaceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;&gt;" Usage="iLinkedServicesOperations.ListByWorkspaceWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkedService&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1c071-132">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c071-132">The name of the resource group to get.</span></span> <span data-ttu-id="1c071-133">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1c071-133">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="1c071-134">リンクされたサービスを含むログ分析ワークスペースの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c071-134">Name of the Log Analytics Workspace that contains the linked services.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="1c071-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="1c071-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c071-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c071-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c071-137">ワークスペースにリンクされたサービス インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c071-137">Gets the linked services instances in a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="1c071-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="1c071-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1c071-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="1c071-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>