<Type Name="IJobsOperations" FullName="Microsoft.Azure.Management.BatchAI.IJobsOperations">
  <TypeSignature Language="C#" Value="public interface IJobsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.IJobsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobsOperations" />
  <TypeSignature Language="F#" Value="type IJobsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce7f4-101">JobsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-101">JobsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="iJobsOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, jobName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-103">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-103">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-104">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-104">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-105">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-105">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ce7f4-106">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-106">The parameters to provide for job creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-109">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-109">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
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
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-113">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-113">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-114">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-114">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-115">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-115">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-116">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-116">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-119">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-119">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginTerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginTerminateWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginTerminateWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.BeginTerminateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginTerminateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobsOperations.BeginTerminateWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
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
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-122">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-122">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-123">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-123">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-124">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-124">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-125">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-125">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-128">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-128">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="iJobsOperations.CreateWithHttpMessagesAsync (resourceGroupName, jobName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-131">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-132">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-132">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-133">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-133">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-134">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-134">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ce7f4-135">ジョブの作成を提供するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-135">The parameters to provide for job creation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-138">クラスターで実行されるジョブを追加します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-138">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
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
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-142">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-142">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-143">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-143">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-144">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-144">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-145">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-145">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-148">指定されたバッチ AI ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-148">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="iJobsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-152">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-152">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-153">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-153">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-154">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-154">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-157">指定したバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-157">Gets information about the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;" Usage="iJobsOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="ce7f4-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-164">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-164">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;" Usage="iJobsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, jobsListByResourceGroupOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobsListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-168">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-168">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobsListByResourceGroupOptions">
            <span data-ttu-id="ce7f4-169">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="ce7f4-169">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-172">指定されたリソース グループ内で関連付けられているバッチ AI ジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-172">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;" Usage="iJobsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="ce7f4-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-179">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-179">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt; ListOutputFilesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt; ListOutputFilesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListOutputFilesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOutputFilesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt;" Usage="iJobsOperations.ListOutputFilesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="ce7f4-183">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-186">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-186">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt; ListOutputFilesWithHttpMessagesAsync (string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt; ListOutputFilesWithHttpMessagesAsync(string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListOutputFilesWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListOutputFilesWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt;" Usage="iJobsOperations.ListOutputFilesWithHttpMessagesAsync (resourceGroupName, jobName, jobsListOutputFilesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="jobsListOutputFilesOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-190">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-190">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-191">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-191">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-192">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-192">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-193">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-193">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="jobsListOutputFilesOptions">
            <span data-ttu-id="ce7f4-194">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="ce7f4-194">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-197">(場合にのみ、出力ディレクトリは、Azure のファイル共有または Azure ストレージ コンテナーには) は、指定された出力ディレクトリ内のすべてのファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-197">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-198">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-198">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-199">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-199">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-200">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-200">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListRemoteLoginInformationNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRemoteLoginInformationNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;" Usage="iJobsOperations.ListRemoteLoginInformationNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
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
            <span data-ttu-id="ce7f4-201">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-201">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-204">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-204">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt; ListRemoteLoginInformationWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListRemoteLoginInformationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRemoteLoginInformationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;&gt;" Usage="iJobsOperations.ListRemoteLoginInformationWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
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
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-208">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-208">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-209">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-209">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-210">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-210">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-211">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-211">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-214">ジョブの実行に使用されるすべてのコンピューティング ノードの IP アドレスとポート情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-214">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-215">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-215">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-216">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-216">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-217">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Management.BatchAI.Models.JobsListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Management.BatchAI.Models.JobsListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;" Usage="iJobsOperations.ListWithHttpMessagesAsync (jobsListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobsListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobsListOptions">
            <span data-ttu-id="ce7f4-218">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="ce7f4-218">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-219">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-221">サブスクリプションに関連付けられているジョブに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-221">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-222">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-222">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="ce7f4-223">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-223">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-224">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-224">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; TerminateWithHttpMessagesAsync (string resourceGroupName, string jobName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; TerminateWithHttpMessagesAsync(string resourceGroupName, string jobName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.IJobsOperations.TerminateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobsOperations.TerminateWithHttpMessagesAsync (resourceGroupName, jobName, customHeaders, cancellationToken)" />
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
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ce7f4-225">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-225">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="ce7f4-226">指定されたリソース グループ内でジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-226">The name of the job within the specified resource group.</span></span> <span data-ttu-id="ce7f4-227">ジョブ名には、およびダッシュ (-) とアンダー スコア (_) 文字の英数字の組み合わせのみを含めることができます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-227">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="ce7f4-228">名前は、1 ~ 64 文字以内でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-228">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="ce7f4-229">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-229">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ce7f4-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ce7f4-231">ジョブを終了します。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-231">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="ce7f4-232">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-232">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="ce7f4-233">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="ce7f4-233">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>