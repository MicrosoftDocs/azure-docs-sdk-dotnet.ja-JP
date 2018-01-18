<Type Name="IFunctionsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations">
  <TypeSignature Language="C#" Value="public interface IFunctionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFunctionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFunctionsOperations" />
  <TypeSignature Language="F#" Value="type IFunctionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9b92b-101">FunctionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="9b92b-101">FunctionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync (string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync(string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.BeginTestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginTestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iFunctionsOperations.BeginTestWithHttpMessagesAsync (resourceGroupName, jobName, functionName, function, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-104">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-104">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-105">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-105">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="9b92b-106">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="9b92b-106">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="9b92b-107">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-107">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-110">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="9b92b-110">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="9b92b-111">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-111">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsCreateOrReplaceHeaders&gt;&gt;" Usage="iFunctionsOperations.CreateOrReplaceWithHttpMessagesAsync (function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="function">
            <span data-ttu-id="9b92b-115">新しい関数を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される関数の定義。</span><span class="sxs-lookup"><span data-stu-id="9b92b-115">The definition of the function that will be used to create a new function or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-116">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-116">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-118">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-118">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-119">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-119">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="9b92b-120">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="9b92b-120">The ETag of the function.</span></span> <span data-ttu-id="9b92b-121">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-121">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="9b92b-122">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-122">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="9b92b-123">設定 ' \*' を作成する新しい関数を既存の関数の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="9b92b-123">Set to '\*' to allow a new function to be created, but to prevent updating an existing function.</span></span> <span data-ttu-id="9b92b-124">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="9b92b-124">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-127">関数を作成するか、既存のストリーミング ジョブの下で既に既存の関数を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-127">Creates a function or replaces an already existing function under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string jobName, string functionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string jobName, string functionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iFunctionsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, jobName, functionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-133">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-133">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-134">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-134">The name of the function.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-137">ストリーミング ジョブから関数を削除します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-137">Deletes a function from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string functionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string functionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders&gt;&gt;" Usage="iFunctionsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, functionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-140">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-140">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-141">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-141">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-142">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-142">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-143">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-143">The name of the function.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-146">指定された関数の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-146">Gets details about the specified function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.ListByStreamingJobNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt;" Usage="iFunctionsOperations.ListByStreamingJobNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="9b92b-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="9b92b-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-153">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-153">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync (string resourceGroupName, string jobName, string select = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync(string resourceGroupName, string jobName, string select, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.ListByStreamingJobWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt;" Usage="iFunctionsOperations.ListByStreamingJobWithHttpMessagesAsync (resourceGroupName, jobName, select, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-157">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-157">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-158">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-158">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-159">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-159">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="9b92b-160">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="9b92b-160">The $select OData query parameter.</span></span> <span data-ttu-id="9b92b-161">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="9b92b-161">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-164">すべての指定したストリーミング ジョブの下で関数の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-164">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; RetrieveDefaultDefinitionWithHttpMessagesAsync (string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; RetrieveDefaultDefinitionWithHttpMessagesAsync(string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.RetrieveDefaultDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveDefaultDefinitionWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="iFunctionsOperations.RetrieveDefaultDefinitionWithHttpMessagesAsync (resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-168">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-168">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-169">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-169">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-170">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-170">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-171">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-171">The name of the function.</span></span>
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            <span data-ttu-id="9b92b-172">パラメーターの既定の定義を取得する関数の種類を指定するために使用します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-172">Parameters used to specify the type of function to retrieve the default definition for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-175">指定されたパラメーターに基づいて関数の既定の定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-175">Retrieves the default definition of a function based on the parameters specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync (string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync(string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.TestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iFunctionsOperations.TestWithHttpMessagesAsync (resourceGroupName, jobName, functionName, function, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-179">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-179">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-180">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-180">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-181">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-181">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-182">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-182">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="9b92b-183">指定された関数が既に存在しない場合、このパラメーターは、テストするためのもので、フル機能定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="9b92b-183">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="9b92b-184">既に指定された関数が存在する場合は、この省略可能ですが、または指定した場合、既存の関数をテストする場合は null、(PATCH 操作) とまったく同じ既存の関数に対応するプロパティを指定したプロパティが上書きされますおよび結果として得られる関数がテストされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-184">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-187">関数の提供情報が有効かどうか。</span><span class="sxs-lookup"><span data-stu-id="9b92b-187">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="9b92b-188">関数の背後にある、基になる web サービスへの接続をテストまたは指定された関数のコードの構文が正しいことを確認してから範囲で指定できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-188">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsUpdateHeaders&gt;&gt;" Usage="iFunctionsOperations.UpdateWithHttpMessagesAsync (function, resourceGroupName, jobName, functionName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="function">
            <span data-ttu-id="9b92b-192">関数オブジェクトを指定します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-192">A function object.</span></span> <span data-ttu-id="9b92b-193">ここで指定されたプロパティ (ie 既存の関数に対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="9b92b-193">The properties specified here will overwrite the corresponding properties in the existing function (ie. Those properties will be updated).</span></span> <span data-ttu-id="9b92b-194">ここでは null に設定されている任意のプロパティがありことを意味の既存の関数に対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="9b92b-194">Any properties that are set to null here will mean that the corresponding property in the existing function will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="9b92b-195">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="9b92b-196">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="9b92b-197">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-197">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="9b92b-198">関数の名前。</span><span class="sxs-lookup"><span data-stu-id="9b92b-198">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="9b92b-199">関数の ETag です。</span><span class="sxs-lookup"><span data-stu-id="9b92b-199">The ETag of the function.</span></span> <span data-ttu-id="9b92b-200">常に現在の関数を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-200">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="9b92b-201">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-201">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9b92b-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9b92b-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="9b92b-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9b92b-204">既存のストリーミング ジョブの下にある既存の関数を更新します。</span><span class="sxs-lookup"><span data-stu-id="9b92b-204">Updates an existing function under an existing streaming job.</span></span> <span data-ttu-id="9b92b-205">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-205">This can be used to partially update (ie.</span></span> <span data-ttu-id="9b92b-206">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは関数の定義に影響を与えず関数。</span><span class="sxs-lookup"><span data-stu-id="9b92b-206">update one or two properties) a function without affecting the rest the job or function definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9b92b-207">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-207">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9b92b-208">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-208">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9b92b-209">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="9b92b-209">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>