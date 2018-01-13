<Type Name="IInputsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations">
  <TypeSignature Language="C#" Value="public interface IInputsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IInputsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IInputsOperations" />
  <TypeSignature Language="F#" Value="type IInputsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="76882-101">InputsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="76882-101">InputsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; BeginTestWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.BeginTestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginTestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iInputsOperations.BeginTestWithHttpMessagesAsync (resourceGroupName, jobName, inputName, input, customHeaders, cancellationToken)" />
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
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-104">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-104">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-105">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-105">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="76882-106">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="76882-106">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="76882-107">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="76882-107">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-110">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="76882-110">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt;" Usage="iInputsOperations.CreateOrReplaceWithHttpMessagesAsync (input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="input">
            <span data-ttu-id="76882-114">新しい入力を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される入力の定義。</span><span class="sxs-lookup"><span data-stu-id="76882-114">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-115">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-115">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-116">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-116">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-117">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-117">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-118">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-118">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="76882-119">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="76882-119">The ETag of the input.</span></span> <span data-ttu-id="76882-120">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="76882-120">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="76882-121">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="76882-121">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="76882-122">設定 ' \*' を作成するが、既存の入力の更新を防ぐために、新しい入力を許可します。</span><span class="sxs-lookup"><span data-stu-id="76882-122">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="76882-123">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="76882-123">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-126">入力を作成するか、既存のストリーミング ジョブの下で、既に既存の入力を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="76882-126">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iInputsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, jobName, inputName, customHeaders, cancellationToken)" />
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
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-130">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-130">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-131">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-132">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-132">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-133">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-133">The name of the input.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-136">ストリーミング ジョブから入力を削除します。</span><span class="sxs-lookup"><span data-stu-id="76882-136">Deletes an input from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt;" Usage="iInputsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, inputName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-139">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-139">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-140">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-141">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-141">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-142">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-142">The name of the input.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-145">詳細については、指定された入力を取得します。</span><span class="sxs-lookup"><span data-stu-id="76882-145">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-147">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-147">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-148">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-148">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.ListByStreamingJobNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;" Usage="iInputsOperations.ListByStreamingJobNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="76882-149">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="76882-149">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-152">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="76882-152">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync (string resourceGroupName, string jobName, string select = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt; ListByStreamingJobWithHttpMessagesAsync(string resourceGroupName, string jobName, string select, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.ListByStreamingJobWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByStreamingJobWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;" Usage="iInputsOperations.ListByStreamingJobWithHttpMessagesAsync (resourceGroupName, jobName, select, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="76882-156">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-157">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-158">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-158">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="76882-159">$Select OData クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="76882-159">The $select OData query parameter.</span></span> <span data-ttu-id="76882-160">これは、応答に含める構造型プロパティのコンマ区切りの一覧または"*"すべてのプロパティを含めます。既定では、診断を除くすべてのプロパティが返されます。現在のみを受け入れる '*' 有効な値として。</span><span class="sxs-lookup"><span data-stu-id="76882-160">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-163">すべての指定したストリーミング ジョブの下にある入力の一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="76882-163">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync (string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt; TestWithHttpMessagesAsync(string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.TestWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TestWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;&gt;" Usage="iInputsOperations.TestWithHttpMessagesAsync (resourceGroupName, jobName, inputName, input, customHeaders, cancellationToken)" />
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
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-167">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-168">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-169">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-169">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-170">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-170">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="76882-171">指定された入力が既に存在しない場合、このパラメーターは、テストするためのもので、完全な入力定義を含める必要があります。</span><span class="sxs-lookup"><span data-stu-id="76882-171">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="76882-172">既に指定した入力が存在する場合、このパラメーターは省略可能、既存の現状有姿の入力をテストする場合は null またはプロパティが指定されましたが (PATCH 操作) とまったく同じ既存の入力と、その結果で対応するプロパティを上書き指定した場合入力がテストされます。</span><span class="sxs-lookup"><span data-stu-id="76882-172">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-175">入力のデータ ソースが到達可能で、Azure Stream Analytics サービスで使用できるかどうかをテストします。</span><span class="sxs-lookup"><span data-stu-id="76882-175">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input, class Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.IInputsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input, Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt;" Usage="iInputsOperations.UpdateWithHttpMessagesAsync (input, resourceGroupName, jobName, inputName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input,Microsoft.Azure.Management.StreamAnalytics.Models.InputsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="input">
            <span data-ttu-id="76882-179">入力オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="76882-179">An Input object.</span></span> <span data-ttu-id="76882-180">ここで指定されたプロパティ (ie 既存の入力の対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="76882-180">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="76882-181">ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="76882-181">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76882-182">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-182">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="76882-183">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="76882-183">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="76882-184">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="76882-184">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="76882-185">入力の名前。</span><span class="sxs-lookup"><span data-stu-id="76882-185">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="76882-186">入力の ETag です。</span><span class="sxs-lookup"><span data-stu-id="76882-186">The ETag of the input.</span></span> <span data-ttu-id="76882-187">常に現在の入力を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="76882-187">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="76882-188">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="76882-188">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="76882-189">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="76882-189">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76882-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76882-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76882-191">既存のストリーミング ジョブの下で、既存の入力を更新します。</span><span class="sxs-lookup"><span data-stu-id="76882-191">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="76882-192">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="76882-192">This can be used to partially update (ie.</span></span> <span data-ttu-id="76882-193">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは入力の定義に影響を与えずに入力します。</span><span class="sxs-lookup"><span data-stu-id="76882-193">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="76882-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="76882-195">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="76882-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="76882-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>