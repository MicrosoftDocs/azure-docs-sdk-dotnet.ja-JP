<Type Name="ITransformationsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations">
  <TypeSignature Language="C#" Value="public interface ITransformationsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransformationsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransformationsOperations" />
  <TypeSignature Language="F#" Value="type ITransformationsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cc74b-101">TransformationsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-101">TransformationsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;" Usage="iTransformationsOperations.CreateOrReplaceWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            <span data-ttu-id="cc74b-102">新しい変換を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される変換の定義。</span><span class="sxs-lookup"><span data-stu-id="cc74b-102">The definition of the transformation that will be used to create a new transformation or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cc74b-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="cc74b-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="cc74b-105">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-105">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="cc74b-106">変換の名前です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-106">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cc74b-107">変換の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-107">The ETag of the transformation.</span></span> <span data-ttu-id="cc74b-108">常に現在の変換を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-108">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="cc74b-109">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-109">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="cc74b-110">設定 ' \*'、新しい変換を作成するが、既存の変換の更新を防ぐために使用できるようにします。</span><span class="sxs-lookup"><span data-stu-id="cc74b-110">Set to '\*' to allow a new transformation to be created, but to prevent updating an existing transformation.</span></span> <span data-ttu-id="cc74b-111">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="cc74b-111">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cc74b-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cc74b-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cc74b-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cc74b-114">変換を作成するか、既存のストリーミング ジョブの下で、既存の変換を置き換えます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-114">Creates a transformation or replaces an already existing transformation under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cc74b-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cc74b-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc74b-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string transformationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string transformationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;" Usage="iTransformationsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, transformationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cc74b-118">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="cc74b-119">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="cc74b-120">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-120">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="cc74b-121">変換の名前です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-121">The name of the transformation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cc74b-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cc74b-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cc74b-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cc74b-124">指定した変換の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-124">Gets details about the specified transformation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cc74b-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cc74b-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc74b-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;" Usage="iTransformationsOperations.UpdateWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            <span data-ttu-id="cc74b-128">変換オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="cc74b-128">A Transformation object.</span></span> <span data-ttu-id="cc74b-129">既存の変換 (ie 対応するプロパティをここで指定したプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="cc74b-129">The properties specified here will overwrite the corresponding properties in the existing transformation (ie. Those properties will be updated).</span></span> <span data-ttu-id="cc74b-130">ここでは null に設定されている任意のプロパティがありことを意味既存の変換では、対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="cc74b-130">Any properties that are set to null here will mean that the corresponding property in the existing transformation will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cc74b-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="cc74b-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="cc74b-133">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="cc74b-133">The name of the streaming job.</span></span>
            </param>
        <param name="transformationName">
            <span data-ttu-id="cc74b-134">変換の名前です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-134">The name of the transformation.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="cc74b-135">変換の ETag です。</span><span class="sxs-lookup"><span data-stu-id="cc74b-135">The ETag of the transformation.</span></span> <span data-ttu-id="cc74b-136">常に現在の変換を上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-136">Omit this value to always overwrite the current transformation.</span></span> <span data-ttu-id="cc74b-137">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-137">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cc74b-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cc74b-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cc74b-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cc74b-140">既存のストリーミング ジョブの下にある既存の変換を更新します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-140">Updates an existing transformation under an existing streaming job.</span></span>
            <span data-ttu-id="cc74b-141">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-141">This can be used to partially update (ie.</span></span> <span data-ttu-id="cc74b-142">1 つまたは 2 つのプロパティの更新)、残りのジョブまたは変換の定義に影響を与えずに変換します。</span><span class="sxs-lookup"><span data-stu-id="cc74b-142">update one or two properties) a transformation without affecting the rest the job or transformation definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cc74b-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cc74b-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cc74b-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cc74b-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>