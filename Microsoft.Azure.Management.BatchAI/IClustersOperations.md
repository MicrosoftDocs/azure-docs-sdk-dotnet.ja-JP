<Type Name="IClustersOperations" FullName="Microsoft.Azure.Management.BatchAI.IClustersOperations">
  <TypeSignature Language="C#" Value="public interface IClustersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClustersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.IClustersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClustersOperations" />
  <TypeSignature Language="F#" Value="type IClustersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="61e15-101">ClustersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="61e15-101">ClustersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="iClustersOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, clusterName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-103">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-103">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-104">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-104">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-105">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-105">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="61e15-106">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="61e15-106">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-109">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="61e15-109">Adds a cluster.</span></span> <span data-ttu-id="61e15-110">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="61e15-110">A cluster is a collection of compute nodes.</span></span>
            <span data-ttu-id="61e15-111">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="61e15-111">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string clusterName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string clusterName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iClustersOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, clusterName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-115">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-115">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-116">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-116">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-117">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-117">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-118">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-118">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-121">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="61e15-121">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="iClustersOperations.CreateWithHttpMessagesAsync (resourceGroupName, clusterName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-124">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-124">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-125">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-125">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-126">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-126">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-127">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-127">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="61e15-128">クラスターの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="61e15-128">The parameters to provide for cluster creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-131">クラスターを追加します。</span><span class="sxs-lookup"><span data-stu-id="61e15-131">Adds a cluster.</span></span> <span data-ttu-id="61e15-132">クラスターとは、コンピューティング ノードのコレクションです。</span><span class="sxs-lookup"><span data-stu-id="61e15-132">A cluster is a collection of compute nodes.</span></span>
            <span data-ttu-id="61e15-133">同じクラスター上に複数のジョブを実行できます。</span><span class="sxs-lookup"><span data-stu-id="61e15-133">Multiple jobs can be run on the same cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-134">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-134">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-135">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-135">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string clusterName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string clusterName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iClustersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, clusterName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-137">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-138">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-138">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-139">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-139">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-140">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-140">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-143">クラスターを削除します。</span><span class="sxs-lookup"><span data-stu-id="61e15-143">Deletes a Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string clusterName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string clusterName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="iClustersOperations.GetWithHttpMessagesAsync (resourceGroupName, clusterName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-146">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-147">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-147">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-148">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-148">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-149">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-149">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-152">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-152">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;" Usage="iClustersOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="61e15-156">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="61e15-156">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-157">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-157">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-159">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-159">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-161">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-161">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions clustersListByResourceGroupOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;" Usage="iClustersOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, clustersListByResourceGroupOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clustersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListByResourceGroupOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-163">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-163">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clustersListByResourceGroupOptions">
            <span data-ttu-id="61e15-164">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="61e15-164">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-167">指定されたリソース グループ内で関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-167">Gets information about the Clusters associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;" Usage="iClustersOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="61e15-171">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="61e15-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-172">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-172">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-174">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-174">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-175">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-175">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-176">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-176">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListRemoteLoginInformationNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRemoteLoginInformationNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;" Usage="iClustersOperations.ListRemoteLoginInformationNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="61e15-178">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="61e15-178">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-181">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-181">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-182">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-182">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-183">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-183">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-184">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-184">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationWithHttpMessagesAsync (string resourceGroupName, string clusterName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationWithHttpMessagesAsync(string resourceGroupName, string clusterName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListRemoteLoginInformationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRemoteLoginInformationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;" Usage="iClustersOperations.ListRemoteLoginInformationWithHttpMessagesAsync (resourceGroupName, clusterName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-185">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-185">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-186">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-186">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-187">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-187">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-188">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-188">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-191">IP アドレス、クラスター内のすべてのコンピューティング ノードのポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-191">Get the IP address, port of all the compute nodes in the cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions clustersListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;" Usage="iClustersOperations.ListWithHttpMessagesAsync (clustersListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clustersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.ClustersListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="clustersListOptions">
            <span data-ttu-id="61e15-195">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="61e15-195">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-198">サブスクリプションに関連付けられている、クラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="61e15-198">Gets information about the Clusters associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string clusterName, Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string clusterName, class Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IClustersOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;" Usage="iClustersOperations.UpdateWithHttpMessagesAsync (resourceGroupName, clusterName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Cluster&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="clusterName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.ClusterUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="61e15-202">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="61e15-202">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="clusterName">
            <span data-ttu-id="61e15-203">指定されたリソース グループ内でクラスターの名前。</span><span class="sxs-lookup"><span data-stu-id="61e15-203">The name of the cluster within the specified resource group.</span></span>
            <span data-ttu-id="61e15-204">クラスター名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="61e15-204">Cluster names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="61e15-205">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="61e15-205">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="61e15-206">クラスター更新プログラムの追加のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="61e15-206">Additional parameters for cluster update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="61e15-207">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="61e15-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="61e15-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="61e15-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="61e15-209">特定のクラスターのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="61e15-209">Update the properties of a given cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="61e15-210">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-210">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="61e15-211">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-211">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="61e15-212">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="61e15-212">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>