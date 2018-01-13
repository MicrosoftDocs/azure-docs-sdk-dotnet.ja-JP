<Type Name="IPipelinesOperations" FullName="Microsoft.Azure.Management.DataFactory.IPipelinesOperations">
  <TypeSignature Language="C#" Value="public interface IPipelinesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelinesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.IPipelinesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelinesOperations" />
  <TypeSignature Language="F#" Value="type IPipelinesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f24ae-101">PipelinesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-101">PipelinesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string factoryName, string pipelineName, Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string factoryName, string pipelineName, class Microsoft.Azure.Management.DataFactory.Models.PipelineResource pipeline, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.PipelineResource,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataFactory.Models.PipelineResource * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="iPipelinesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, factoryName, pipelineName, pipeline, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineResource" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f24ae-102">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f24ae-102">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f24ae-103">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-103">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="f24ae-104">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-104">The pipeline name.</span></span>
            </param>
        <param name="pipeline">
            <span data-ttu-id="f24ae-105">リソース定義をパイプラインです。</span><span class="sxs-lookup"><span data-stu-id="f24ae-105">Pipeline resource definition.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="f24ae-106">パイプラインのエンティティの ETag です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-106">ETag of the pipeline entity.</span></span>  <span data-ttu-id="f24ae-107">更新については、対象の既存のエンティティが一致していることもできますのみ指定する必要があります \* の無条件更新します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-107">Should only be specified for update, for which it should match existing entity or can be \* for unconditional update.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-110">作成するか、パイプラインを更新します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-110">Creates or updates a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f24ae-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateRunWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;&gt; CreateRunWithHttpMessagesAsync (string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;&gt; CreateRunWithHttpMessagesAsync(string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.CreateRunWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateRunWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;&gt;" Usage="iPipelinesOperations.CreateRunWithHttpMessagesAsync (resourceGroupName, factoryName, pipelineName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.CreateRunResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f24ae-114">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f24ae-114">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f24ae-115">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-115">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="f24ae-116">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-116">The pipeline name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f24ae-117">パイプラインのパラメーターを実行します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-117">Parameters of the pipeline run.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-120">パイプラインの実行を作成します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-120">Creates a run of a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f24ae-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iPipelinesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, factoryName, pipelineName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f24ae-124">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f24ae-124">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f24ae-125">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-125">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="f24ae-126">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-126">The pipeline name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-129">パイプラインを削除します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-129">Deletes a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string factoryName, string pipelineName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string factoryName, string pipelineName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;" Usage="iPipelinesOperations.GetWithHttpMessagesAsync (resourceGroupName, factoryName, pipelineName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f24ae-132">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f24ae-132">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f24ae-133">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-133">The factory name.</span></span>
            </param>
        <param name="pipelineName">
            <span data-ttu-id="f24ae-134">パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-134">The pipeline name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-137">パイプラインを取得します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-137">Gets a pipeline.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f24ae-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt; ListByFactoryNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.ListByFactoryNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt;" Usage="iPipelinesOperations.ListByFactoryNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="f24ae-141">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-141">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-144">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-144">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f24ae-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByFactoryWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync (string resourceGroupName, string factoryName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt; ListByFactoryWithHttpMessagesAsync(string resourceGroupName, string factoryName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.IPipelinesOperations.ListByFactoryWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByFactoryWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt;" Usage="iPipelinesOperations.ListByFactoryWithHttpMessagesAsync (resourceGroupName, factoryName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataFactory.Models.PipelineResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="factoryName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f24ae-148">リソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="f24ae-148">The resource group name.</span></span>
            </param>
        <param name="factoryName">
            <span data-ttu-id="f24ae-149">ファクトリの名前です。</span><span class="sxs-lookup"><span data-stu-id="f24ae-149">The factory name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="f24ae-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f24ae-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f24ae-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f24ae-152">パイプラインの一覧を示します。</span><span class="sxs-lookup"><span data-stu-id="f24ae-152">Lists pipelines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.DataFactory.Models.ErrorResponseException">
            <span data-ttu-id="f24ae-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="f24ae-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f24ae-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="f24ae-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>