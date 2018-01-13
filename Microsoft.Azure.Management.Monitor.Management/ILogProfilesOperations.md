<Type Name="ILogProfilesOperations" FullName="Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations">
  <TypeSignature Language="C#" Value="public interface ILogProfilesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILogProfilesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILogProfilesOperations" />
  <TypeSignature Language="F#" Value="type ILogProfilesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="46789-101">LogProfilesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="46789-101">LogProfilesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;" Usage="iLogProfilesOperations.CreateOrUpdateWithHttpMessagesAsync (logProfileName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="logProfileName">
            <span data-ttu-id="46789-102">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="46789-102">The name of the log profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="46789-103">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="46789-103">Parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="46789-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="46789-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="46789-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46789-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46789-106">作成または監視の REST API を Azure でログのプロファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="46789-106">Create or update a log profile in Azure Monitoring REST API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="46789-107">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-107">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="46789-108">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-108">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46789-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string logProfileName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string logProfileName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations.DeleteWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iLogProfilesOperations.DeleteWithHttpMessagesAsync (logProfileName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="logProfileName">
            <span data-ttu-id="46789-110">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="46789-110">The name of the log profile.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="46789-111">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="46789-111">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="46789-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46789-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46789-113">ログのプロファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="46789-113">Deletes the log profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="46789-114">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-114">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46789-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; GetWithHttpMessagesAsync (string logProfileName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; GetWithHttpMessagesAsync(string logProfileName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;" Usage="iLogProfilesOperations.GetWithHttpMessagesAsync (logProfileName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="logProfileName">
            <span data-ttu-id="46789-116">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="46789-116">The name of the log profile.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="46789-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="46789-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="46789-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46789-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46789-119">ログのプロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="46789-119">Gets the log profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="46789-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="46789-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46789-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;&gt;" Usage="iLogProfilesOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="46789-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="46789-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="46789-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46789-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46789-125">ログのプロファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="46789-125">List the log profiles.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="46789-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="46789-127">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-127">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46789-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; UpdateWithHttpMessagesAsync (string logProfileName, Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt; UpdateWithHttpMessagesAsync(string logProfileName, class Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch logProfilesResource, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.ILogProfilesOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;" Usage="iLogProfilesOperations.UpdateWithHttpMessagesAsync (logProfileName, logProfilesResource, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logProfileName" Type="System.String" />
        <Parameter Name="logProfilesResource" Type="Microsoft.Azure.Management.Monitor.Management.Models.LogProfileResourcePatch" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="logProfileName">
            <span data-ttu-id="46789-129">ログのプロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="46789-129">The name of the log profile.</span></span>
            </param>
        <param name="logProfilesResource">
            <span data-ttu-id="46789-130">パラメーターは、操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="46789-130">Parameters supplied to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="46789-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="46789-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="46789-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="46789-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="46789-133">既存の LogProfilesResource を更新します。</span><span class="sxs-lookup"><span data-stu-id="46789-133">Updates an existing LogProfilesResource.</span></span> <span data-ttu-id="46789-134">更新するには、その他のフィールドは、CreateOrUpdate メソッドを使用します。</span><span class="sxs-lookup"><span data-stu-id="46789-134">To update other fields use the CreateOrUpdate method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.Monitor.Management.Models.ErrorResponseException">
            <span data-ttu-id="46789-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="46789-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="46789-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="46789-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>