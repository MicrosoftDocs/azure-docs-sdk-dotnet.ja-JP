<Type Name="IFileServersOperations" FullName="Microsoft.Azure.Management.BatchAI.IFileServersOperations">
  <TypeSignature Language="C#" Value="public interface IFileServersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileServersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.IFileServersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileServersOperations" />
  <TypeSignature Language="F#" Value="type IFileServersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0814-101">FileServersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c0814-101">FileServersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="iFileServersOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, fileServerName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="c0814-103">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0814-103">The name of the file server within the specified resource group.</span></span>
            <span data-ttu-id="c0814-104">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c0814-104">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="c0814-105">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c0814-105">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0814-106">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0814-106">The parameters to provide for file server creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-109">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="c0814-109">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string fileServerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string fileServerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileServersOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, fileServerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-113">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-113">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="c0814-114">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0814-114">The name of the file server within the specified resource group.</span></span>
            <span data-ttu-id="c0814-115">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c0814-115">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="c0814-116">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c0814-116">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-119">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0814-119">Delete a file Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string fileServerName, Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string fileServerName, class Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="iFileServersOperations.CreateWithHttpMessagesAsync (resourceGroupName, fileServerName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-122">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="c0814-123">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0814-123">The name of the file server within the specified resource group.</span></span>
            <span data-ttu-id="c0814-124">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c0814-124">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="c0814-125">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c0814-125">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0814-126">ファイル サーバーの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c0814-126">The parameters to provide for file server creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-129">ファイル サーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="c0814-129">Creates a file server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string fileServerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string fileServerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFileServersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, fileServerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-133">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="c0814-134">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0814-134">The name of the file server within the specified resource group.</span></span>
            <span data-ttu-id="c0814-135">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c0814-135">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="c0814-136">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c0814-136">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-139">ファイル サーバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="c0814-139">Delete a file Server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string fileServerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string fileServerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;" Usage="iFileServersOperations.GetWithHttpMessagesAsync (resourceGroupName, fileServerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-142">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-142">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServerName">
            <span data-ttu-id="c0814-143">指定されたリソース グループ内でファイル サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c0814-143">The name of the file server within the specified resource group.</span></span>
            <span data-ttu-id="c0814-144">ファイル サーバー名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="c0814-144">File server names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="c0814-145">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="c0814-145">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-148">指定されたクラスターに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0814-148">Gets information about the specified Cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;" Usage="iFileServersOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c0814-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0814-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-155">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0814-155">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions fileServersListByResourceGroupOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;" Usage="iFileServersOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, fileServersListByResourceGroupOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fileServersListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListByResourceGroupOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c0814-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="c0814-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="fileServersListByResourceGroupOptions">
            <span data-ttu-id="c0814-160">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="c0814-160">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-163">ファイル サーバーとそのプロパティが指定されたリソース グループ内で関連付けの書式設定された一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c0814-163">Gets a formatted list of file servers and their properties associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;" Usage="iFileServersOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c0814-167">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c0814-167">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-168">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-168">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-170">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="c0814-170">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-171">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-171">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-172">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-172">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions fileServersListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IFileServersOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;" Usage="iFileServersOperations.ListWithHttpMessagesAsync (fileServersListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.FileServer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fileServersListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.FileServersListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fileServersListOptions">
            <span data-ttu-id="c0814-174">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="c0814-174">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c0814-175">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c0814-175">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0814-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c0814-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0814-177">所定のサブスクリプション (とそのサブスクリプション内のすべてのリソース グループ間で) 使用可能なすべてのファイル サーバーを一覧表示</span><span class="sxs-lookup"><span data-stu-id="c0814-177">To list all the file servers available under the given subscription (and across all resource groups within that subscription)</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c0814-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c0814-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c0814-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c0814-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>