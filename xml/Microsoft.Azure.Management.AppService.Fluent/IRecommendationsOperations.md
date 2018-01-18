<Type Name="IRecommendationsOperations" FullName="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations">
  <TypeSignature Language="C#" Value="public interface IRecommendationsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRecommendationsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRecommendationsOperations" />
  <TypeSignature Language="F#" Value="type IRecommendationsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4653a-101">RecommendationsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="4653a-101">RecommendationsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableAllForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DisableAllForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.DisableAllForWebAppWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAllForWebAppWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.DisableAllForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4653a-102">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-102">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="4653a-103">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-103">Name of the app.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-104">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-106">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="4653a-106">Disable all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-107">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="4653a-107">Disable all recommendations for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-109">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-109">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;&gt; GetRuleDetailsByWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;&gt; GetRuleDetailsByWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.GetRuleDetailsByWebAppWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRuleDetailsByWebAppWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;&gt;" Usage="iRecommendationsOperations.GetRuleDetailsByWebAppWithHttpMessagesAsync (resourceGroupName, siteName, name, updateSeen, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4653a-110">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="4653a-111">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-111">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="4653a-112">推奨設定の名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-112">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="4653a-113">指定&lt;コード&gt;true&lt;/code&gt;推奨設定オブジェクトの最後に表示されるタイムスタンプを更新します。</span><span class="sxs-lookup"><span data-stu-id="4653a-113">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-116">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-116">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-117">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-117">Get a recommendation rule for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4653a-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListHistoryForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListHistoryForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.ListHistoryForWebAppWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHistoryForWebAppWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListHistoryForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4653a-121">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-121">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="4653a-122">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-122">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4653a-123">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="4653a-123">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="4653a-124">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="4653a-124">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-127">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-127">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-128">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-128">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4653a-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListRecommendedRulesForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListRecommendedRulesForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.ListRecommendedRulesForWebAppWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRecommendedRulesForWebAppWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListRecommendedRulesForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, featured, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4653a-132">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-132">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="4653a-133">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-133">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="4653a-134">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="4653a-134">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="4653a-135">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="4653a-135">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4653a-136">フィルターに指定されたチャネルのみを返します。</span><span class="sxs-lookup"><span data-stu-id="4653a-136">Return only channels specified in the filter.</span></span> <span data-ttu-id="4653a-137">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="4653a-137">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="4653a-138">例: $filter = チャネル eq 'Api' またはチャネル eq '通知'</span><span class="sxs-lookup"><span data-stu-id="4653a-138">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-139">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-139">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-141">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-141">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-142">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="4653a-142">Get all recommendations for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4653a-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListWithHttpMessagesAsync (Nullable&lt;bool&gt; featured = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt; ListWithHttpMessagesAsync(valuetype System.Nullable`1&lt;bool&gt; featured, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.ListWithHttpMessagesAsync(System.Nullable{System.Boolean},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Nullable&lt;bool&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;" Usage="iRecommendationsOperations.ListWithHttpMessagesAsync (featured, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="featured">
            <span data-ttu-id="4653a-146">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="4653a-146">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="4653a-147">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="4653a-147">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="4653a-148">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="4653a-148">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="4653a-149">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="4653a-149">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-152">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4653a-152">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-153">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4653a-153">List all recommendations for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="4653a-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersForWebAppWithHttpMessagesAsync (string resourceGroupName, string siteName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersForWebAppWithHttpMessagesAsync(string resourceGroupName, string siteName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.ResetAllFiltersForWebAppWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAllFiltersForWebAppWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.ResetAllFiltersForWebAppWithHttpMessagesAsync (resourceGroupName, siteName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4653a-157">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-157">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="4653a-158">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="4653a-158">Name of the app.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="4653a-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-161">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="4653a-161">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-162">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="4653a-162">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-164">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-164">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResetAllFiltersWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations.ResetAllFiltersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAllFiltersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRecommendationsOperations.ResetAllFiltersWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="4653a-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="4653a-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4653a-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4653a-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4653a-167">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="4653a-167">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="4653a-168">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="4653a-168">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="4653a-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4653a-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="4653a-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>