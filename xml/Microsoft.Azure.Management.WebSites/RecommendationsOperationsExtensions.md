<Type Name="RecommendationsOperationsExtensions" FullName="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="86026-101">RecommendationsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="86026-101">Extension methods for RecommendationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebApp">
      <MemberSignature Language="C#" Value="public static void DisableAllForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableAllForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableAllForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-103">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-104">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-104">Name of the app.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-105">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="86026-105">Disable all recommendations for an app.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="86026-106">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="86026-106">Disable all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAllForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableAllForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableAllForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.DisableAllForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;DisableAllForWebAppAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-108">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-108">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-109">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-109">Name of the app.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-111">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="86026-111">Disable all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-112">アプリのすべての推奨設定を無効にします。</span><span class="sxs-lookup"><span data-stu-id="86026-112">Disable all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebApp">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.RecommendationRule GetRuleDetailsByWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRuleDetailsByWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, name As String, Optional updateSeen As Nullable(Of Boolean) = null) As RecommendationRule" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.RecommendationRule" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebApp (operations, resourceGroupName, siteName, name, updateSeen)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.RecommendationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-114">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-114">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-115">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-115">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="86026-116">推奨設定の名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-116">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="86026-117">指定&lt;コード&gt;true&lt;/code&gt;推奨設定オブジェクトの最後に表示されるタイムスタンプを更新します。</span><span class="sxs-lookup"><span data-stu-id="86026-117">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-118">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-118">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-119">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-119">Get a recommendation rule for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt; GetRuleDetailsByWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync (operations, resourceGroupName, siteName, name, updateSeen, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;GetRuleDetailsByWebAppAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.RecommendationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-121">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-121">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-122">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-122">Name of the app.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="86026-123">推奨設定の名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-123">Name of the recommendation.</span></span>
            </param>
        <param name="updateSeen">
            <span data-ttu-id="86026-124">指定&lt;コード&gt;true&lt;/code&gt;推奨設定オブジェクトの最後に表示されるタイムスタンプを更新します。</span><span class="sxs-lookup"><span data-stu-id="86026-124">Specify &lt;code&gt;true&lt;/code&gt; to update the last-seen timestamp of the recommendation object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-126">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-126">Get a recommendation rule for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-127">アプリのリコメンデーション ルールを取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-127">Get a recommendation rule for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; List(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecommendationsOperations, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.List (operations, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-128">The operations group for this extension method.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="86026-129">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-129">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="86026-130">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="86026-130">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-131">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-131">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-132">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="86026-132">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-133">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="86026-133">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-134">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="86026-134">List all recommendations for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListAsync (operations, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-135">The operations group for this extension method.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="86026-136">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-136">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="86026-137">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="86026-137">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-138">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-138">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-139">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="86026-139">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-141">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="86026-141">List all recommendations for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-142">サブスクリプションのすべての推奨事項を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="86026-142">List all recommendations for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListHistoryForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListHistoryForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebApp (operations, resourceGroupName, siteName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-144">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-145">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-145">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-146">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-146">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-147">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="86026-147">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-148">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-148">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-149">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-149">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListHistoryForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync (operations, resourceGroupName, siteName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListHistoryForWebAppAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-151">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-152">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-152">Name of the app.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-153">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-153">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-154">例: $filter = チャネル eq 'Api' またはチャネル eq '通知' と startTime eq '2014-01-01T00:00:00Z' と endTime eq' 2014-12-31T23:59:59Z' と timeGrain eq 期間 ' [PT1H |PT1M |P1D]</span><span class="sxs-lookup"><span data-stu-id="86026-154">Example: $filter=channels eq 'Api' or channel eq 'Notification' and startTime eq '2014-01-01T00:00:00Z' and endTime eq '2014-12-31T23:59:59Z' and timeGrain eq duration'[PT1H|PT1M|P1D]</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-156">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-156">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-157">過去の時間の範囲で指定されたオプションで、アプリに関する推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-157">Get past recommendations for an app, optionally specified by the time range.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebApp">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt; ListRecommendedRulesForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRecommendedRulesForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String, Optional featured As Nullable(Of Boolean) = null, Optional filter As String = null) As IList(Of Recommendation)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebApp (operations, resourceGroupName, siteName, featured, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-159">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-160">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-160">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="86026-161">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-161">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="86026-162">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="86026-162">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-163">フィルターに指定されたチャネルのみを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-163">Return only channels specified in the filter.</span></span> <span data-ttu-id="86026-164">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-164">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-165">例: $filter = チャネル eq 'Api' またはチャネル eq '通知'</span><span class="sxs-lookup"><span data-stu-id="86026-165">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-166">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-166">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-167">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-167">Get all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt; ListRecommendedRulesForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync (operations, resourceGroupName, siteName, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ListRecommendedRulesForWebAppAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Recommendation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-169">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-169">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-170">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-170">Name of the app.</span></span>
            </param>
        <param name="featured">
            <span data-ttu-id="86026-171">指定&lt;コード&gt;true&lt;/code&gt;を最も重要な推奨事項だけを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-171">Specify &lt;code&gt;true&lt;/code&gt; to return only the most critical recommendations.</span></span> <span data-ttu-id="86026-172">既定値は&lt;コード&gt;false&lt;/code&gt;、すべての推奨事項が返されます。</span><span class="sxs-lookup"><span data-stu-id="86026-172">The default is &lt;code&gt;false&lt;/code&gt;, which returns all recommendations.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="86026-173">フィルターに指定されたチャネルのみを返します。</span><span class="sxs-lookup"><span data-stu-id="86026-173">Return only channels specified in the filter.</span></span> <span data-ttu-id="86026-174">フィルターを指定するには、OData 構文を使用します。</span><span class="sxs-lookup"><span data-stu-id="86026-174">Filter is specified by using OData syntax.</span></span> <span data-ttu-id="86026-175">例: $filter = チャネル eq 'Api' またはチャネル eq '通知'</span><span class="sxs-lookup"><span data-stu-id="86026-175">Example: $filter=channels eq 'Api' or channel eq 'Notification'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-177">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-177">Get all recommendations for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-178">アプリのすべての推奨事項を取得します。</span><span class="sxs-lookup"><span data-stu-id="86026-178">Get all recommendations for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFilters">
      <MemberSignature Language="C#" Value="public static void ResetAllFilters (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFilters(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters(Microsoft.Azure.Management.WebSites.IRecommendationsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFilters (operations As IRecommendationsOperations)" />
      <MemberSignature Language="F#" Value="static member ResetAllFilters : Microsoft.Azure.Management.WebSites.IRecommendationsOperations -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFilters operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-179">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-180">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-180">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="86026-181">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-181">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-182">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-184">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-184">Reset all recommendation opt-out settings for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-185">サブスクリプションのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-185">Reset all recommendation opt-out settings for a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebApp">
      <MemberSignature Language="C#" Value="public static void ResetAllFiltersForWebApp (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ResetAllFiltersForWebApp(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ResetAllFiltersForWebApp (operations As IRecommendationsOperations, resourceGroupName As String, siteName As String)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebApp : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebApp (operations, resourceGroupName, siteName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-187">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-187">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-188">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-188">Name of the app.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-189">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-189">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="86026-190">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-190">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync (this Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync(class Microsoft.Azure.Management.WebSites.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync(Microsoft.Azure.Management.WebSites.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebAppAsync : Microsoft.Azure.Management.WebSites.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.RecommendationsOperationsExtensions/&lt;ResetAllFiltersForWebAppAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="86026-191">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="86026-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="86026-192">リソースが属するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="siteName">
            <span data-ttu-id="86026-193">アプリの名前です。</span><span class="sxs-lookup"><span data-stu-id="86026-193">Name of the app.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="86026-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="86026-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="86026-195">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-195">Reset all recommendation opt-out settings for an app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="86026-196">アプリのすべての推奨事項オプトアウトの設定をリセットします。</span><span class="sxs-lookup"><span data-stu-id="86026-196">Reset all recommendation opt-out settings for an app.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>