<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="03e0e-101">JobOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="03e0e-101">JobOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BuildWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; BuildWithHttpMessagesAsync (string accountName, Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; BuildWithHttpMessagesAsync(string accountName, class Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.BuildWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BuildWithHttpMessagesAsync : string * Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;" Usage="iJobOperations.BuildWithHttpMessagesAsync (accountName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.BuildJobParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-102">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-102">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="03e0e-103">ジョブを作成するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="03e0e-103">The parameters to build a job.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-106">ジョブの正確性と検証のため、指定された Data Lake Analytics アカウントに (コンパイル)、指定されたジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-106">Builds (compiles) the specified job in the specified Data Lake Analytics account for job correctness and validation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync (string accountName, Guid jobIdentity, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.CancelWithHttpMessagesAsync(System.String,System.Guid,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelWithHttpMessagesAsync : string * Guid * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.CancelWithHttpMessagesAsync (accountName, jobIdentity, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-110">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-110">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-111">キャンセルする JobInfo ID です。</span><span class="sxs-lookup"><span data-stu-id="03e0e-111">JobInfo ID to cancel.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-114">ジョブ ID で指定された実行中のジョブを取り消します</span><span class="sxs-lookup"><span data-stu-id="03e0e-114">Cancels the running job specified by the job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-116">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-116">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; CreateWithHttpMessagesAsync (string accountName, Guid jobIdentity, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; CreateWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.CreateWithHttpMessagesAsync(System.String,System.Guid,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * Guid * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;" Usage="iJobOperations.CreateWithHttpMessagesAsync (accountName, jobIdentity, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-117">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-117">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-118">送信されるジョブのジョブ ID (GUID)。</span><span class="sxs-lookup"><span data-stu-id="03e0e-118">The job ID (a GUID) for the job being submitted.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="03e0e-119">ジョブを送信するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="03e0e-119">The parameters to submit a job.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-122">指定された Data Lake Analytics アカウントへのジョブを送信します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-122">Submits a job to the specified Data Lake Analytics account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync (string accountName, Guid jobIdentity, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;bool&gt;&gt; ExistsWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.ExistsWithHttpMessagesAsync(System.String,System.Guid,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Guid * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool&gt;&gt;" Usage="iJobOperations.ExistsWithHttpMessagesAsync (accountName, jobIdentity, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-126">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-126">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-127">存在をテストする JobInfo ID です。</span><span class="sxs-lookup"><span data-stu-id="03e0e-127">JobInfo ID to test the existence of.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-130">指定したジョブ ID のジョブ情報の存在をテストします。</span><span class="sxs-lookup"><span data-stu-id="03e0e-130">Tests the existence of job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDebugDataPathWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;&gt; GetDebugDataPathWithHttpMessagesAsync (string accountName, Guid jobIdentity, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;&gt; GetDebugDataPathWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.GetDebugDataPathWithHttpMessagesAsync(System.String,System.Guid,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDebugDataPathWithHttpMessagesAsync : string * Guid * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;&gt;" Usage="iJobOperations.GetDebugDataPathWithHttpMessagesAsync (accountName, jobIdentity, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobDataPath&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-134">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-134">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-135">JobInfo id。</span><span class="sxs-lookup"><span data-stu-id="03e0e-135">JobInfo ID.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-138">ジョブ ID で指定されたジョブのデバッグ情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-138">Gets the job debug data information specified by the job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;&gt; GetStatisticsWithHttpMessagesAsync (string accountName, Guid jobIdentity, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;&gt; GetStatisticsWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.GetStatisticsWithHttpMessagesAsync(System.String,System.Guid,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStatisticsWithHttpMessagesAsync : string * Guid * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;&gt;" Usage="iJobOperations.GetStatisticsWithHttpMessagesAsync (accountName, jobIdentity, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-142">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-142">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-143">ジョブ情報の id。</span><span class="sxs-lookup"><span data-stu-id="03e0e-143">Job Information ID.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-146">指定されたジョブの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-146">Gets statistics of the specified job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; GetWithHttpMessagesAsync (string accountName, Guid jobIdentity, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt; GetWithHttpMessagesAsync(string accountName, valuetype System.Guid jobIdentity, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.GetWithHttpMessagesAsync(System.String,System.Guid,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Guid * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;" Usage="iJobOperations.GetWithHttpMessagesAsync (accountName, jobIdentity, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="jobIdentity" Type="System.Guid" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-150">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-150">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="jobIdentity">
            <span data-ttu-id="03e0e-151">JobInfo id。</span><span class="sxs-lookup"><span data-stu-id="03e0e-151">JobInfo ID.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-152">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-152">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-154">指定したジョブ ID のジョブ情報を取得します</span><span class="sxs-lookup"><span data-stu-id="03e0e-154">Gets the job information for the specified job ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-155">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-155">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-156">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-156">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-157">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-157">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt;" Usage="iJobOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="03e0e-158">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="03e0e-158">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-161">指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-161">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="03e0e-162">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="03e0e-162">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt; ListWithHttpMessagesAsync (string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt; ListWithHttpMessagesAsync(string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.IJobOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt;" Usage="iJobOperations.ListWithHttpMessagesAsync (accountName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="03e0e-166">ジョブの操作を実行する Azure Data Lake Analytics アカウント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-166">The Azure Data Lake Analytics account to execute job operations on.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="03e0e-167">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="03e0e-167">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="03e0e-168">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="03e0e-168">OData Select statement.</span></span> <span data-ttu-id="03e0e-169">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-169">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="03e0e-170">省略可能。</span><span class="sxs-lookup"><span data-stu-id="03e0e-170">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="03e0e-171">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="03e0e-171">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="03e0e-172">省略可能。</span><span class="sxs-lookup"><span data-stu-id="03e0e-172">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="03e0e-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="03e0e-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="03e0e-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="03e0e-175">指定された Data Lake Analytics アカウントに関連付けられている場合、ジョブを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="03e0e-175">Lists the jobs, if any, associated with the specified Data Lake Analytics account.</span></span> <span data-ttu-id="03e0e-176">応答には、存在する場合、結果の次のページへのリンクが含まれています。</span><span class="sxs-lookup"><span data-stu-id="03e0e-176">The response includes a link to the next page of results, if any.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="03e0e-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="03e0e-178">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-178">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="03e0e-179">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="03e0e-179">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>