<Type Name="MobileServiceSyncTableExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceSyncTableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceSyncTableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceSyncTableExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceSyncTableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0bf72-101">拡張メソッドを提供します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /></span><span class="sxs-lookup"><span data-stu-id="0bf72-101">Provides extension methods on <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PullAsync (table As IMobileServiceSyncTable, queryId As String, query As String) As Task" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-102">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-102">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-103">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-103">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-104">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-104">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-105">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含めるとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-105">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-106">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-106">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-107">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-107">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="0bf72-108">増分同期をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0bf72-108">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-109">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-109">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-110">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-110">Thrown when <paramref name="queryId" />does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-111">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-111">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-112">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-112">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-113">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-113">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-114">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含めるとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-114">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-115">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-115">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="0bf72-116">リモート テーブルからデータをプルする方法を決定する PullOptions</span><span class="sxs-lookup"><span data-stu-id="0bf72-116">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-117">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-117">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="0bf72-118">増分同期をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0bf72-118">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-119">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-119">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-120">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-120">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-121">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-121">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-122">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-122">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-123">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-123">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-124">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含めるとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-124">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-125">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-125">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0bf72-126">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-126">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-127"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-127">The <see cref="T:System.Threading.CancellationToken" />token to observe</span></span></param>
        <summary>
            <span data-ttu-id="0bf72-128">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-128">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="0bf72-129">増分同期をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0bf72-129">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-130">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-130">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-131">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-131">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, bool pushOtherTables, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, pushOtherTables, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="table">To be added.</param>
        <param name="queryId">
            <span data-ttu-id="0bf72-132">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-132">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-133">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-133">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-134">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-134">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-135">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-135">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0bf72-136">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-136">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="0bf72-137">このテーブルがダーティの場合は、他のテーブルをプッシュします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-137">Push other tables if this table is dirty.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-138"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-138">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-139">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-139">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="0bf72-140">増分同期をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0bf72-140">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-141">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-141">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-142">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-142">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string queryId, string query, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, parameters, cancellationToken, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-143">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-143">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-144">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-144">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-145">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-145">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-146">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含めるとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-146">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-147">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-147">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0bf72-148">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-148">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-149"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-149">The <see cref="T:System.Threading.CancellationToken" />token to observe</span></span></param>
        <param name="pullOptions">
            <span data-ttu-id="0bf72-150">リモート テーブルからデータをプルする方法を決定する PullOptions</span><span class="sxs-lookup"><span data-stu-id="0bf72-150">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-151">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-151">Pulls all items that match the given query from the associated remote table.</span></span> <span data-ttu-id="0bf72-152">増分同期をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="0bf72-152">Supports incremental sync.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-153">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-153">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-154">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-154">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PullAsync(Of T, U) (table As IMobileServiceSyncTable(Of T), queryId As String, query As IMobileServiceTableQuery(Of U)) As Task" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table"><span data-ttu-id="0bf72-155">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-155">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-156">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-156">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-157">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-157">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-158">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-158">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-159">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-159">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-160">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-160">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-161">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-161">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-162">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-162">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table"><span data-ttu-id="0bf72-163">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-163">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-164">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-164">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-165">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-165">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-166">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-166">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-167">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-167">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="0bf72-168">リモート テーブルからデータをプルする方法を決定する PullOptions</span><span class="sxs-lookup"><span data-stu-id="0bf72-168">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-169">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-169">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-170">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-170">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-171">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-171">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table"><span data-ttu-id="0bf72-172">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-172">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-173">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-173">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-174">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-174">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-175">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-175">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-176">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-176">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-177"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-177">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-178">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-178">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-179">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-179">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-180">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-180">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool pushOtherTables, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, pushOtherTables, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table">To be added.</param>
        <param name="queryId">
            <span data-ttu-id="0bf72-181">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-181">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-182">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-182">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-183">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-183">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-184">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-184">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="0bf72-185">このテーブルがダーティの場合は、他のテーブルをプッシュします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-185">Push other tables if this table is dirty</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-186"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-186">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-187">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-187">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-188">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-188">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-189">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-189">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PullAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PullAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1},System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="static member PullAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PullAsync (table, queryId, query, cancellationToken, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table"><span data-ttu-id="0bf72-190">プルを実行するテーブルのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0bf72-190">The instance of table to execute pull on.</span></span></param>
        <param name="queryId">
            <span data-ttu-id="0bf72-191">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="0bf72-191">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="0bf72-192">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-192">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span> <span data-ttu-id="0bf72-193">255 文字である必要がありますまたはそれ以下の英数字、ダッシュ、およびアンダー スコアのみを含める</span><span class="sxs-lookup"><span data-stu-id="0bf72-193">Must be 255 characters or less and contain only alphanumeric characters, dash, and underscore</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="0bf72-194">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-194">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="0bf72-195"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="0bf72-195">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="0bf72-196">リモート テーブルからデータをプルする方法を決定する PullOptions</span><span class="sxs-lookup"><span data-stu-id="0bf72-196">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="0bf72-197">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-197">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0bf72-198">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-198">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="0bf72-199">場合にスローされる<paramref name="queryId" />正規表現と一致しません<value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>です。</span><span class="sxs-lookup"><span data-stu-id="0bf72-199">Thrown when <paramref name="queryId" /> does not match the regular expression <value>[a-zA-Z][a-zA-Z0-9_-]{1,255}</value>.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync table" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-200">実行するテーブルのインスタンスをパージにします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-200">The instance of table to execute purge on.</span></span></param>
        <summary>
            <span data-ttu-id="0bf72-201">ローカル テーブルのすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-201">Deletes all the items in local table</span></span>
            </summary>
        <returns><span data-ttu-id="0bf72-202">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-202">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * bool -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, force)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-203">実行するテーブルのインスタンスをパージにします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-203">The instance of table to execute purge on.</span></span></param>
        <param name="force"><span data-ttu-id="0bf72-204">保留中の操作を破棄することによって、消去を強制します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-204">Force the purge by discarding the pending operations.</span></span></param>
        <summary>
            <span data-ttu-id="0bf72-205">ローカル テーブルのすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-205">Deletes all the items in local table</span></span>
            </summary>
        <returns><span data-ttu-id="0bf72-206">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-206">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable table, string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync (table As IMobileServiceSyncTable, query As String) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable * string -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" RefType="this" />
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="table"><span data-ttu-id="0bf72-207">実行するテーブルのインスタンスをパージにします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-207">The instance of table to execute purge on.</span></span></param>
        <param name="query"><span data-ttu-id="0bf72-208">削除する項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-208">An OData query that determines which items to delete.</span></span></param>
        <summary>
            <span data-ttu-id="0bf72-209">クエリに一致するローカル テーブル内のすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-209">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="0bf72-210">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-210">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeAsync&lt;T,U&gt; (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; table, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeAsync&lt;T, U&gt;(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; table, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync``2(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable{``0},Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``1})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PurgeAsync(Of T, U) (table As IMobileServiceSyncTable(Of T), query As IMobileServiceTableQuery(Of U)) As Task" />
      <MemberSignature Language="F#" Value="static member PurgeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt; * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncTableExtensions.PurgeAsync (table, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="table" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;" RefType="this" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <typeparam name="U">To be added.</typeparam>
        <param name="table"><span data-ttu-id="0bf72-211">実行するテーブルのインスタンスをパージにします。</span><span class="sxs-lookup"><span data-stu-id="0bf72-211">The instance of table to execute purge on.</span></span></param>
        <param name="query"><span data-ttu-id="0bf72-212">削除する項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="0bf72-212">An OData query that determines which items to delete.</span></span></param>
        <summary>
            <span data-ttu-id="0bf72-213">クエリに一致するローカル テーブル内のすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-213">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="0bf72-214">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="0bf72-214">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>