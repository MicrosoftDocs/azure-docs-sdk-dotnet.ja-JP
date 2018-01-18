<Type Name="IEndpointsOperations" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations">
  <TypeSignature Language="C#" Value="public interface IEndpointsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEndpointsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEndpointsOperations" />
  <TypeSignature Language="F#" Value="type IEndpointsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eaa2a-101">EndpointsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-101">EndpointsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eaa2a-102">作成または更新する Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-102">The name of the resource group containing the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="eaa2a-103">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-103">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="eaa2a-104">作成または更新する Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-104">The type of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="eaa2a-105">作成または更新する Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-105">The name of the Traffic Manager endpoint to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eaa2a-106">CreateOrUpdate 操作に指定された Traffic Manager エンドポイント パラメーター。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-106">The Traffic Manager endpoint parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="eaa2a-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eaa2a-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eaa2a-109">作成または Traffic Manager エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-109">Create or update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="eaa2a-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="eaa2a-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eaa2a-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;&gt;" Usage="iEndpointsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="endpointType">To be added.</param>
        <param name="endpointName">To be added.</param>
        <param name="customHeaders">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eaa2a-113">Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-113">The name of the resource group containing the Traffic Manager endpoint.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="eaa2a-114">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-114">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="eaa2a-115">Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-115">The type of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="eaa2a-116">Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-116">The name of the Traffic Manager endpoint.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="eaa2a-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eaa2a-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eaa2a-119">Traffic Manager エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-119">Gets a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="eaa2a-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="eaa2a-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eaa2a-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, string endpointType, string endpointName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, string endpointType, string endpointName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.IEndpointsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;" Usage="iEndpointsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, profileName, endpointType, endpointName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointType" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eaa2a-123">更新する Traffic Manager エンドポイントを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-123">The name of the resource group containing the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="eaa2a-124">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-124">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="endpointType">
            <span data-ttu-id="eaa2a-125">更新する Traffic Manager エンドポイントの型。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-125">The type of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="endpointName">
            <span data-ttu-id="eaa2a-126">更新する Traffic Manager エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-126">The name of the Traffic Manager endpoint to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eaa2a-127">更新操作に指定された Traffic Manager エンドポイントのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-127">The Traffic Manager endpoint parameters supplied to the Update operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="eaa2a-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eaa2a-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eaa2a-130">Traffic Manager エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-130">Update a Traffic Manager endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="eaa2a-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="eaa2a-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="eaa2a-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="eaa2a-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>