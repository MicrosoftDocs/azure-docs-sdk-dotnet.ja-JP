<Type Name="FabricClient+QueryClient" FullName="System.Fabric.FabricClient+QueryClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.QueryClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/QueryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.QueryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.QueryClient" />
  <TypeSignature Language="F#" Value="type FabricClient.QueryClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="7a036-101">クエリを実行するために使用するファブリック クライアントを表します。</span><span class="sxs-lookup"><span data-stu-id="7a036-101">Represents the fabric client that can be used to issue queries.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync () As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="7a036-102">システムで作成されたすべてのアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-102">Gets the details for all applications created in the system.</span></span> <span data-ttu-id="7a036-103">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-103">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-104">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-104">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-105">指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-105">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
          <para><span data-ttu-id="7a036-106">返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-106">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-107">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-107">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-108">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-108">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-109">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-109">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-110">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-110">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync applicationNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-111">詳細を取得するアプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-111">The name of the application to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-112">すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-112">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="7a036-113">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-113">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-114">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-114">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-115">返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-115">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="7a036-116">指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-116">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-117">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-117">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-118">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-118">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-119">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-119">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-120">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-120">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri, continuationToken As String) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-121">詳細を取得するアプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-121">The name of the application to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-122">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-122">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-123">すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-123">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="7a036-124">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-124">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-125">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-125">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-126">返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-126">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="7a036-127">指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-127">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-128">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-128">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-129">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-129">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-130">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-130">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-131">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-131">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-132">詳細を取得するアプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-132">The name of the application to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-133">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-133">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-134">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-134">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-135">すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-135">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="7a036-136">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-136">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-137">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-137">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-138">返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-138">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="7a036-139">指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-139">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-140">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-140">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-141">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-141">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-142">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-142">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-143">詳細を取得するアプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-143">The name of the application to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-144">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-144">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-145">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-145">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-146">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-146">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-147">すべてのアプリケーションまたはシステムで作成された特定のアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-147">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="7a036-148">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-148">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-149">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-149">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-150">返されたタスクには、としてアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-150">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="7a036-151">指定されたアプリケーション名が一致するアプリケーションを持たない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-151">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-152">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-152">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-153">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-153">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-154">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-154">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationLoadInformationAsync (applicationName As String) As Task(Of ApplicationLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-155">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="7a036-155">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-156">指定したアプリケーション インスタンスの読み込み情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-156">Retrieves the load information of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-157">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-157">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-158">返されたタスクには、アプリケーションの情報が含まれています。<see cref="T:System.Fabric.Query.ApplicationLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-158">The returned task contains the information of an application as <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-159">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-159">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="7a036-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="7a036-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-161">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-161">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-162">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-162">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-163">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-163">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-164">アプリケーション インスタンス名の URI。</span><span class="sxs-lookup"><span data-stu-id="7a036-164">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-165">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-165">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-166">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-166">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-167">指定したアプリケーション インスタンスの読み込み情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-167">Retrieves the load information of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-168">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-168">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-169">返されたタスクには、アプリケーションの情報が含まれています。<see cref="T:System.Fabric.Query.ApplicationLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-169">The returned task contains the information of an application as <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-170">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-170">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="7a036-171"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: アプリケーションは存在しません。</span><span class="sxs-lookup"><span data-stu-id="7a036-171"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-172">要求がタイムアウトしました。</span><span class="sxs-lookup"><span data-stu-id="7a036-172">The request timed out.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-173">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-173">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;" Usage="queryClient.GetApplicationNameAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-174">アプリケーションの名前を取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-174">The name of the service to get the application name for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-175">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-175">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-176">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-176">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-177">指定したサービス アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-177">Gets the application name for the specified service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-178">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-178">A task that represents the asynchronous query operation.</span></span> </para>
          <para><span data-ttu-id="7a036-179">返されたタスクには、アプリケーション名が含まれています。<see cref="T:System.Fabric.Query.ApplicationNameResult" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-179">The returned task contains the application name as <see cref="T:System.Fabric.Query.ApplicationNameResult" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-180">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-180">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-181">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-181">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-182">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-182">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync applicationQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><span data-ttu-id="7a036-183"><see cref="T:System.Fabric.Description.ApplicationQueryDescription" />を決定するアプリケーションのクエリを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a036-183">The <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> that determines which applications should be queried.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-184">作成する (存在する場合)、クエリの説明で指定されたフィルターに一致するアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-184">Gets the details of applications created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="7a036-185">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-185">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-186">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-186">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="7a036-187">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationList" />内のフィルターを適用するアプリケーションの一覧を表す、<see cref="T:System.Fabric.Description.ApplicationQueryDescription" />ページに合わせてとします。</span><span class="sxs-lookup"><span data-stu-id="7a036-187">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationList" /> that represents the list of applications that respect the filters in the <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="7a036-188">指定されたクエリの説明に一致するアプリケーションがあるない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-188">If the provided query description has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-189">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-189">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-190">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-190">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-191">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-191">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync (applicationQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><span data-ttu-id="7a036-192"><see cref="T:System.Fabric.Description.ApplicationQueryDescription" />を決定するアプリケーションのクエリを実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a036-192">The <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> that determines which applications should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-193">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-193">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-194">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-194">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-195">作成する (存在する場合)、クエリの説明で指定されたフィルターに一致するアプリケーションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-195">Gets the details of applications created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="7a036-196">ページで、アプリケーションが収まらない場合は、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-196">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-197">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-197">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="7a036-198">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationList" />内のフィルターを適用するアプリケーションの一覧を表す、<see cref="T:System.Fabric.Description.ApplicationQueryDescription" />ページに合わせてとします。</span><span class="sxs-lookup"><span data-stu-id="7a036-198">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationList" /> that represents the list of applications that respect the filters in the <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="7a036-199">指定されたクエリの説明に一致するアプリケーションがあるない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-199">If the provided query description has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-200">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-200">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-201">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-201">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-202">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-202">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync () As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7a036-203">すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステムでプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-203">Gets the details for all the application types provisioned or being provisioned in the system.</span></span>
            <span data-ttu-id="7a036-204">多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-204">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="7a036-205">このメソッドは、今後廃止される予定です。</span><span class="sxs-lookup"><span data-stu-id="7a036-205">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-206">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-206">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-207">返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-207">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-208">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-208">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-209">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-209">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-210">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-210">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync (applicationTypeNameFilter As String) As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync applicationTypeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para><span data-ttu-id="7a036-211">サービスの種類を取得するアプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="7a036-211">The type name of the application to get service types for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-212">すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステム、または、指定したアプリケーションの種類にプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-212">Gets the details for all the application types provisioned or being provisioned in the system or for the specified application type.</span></span>
            <span data-ttu-id="7a036-213">多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-213">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="7a036-214">このメソッドは、今後廃止される予定です。</span><span class="sxs-lookup"><span data-stu-id="7a036-214">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-215">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-215">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-216">返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-216">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-217">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-217">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-218">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-218">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-219">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-219">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-220">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-220">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync (applicationTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para><span data-ttu-id="7a036-221">サービスの種類を取得するアプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="7a036-221">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-222">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-222">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-223">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-223">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-224">すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステム、または、指定したアプリケーションの種類にプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-224">Gets the details for all the application types provisioned or being provisioned in the system or for the specified application type.</span></span>
            <span data-ttu-id="7a036-225">多くの機能を使用してください<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-225">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="7a036-226">このメソッドは、今後廃止される予定です。</span><span class="sxs-lookup"><span data-stu-id="7a036-226">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-227">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-227">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-228">返されたタスクには、としてアプリケーションの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ApplicationTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-228">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-229">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-229">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-230">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-230">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-231">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-231">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync () As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
                    <span data-ttu-id="7a036-232">すべてのアプリケーションの種類の詳細を取得プロビジョニングまたはシステムでプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-232">Gets the details for all the application types provisioned or being provisioned in the system.</span></span> 
                </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="7a036-233">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-233">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="7a036-234">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-234">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="7a036-235">アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-235">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-236">これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-236">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="7a036-237">たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-237">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="7a036-238">残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-238">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="7a036-239">後続のページが存在しない場合は、null の継続トークンが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-239">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="7a036-240">特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。</span><span class="sxs-lookup"><span data-stu-id="7a036-240">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-241">ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-241">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-242">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-242">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-243">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-243">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-244">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-244">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync (queryDescription As PagedApplicationTypeQueryDescription) As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    <span data-ttu-id="7a036-245">A<see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />すると、アプリケーションが返される型を記述するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7a036-245">A <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> object describing which application types to return.</span></span>
                    </para>
        </param>
        <summary>
          <para>
                    <span data-ttu-id="7a036-246">アプリケーションの種類の詳細のプロビジョニングを取得または queryDescription 引数によって提供されるフィルターに一致するシステムでプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-246">Gets the details for application types provisioned or being provisioned in the system which match filters provided by the queryDescription argument.</span></span>
                    </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="7a036-247">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-247">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="7a036-248">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-248">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="7a036-249">アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-249">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-250">これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-250">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="7a036-251">たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-251">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="7a036-252">残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-252">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="7a036-253">後続のページが存在しない場合は、null の継続トークンが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-253">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="7a036-254">特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。</span><span class="sxs-lookup"><span data-stu-id="7a036-254">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-255">ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-255">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-256">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-256">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-257">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-257">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-258">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-258">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    <span data-ttu-id="7a036-259">A<see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />すると、アプリケーションが返される型を記述するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="7a036-259">A <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> object describing which application types to return.</span></span>
                    </para>
        </param>
        <param name="timeout">
          <para>
                    <span data-ttu-id="7a036-260">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-260">Specifies the duration this operation has to complete before timing out.</span></span>
                </para>
        </param>
        <param name="cancellationToken">
          <para>
                    <span data-ttu-id="7a036-261">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-261">Propagates notification that operations should be canceled.</span></span>
                </para>
        </param>
        <summary>
          <para>
                    <span data-ttu-id="7a036-262">アプリケーションの種類の詳細のプロビジョニングを取得または queryDescription 引数によって提供されるフィルターに一致するシステムでプロビジョニングされています。</span><span class="sxs-lookup"><span data-stu-id="7a036-262">Gets the details for application types provisioned or being provisioned in the system which match filters provided by the queryDescription argument.</span></span>
                    </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="7a036-263">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-263">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="7a036-264">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ApplicationTypePagedList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-264">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="7a036-265">アプリケーションの種類が見つからない場合、使用できるフィルターに一致する、このクエリは、エラーではなくアプリケーション型ではなくを返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-265">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-266">これをすべてのアプリケーションの種類収まらない場合、ページ内の意味、ページングされたクエリは、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-266">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="7a036-267">たとえば、10000 アプリケーションの種類がありますが、ページでは、最初の 3000 アプリケーションの種類のみに適した、3000 が返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-267">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="7a036-268">残りの結果にアクセスするには、返された継続トークンを次のクエリで使用して、後続のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-268">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="7a036-269">後続のページが存在しない場合は、null の継続トークンが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-269">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="7a036-270">特定のアプリケーションの種類の各バージョンでは、結果内の 1 つのエントリです。</span><span class="sxs-lookup"><span data-stu-id="7a036-270">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="7a036-271">ここでのアプリケーションの種類に関する詳細を参照してください:<see cref="T:System.Fabric.Query.ApplicationType" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-271">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-272">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-272">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-273">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-273">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-274">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-274">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterLoadInformationAsync () As Task(Of ClusterLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7a036-275">クラスターの読み込み情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-275">Gets the cluster load information.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-276">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-276">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-277">以下を参照してください。<see cref="T:System.Fabric.Query.ClusterLoadInformation" /></span><span class="sxs-lookup"><span data-stu-id="7a036-277">See <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
          <para><span data-ttu-id="7a036-278">返されたタスクには、としてクラスターの負荷の情報が含まれています。<see cref="T:System.Fabric.Query.ClusterLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-278">The returned task contains the load information of the cluster as <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-279">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-279">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-280">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-280">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-281">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-281">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-282">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-282">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="7a036-283">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-283">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-284">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-284">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-285">クラスターの読み込み情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-285">Gets the cluster load information.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-286">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-286">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-287">返されたタスクには、としてクラスターの負荷の情報が含まれています。<see cref="T:System.Fabric.Query.ClusterLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-287">The returned task contains the load information of the cluster as <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-288">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-288">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-289">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-289">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-290">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-290">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-291">対応アプリケーションを取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-291">The name of the node to get applications for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-292">展開済みアプリケーションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-292">Gets the deployed application list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-293">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-293">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-294">返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-294">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-295">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-295">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-296">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-296">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-297">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-297">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-298">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-298">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String, applicationNameFilter As Uri) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-299">対応アプリケーションを取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-299">The name of the node to get applications for.</span></span></para>
        </param>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-300">このアプリケーションの名前と一致するアプリケーションのみを含める結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-300">Filter results to include only applications matching this application name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-301">指定したアプリケーション名のノードに展開されたアプリケーションを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-301">Gets the deployed applications on a node with the specified application name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-302">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-302">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-303">返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-303">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-304">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-304">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-305">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-305">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-306">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-306">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-307">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-307">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-308">対応アプリケーションを取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-308">The name of the node to get applications for.</span></span></para>
        </param>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="7a036-309">このアプリケーションの名前と一致するアプリケーションのみを含める結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-309">Filter results to include only applications matching this application name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-310">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-310">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-311">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-311">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-312">指定したアプリケーション名のノードに展開されたアプリケーションを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-312">Gets the deployed applications on a node with the specified application name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-313">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-313">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-314">返されたタスクには、として配置されているアプリケーションの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedApplicationList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-314">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-315">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-315">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-316">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-316">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-317">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-317">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-318">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-318">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-319">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-319">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-320">配置されたコード パッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-320">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-321">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-321">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-322">返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-322">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-323">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-323">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-324">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-324">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-325">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-325">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-326">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-326">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, codePackageNameFilter As String) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-327">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-327">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-328">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-328">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-329">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-329">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="codePackageNameFilter">
          <para><span data-ttu-id="7a036-330">ものだけにこのコード パッケージの名前と一致する結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-330">Filter results to include only those matching this code package name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-331">配置されたコード パッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-331">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-332">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-332">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-333">返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-333">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-334">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-334">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-335">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-335">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-336">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-336">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-337">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-337">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-338">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-338">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-339">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-339">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-340">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-340">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="codePackageNameFilter">
          <para><span data-ttu-id="7a036-341">ものだけにこのコード パッケージの名前と一致する結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-341">Filter results to include only those matching this code package name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-342">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-342">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-343">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-343">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-344">配置されたコード パッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-344">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-345">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-345">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-346">返されたタスクには、として配置されたコード パッケージの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedCodePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-346">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-347">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-347">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-348">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-348">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-349">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-349">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaDetailAsync (nodeName As String, partitionId As Guid, replicaId As Long) As Task(Of DeployedServiceReplicaDetail)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-350">元の結果が必要なノード名です。</span><span class="sxs-lookup"><span data-stu-id="7a036-350">The node name from which the results are desired.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-351">結果が必要となるパーティションの id です。</span><span class="sxs-lookup"><span data-stu-id="7a036-351">The partition id for which the results are desired.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="7a036-352">レプリカまたは結果が必要となるインスタンスの識別子。</span><span class="sxs-lookup"><span data-stu-id="7a036-352">The identifier for the replica or the instance for which the results are desired.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-353">指定したノードで実行されているレプリカの詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-353">Returns details of a replica running on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-354">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-354">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-355">返されるタスク、レプリカとして情報を含む<see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-355">The returned task contains the replica information as <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-356">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-356">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-357">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-357">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-358">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-358">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-359">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-359">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-360">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-360">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-361">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-361">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-362">元の結果が必要なノード名です。</span><span class="sxs-lookup"><span data-stu-id="7a036-362">The node name from which the results are desired.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-363">結果が必要となるパーティションの id です。</span><span class="sxs-lookup"><span data-stu-id="7a036-363">The partition id for which the results are desired.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="7a036-364">レプリカまたは結果が必要となるインスタンスの識別子。</span><span class="sxs-lookup"><span data-stu-id="7a036-364">The identifier for the replica or the instance for which the results are desired.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-365">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-365">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-366">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-366">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-367">指定したノードで実行されているレプリカの詳細を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-367">Returns details of a replica running on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-368">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-368">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-369">返されるタスク、レプリカとして情報を含む<see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-369">The returned task contains the replica information as <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-370">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-370">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-371">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-371">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-372">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-372">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-373">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-373">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-374">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-374">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-375">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-375">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-376">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-376">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-377">ノードからのレプリカのビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-377">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-378">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-378">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-379">返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-379">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-380">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-380">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-381">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-381">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-382">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-382">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-383">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-383">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-384">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-384">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-385">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-385">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-386">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-386">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-387">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-387">The name of the application.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-388">このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-388">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-389">ノードからのレプリカのビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-389">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-390">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-390">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-391">返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-391">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-392">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-392">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-393">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-393">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-394">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-394">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-395">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-395">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-396">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-396">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-397">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-397">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-398">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-398">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-399">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-399">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-400">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-400">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-401">このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-401">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-402">ノードからのレプリカのビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-402">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-403">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-403">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-404">返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-404">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-405">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-405">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-406">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-406">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-407">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-407">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-408">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-408">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-409">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-409">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-410">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-410">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-411">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-411">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-412">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-412">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-413">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-413">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-414">このパーティションの ID に一致するレプリカだけを結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-414">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-415">返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-415">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-416">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7a036-416">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="7a036-417">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="7a036-417">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="7a036-418">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7a036-418">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-419">ノードからのレプリカのビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-419">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-420">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-420">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-421">返されるタスクには、展開済みサービスのレプリカとしての一覧が含まれています<see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-421">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-422">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-422">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-423">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-423">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-424">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-424">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-425">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-425">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-426">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-426">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-427">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-427">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-428">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-428">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-429">指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-429">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-430">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-430">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-431">返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-431">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-432">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-432">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-433">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-433">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-434">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-434">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-435">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-435">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-436">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-436">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-437">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-437">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-438">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-438">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-439">指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-439">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-440">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-440">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-441">返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-441">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-442">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-442">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-443">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-443">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-444">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-444">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-445">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-445">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-446">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-446">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-447">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-447">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-448">このサービスに一致するもののマニフェスト名だけを含めるようにする結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-448">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-449">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-449">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-450">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-450">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-451">指定したノードとアプリケーションの展開済みサービス パッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-451">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-452">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-452">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-453">返されたタスクには、パッケージの展開済みサービスの一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServicePackageList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-453">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-454">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-454">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-455">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-455">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-456">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-456">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-457">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-457">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-458">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-458">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-459">指定したノードとアプリケーションの展開済みサービスの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-459">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-460">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-460">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-461">返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-461">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-462">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-462">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-463">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-463">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-464">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-464">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-465">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-465">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, serviceTypeNameFilter As String) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-466">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-466">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-467">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-467">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-468">このサービス マニフェスト名と一致するサービス型のみを含めるための結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-468">Filter results to include only service types matching this service manifest name.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="7a036-469">この名前に一致するサービス型のみを含めるための結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-469">Filter results to include only service types matching this name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-470">指定したノードとアプリケーションの展開済みサービスの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-470">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-471">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-471">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-472">返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-472">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-473">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-473">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-474">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-474">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-475">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-475">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-476">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-476">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-477">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-477">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-478">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-478">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="7a036-479">このサービス マニフェスト名と一致するサービス型のみを含めるための結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-479">Filter results to include only service types matching this service manifest name.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="7a036-480">この名前に一致するサービス型のみを含めるための結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-480">Filter results to include only service types matching this name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-481">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-481">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-482">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-482">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-483">指定したノードとアプリケーションの展開済みサービスの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-483">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-484">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-484">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-485">返されたタスクには、として展開されているサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.DeployedServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-485">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-486">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-486">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-487">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-487">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-488">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-488">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync () As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="7a036-489">クラスター内のすべてのノードの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-489">Gets the details for all nodes in the cluster.</span></span> <span data-ttu-id="7a036-490">ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-490">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-491">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-491">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-492">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-492">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-493">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-493">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-494">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-494">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-495">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-495">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync nodeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="7a036-496">詳細を取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-496">The name of the node to get details for.</span></span> <span data-ttu-id="7a036-497">ノード名は区別されません。</span><span class="sxs-lookup"><span data-stu-id="7a036-497">The node name is case-insensitive.</span></span> <span data-ttu-id="7a036-498">指定したノード名が null の場合は、クラスター内のすべてのノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-498">Gets all nodes in the cluster if the given node name is null.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-499">クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-499">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="7a036-500">ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-500">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-501">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-501">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-502">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-502">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-503">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-503">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-504">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-504">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-505">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-505">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-506">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-506">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String, continuationToken As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="7a036-507">詳細を取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-507">The name of the node to get details for.</span></span> <span data-ttu-id="7a036-508">ノード名は区別されません。</span><span class="sxs-lookup"><span data-stu-id="7a036-508">The node name is case-insensitive.</span></span> <span data-ttu-id="7a036-509">指定したノード名が null の場合は、すべてのノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-509">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-510">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-510">The continuation token obtained from a previous query.</span></span></para>
          <returns>
            <para><span data-ttu-id="7a036-511">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-511">A task that represents the asynchronous query operation.</span></span></para>
            <para><span data-ttu-id="7a036-512">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-512">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
          </returns>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-513">クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-513">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="7a036-514">ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-514">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-515">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-515">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-516">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-516">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-517">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-517">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-518">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-518">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="7a036-519">詳細を取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-519">The name of the node to get details for.</span></span> <span data-ttu-id="7a036-520">ノード名は区別されません。</span><span class="sxs-lookup"><span data-stu-id="7a036-520">The node name is case-insensitive.</span></span> <span data-ttu-id="7a036-521">指定したノード名が null の場合は、すべてのノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-521">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-522">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-522">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-523">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-523">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-524">クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-524">Gets the details for all nodes in the cluster or for the specified node.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-525">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-525">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-526">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-526">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-527">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-527">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-528">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-528">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-529">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-529">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="7a036-530">詳細を取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-530">The name of the node to get details for.</span></span> <span data-ttu-id="7a036-531">ノード名は区別されません。</span><span class="sxs-lookup"><span data-stu-id="7a036-531">The node name is case-insensitive.</span></span> <span data-ttu-id="7a036-532">指定したノード名が null の場合は、すべてのノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-532">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-533">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-533">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-534">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-534">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-535">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-535">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-536">クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-536">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="7a036-537">ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-537">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-538">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-538">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-539">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-539">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-540">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-540">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-541">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-541">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-542">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-542">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.Fabric.Query.NodeStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * System.Fabric.Query.NodeStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, nodeStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="nodeStatusFilter" Type="System.Fabric.Query.NodeStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="7a036-543">詳細を取得するノードの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-543">The name of the node to get details for.</span></span> <span data-ttu-id="7a036-544">ノード名は区別されません。</span><span class="sxs-lookup"><span data-stu-id="7a036-544">The node name is case-insensitive.</span></span> <span data-ttu-id="7a036-545">指定したノード名が null の場合は、すべてのノードを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-545">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="nodeStatusFilter">
          <para><span data-ttu-id="7a036-546">詳細を取得するノードのノードの性状態です。</span><span class="sxs-lookup"><span data-stu-id="7a036-546">The node status(es) of the nodes to get details for.</span></span></para>
        </param>
        <param name="continuationToken"><span data-ttu-id="7a036-547">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-547">The continuation token obtained from a previous query.</span></span></param>
        <param name="timeout"><span data-ttu-id="7a036-548">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-548">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7a036-549">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-549">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="7a036-550">クラスター内のすべてのノードのまたは指定したノードに対しては、詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-550">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="7a036-551">ページ内のノードが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-551">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="7a036-552">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-552">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-553">返されたタスクには、としてノードの一覧が含まれています。<see cref="T:System.Fabric.Query.NodeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-553">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-554">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-554">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-555">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-555">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-556">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-556">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeLoadInformationAsync (nodeName As String) As Task(Of NodeLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-557">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-557">The name of the node.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-558">メトリックを取得し、ノードに関する情報を読み込みます。</span><span class="sxs-lookup"><span data-stu-id="7a036-558">Get metrics and load information on the node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-559">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-559">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-560">返されたタスクには、ノードの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.NodeLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-560">The returned task contains the load information of the node as <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-561">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-561">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-562">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-562">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-563">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-563">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-564">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-564">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="7a036-565">ノード名。</span><span class="sxs-lookup"><span data-stu-id="7a036-565">The name of the node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-566">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-566">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-567">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-567">Propagates notification that operations should be canceled</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-568">メトリックを取得し、ノードに関する情報を読み込みます。</span><span class="sxs-lookup"><span data-stu-id="7a036-568">Get metrics and load information on the node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-569">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-569">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-570">返されたタスクには、ノードの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.NodeLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-570">The returned task contains the load information of the node as <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-571">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-571">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-572">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-572">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-573">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-573">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionAsync (partitionId As Guid) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-574">詳細を取得するパーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-574">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-575">指定したパーティションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-575">Gets the details for the specified partition.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-576">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-576">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-577">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-577">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-578">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-578">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-579">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-579">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-580">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-580">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-581">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-581">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-582">詳細を取得するパーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-582">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-583">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-583">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-584">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-584">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-585">指定したパーティションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-585">Gets the details for the specified partition.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-586">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-586">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-587">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-587">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-588">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-588">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-589">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-589">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-590">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-590">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-591">用のパーティションを取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-591">The name of the service to get partitions for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-592">サービスのすべてのパーティションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-592">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="7a036-593">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-593">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-594">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-594">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-595">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-595">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-596">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-596">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-597">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-597">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-598">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-598">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-599">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-599">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-600">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-600">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-601">詳細を取得するパーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-601">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-602">サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-602">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="7a036-603">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-603">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-604">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-604">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-605">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-605">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-606">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-606">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-607">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-607">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-608">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-608">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-609">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-609">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, continuationToken As String) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-610">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-610">The name of the service.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-611">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-611">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-612">サービスのすべてのパーティションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-612">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="7a036-613">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-613">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-614">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-614">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-615">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-615">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-616">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-616">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-617">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-617">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-618">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-618">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-619">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-619">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-620">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-620">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-621">詳細を取得するパーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-621">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-622">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-622">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-623">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-623">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-624">サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-624">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="7a036-625">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-625">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-626">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-626">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-627">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-627">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-628">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-628">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-629">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-629">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-630">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-630">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-631">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-631">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="7a036-632">詳細を取得するパーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-632">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-633">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-633">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-634">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-634">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-635">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-635">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-636">サービスのすべてのパーティションまたは指定されたパーティションのみの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-636">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="7a036-637">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-637">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-638">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-638">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-639">返されたタスクには、としてパーティションの一覧が含まれています。<see cref="T:System.Fabric.Query.ServicePartitionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-639">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-640">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-640">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-641">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-641">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-642">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-642">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionLoadInformationAsync (partitionId As Guid) As Task(Of PartitionLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-643">負荷の情報を取得する、パーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-643">The partition ID of the partition to get load information for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-644">パーティションの読み込みに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-644">Gets the information about the partition load.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-645">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-645">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-646">返されたタスクとパーティションの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.PartitionLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-646">The returned task contains the load information of a partition as <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-647">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-647">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-648">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-648">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-649">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-649">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-650">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-650">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-651">負荷の情報を取得する、パーティションのパーティション ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-651">The partition ID of the partition to get load information for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-652">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-652">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-653">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-653">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-654">パーティションの読み込みに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-654">Gets the information about the partition load.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-655">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-655">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-656">返されたタスクとパーティションの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.PartitionLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-656">The returned task contains the load information of a partition as <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-657">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-657">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-658">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-658">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-659">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-659">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync () As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7a036-660">システムでプロビジョニングされたすべてのクラスター コード バージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-660">Gets details for all cluster code versions provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-661">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-661">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-662">返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-662">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-663">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-663">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-664">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-664">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-665">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-665">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync (codeVersionFilter As String) As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync codeVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para><span data-ttu-id="7a036-666">詳細を取得するコードのバージョン。</span><span class="sxs-lookup"><span data-stu-id="7a036-666">The code version to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-667">特定のクラスター コードのバージョンが、システムでプロビジョニングの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-667">Gets details for the specific cluster code version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-668">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-668">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-669">返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-669">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-670">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-670">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-671">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-671">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-672">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-672">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-673">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-673">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync (codeVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para><span data-ttu-id="7a036-674">コードのバージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-674">Code version to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-675">TimeoutException がスローされる前に完了する操作にできる最長時間。</span><span class="sxs-lookup"><span data-stu-id="7a036-675">The maximum time allowed for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-676">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="7a036-676">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-677">特定のクラスター コードのバージョンが、システムでプロビジョニングの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-677">Gets details for the specific cluster code version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-678">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-678">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-679">返されたタスクには、プロビジョニング済みの Service Fabric コード バージョンとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-679">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-680">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-680">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-681">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-681">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-682">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-682">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync () As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7a036-683">システムでプロビジョニングされたすべてのクラスター構成バージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-683">Gets details for all cluster config versions provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-684">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-684">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-685">返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-685">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-686">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-686">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-687">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-687">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-688">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-688">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync (configVersionFilter As String) As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync configVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para><span data-ttu-id="7a036-689">Config のバージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-689">The config version to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-690">システムでプロビジョニングされた特定のクラスター構成のバージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-690">Gets details for a specific cluster config version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-691">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-691">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-692">返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-692">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-693">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-693">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-694">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-694">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-695">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-695">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-696">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-696">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync (configVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para><span data-ttu-id="7a036-697">Config のバージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-697">The config version to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-698">TimeoutException がスローされる前に完了する操作にできる最長時間。</span><span class="sxs-lookup"><span data-stu-id="7a036-698">The maximum time allowed for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-699">将来使用するために予約されています。</span><span class="sxs-lookup"><span data-stu-id="7a036-699">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-700">システムでプロビジョニングされた特定のクラスター構成のバージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-700">Gets details for a specific cluster config version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-701">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-701">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-702">返されたタスクには、としてプロビジョニング済みの Service Fabric config のバージョンの一覧が含まれています。<see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-702">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-703">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-703">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-704">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-704">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-705">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-705">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-706">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-706">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-707">パーティションのすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-707">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="7a036-708">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-708">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-709">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-709">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-710">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-710">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-711">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-711">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-712">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-712">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-713">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-713">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-714">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-714">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-715">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-715">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, replicaIdOrInstanceIdFilter As Long) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-716">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-716">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="7a036-717">レプリカ識別子またはインスタンス識別子のレプリカを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-717">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-718">パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-718">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="7a036-719">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-719">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-720">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-720">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-721">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-721">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-722">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-722">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-723">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-723">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-724">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-724">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-725">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-725">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-726">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-726">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-727">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-727">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, continuationToken As String) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-728">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-728">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-729">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-729">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-730">パーティションのすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-730">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="7a036-731">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-731">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-732">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-732">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-733">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-733">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-734">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-734">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-735">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-735">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-736">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-736">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-737">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-737">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-738">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-738">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-739">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-739">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-740">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-740">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="7a036-741">レプリカ識別子またはインスタンス識別子のレプリカを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-741">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-742">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-742">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-743">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-743">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-744">パーティションのレプリカまたはインスタンスのフィルターに一致するすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-744">Gets the details for all replicas of a partition that match the replica or instance filter.</span></span> <span data-ttu-id="7a036-745">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-745">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-746">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-746">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-747">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-747">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-748">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-748">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-749">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-749">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-750">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-750">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-751">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-751">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-752">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-752">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-753">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-753">The partition identifier of the partition to get replicas for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-754">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-754">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-755">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-755">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-756">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-756">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-757">パーティションのすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-757">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="7a036-758">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-758">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-759">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-759">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-760">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-760">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-761">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-761">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-762">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-762">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-763">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-763">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-764">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-764">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-765">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-765">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-766">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-766">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="7a036-767">レプリカ識別子またはインスタンス識別子のレプリカを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-767">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="replicaStatusFilter">
          <para><span data-ttu-id="7a036-768">レプリカを取得するレプリカ性状態です。</span><span class="sxs-lookup"><span data-stu-id="7a036-768">The replica status(es) to get replicas for.</span></span></para>
        </param>
        <param name="timeout"><span data-ttu-id="7a036-769">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-769">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7a036-770">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-770">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="7a036-771">パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-771">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="7a036-772">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-772">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-773">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-773">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-774">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-774">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-775">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-775">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-776">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-776">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-777">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-777">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-778">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-778">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-779">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-779">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-780">レプリカを取得するパーティションのパーティション識別子です。</span><span class="sxs-lookup"><span data-stu-id="7a036-780">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="7a036-781">レプリカ識別子またはインスタンス識別子のレプリカを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-781">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="replicaStatusFilter">
          <para><span data-ttu-id="7a036-782">ものだけにこのレプリカの状態に一致する結果をフィルター処理します。</span><span class="sxs-lookup"><span data-stu-id="7a036-782">Filter results to include only those matching this replica status.</span></span></para>
        </param>
        <param name="continuationToken"><span data-ttu-id="7a036-783">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-783">The continuation token obtained from a previous query.</span></span></param>
        <param name="timeout"><span data-ttu-id="7a036-784">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-784">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7a036-785">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-785">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="7a036-786">パーティションのレプリカまたはインスタンスのフィルターおよびステータス フィルターに一致するすべてのレプリカの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-786">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="7a036-787">ページで、レプリカが収まらない場合、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-787">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-788">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-788">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-789">返されたタスクには、として、パーティションのレプリカ情報が含まれています。<see cref="T:System.Fabric.Query.ServiceReplicaList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-789">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="7a036-790">Service Fabric は、多くのコンポーネントが、同じエンティティの表示をある分散システムです。</span><span class="sxs-lookup"><span data-stu-id="7a036-790">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="7a036-791">このビューと一致しない、不安定になったり一時的な状態で<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />と<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="7a036-791">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-792">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-792">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-793">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-793">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-794">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-794">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaLoadInformationAsync (partitionId As Guid, replicaIdOrInstanceId As Long) As Task(Of ReplicaLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-795">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="7a036-795">The partition ID.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para><span data-ttu-id="7a036-796">レプリカ ID (ステートフル サービス) または (ステートレス サービス) のインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-796">The replica ID (stateful service) or instance ID (stateless service).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-797">レプリカ上のメトリックとその負荷の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-797">Get a list of metric and their load on a replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-798">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-798">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-799">返されたタスクと、レプリカの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.ReplicaLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-799">The returned task contains the load information of the replica as <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-800">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-800">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-801">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-801">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-802">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-802">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-803">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-803">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-804">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="7a036-804">The partition ID.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para><span data-ttu-id="7a036-805">レプリカ ID (ステートフル サービス) または (ステートレス サービス) のインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7a036-805">The replica ID (stateful service) or instance ID (stateless service).</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-806">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-806">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-807">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-807">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-808">レプリカ上のメトリックとその負荷の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-808">Get a list of metric and their load on a replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-809">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-809">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-810">返されたタスクと、レプリカの読み込み情報が含まれています。<see cref="T:System.Fabric.Query.ReplicaLoadInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-810">The returned task contains the load information of the replica as <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-811">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-811">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-812">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-812">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-813">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-813">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-814">サービス グループのアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-814">The application name of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-815">アプリケーションのサービス グループのメンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-815">Get service group members of an application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-816">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-816">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-817">返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-817">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-818">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-818">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-819">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-819">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-820">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-820">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-821">サービス グループのアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-821">The application name of the service group.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-822">サービス グループのサービス名。</span><span class="sxs-lookup"><span data-stu-id="7a036-822">The service name of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-823">アプリケーションのサービス グループのメンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-823">Get service group members of an application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-824">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-824">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-825">返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-825">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-826">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-826">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-827">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-827">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-828">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-828">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-829">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-829">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-830">サービス グループのアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-830">The application name of the service group.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-831">サービス グループのサービス名。</span><span class="sxs-lookup"><span data-stu-id="7a036-831">The service name of the service group.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-832">操作をタイムアウトしました。</span><span class="sxs-lookup"><span data-stu-id="7a036-832">The timeout to the operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-833">操作をキャンセルするかを通知します。</span><span class="sxs-lookup"><span data-stu-id="7a036-833">Notifies the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-834">サービスのすべてのパーティションの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-834">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="7a036-835">パーティションは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-835">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-836">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-836">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-837">返されたタスクには、サービス グループのメンバーとしての一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-837">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-838">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-838">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-839">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-839">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-840">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-840">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-841">サービス グループのアプリケーションの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-841">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-842">サービス グループのアプリケーション タイプのバージョン。</span><span class="sxs-lookup"><span data-stu-id="7a036-842">The application type version of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-843">サービス グループ メンバーのサービス グループの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-843">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-844">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-844">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-845">返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-845">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-846">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-846">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-847">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-847">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-848">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-848">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceGroupTypeNameFilter As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-849">サービス グループのアプリケーションの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-849">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-850">サービス グループのアプリケーション タイプのバージョン。</span><span class="sxs-lookup"><span data-stu-id="7a036-850">The application type version of the service group.</span></span></para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para><span data-ttu-id="7a036-851">取得するサービスのグループの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-851">The name of the service group type to get.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-852">サービス グループ メンバーのサービス グループの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-852">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-853">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-853">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-854">返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-854">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-855">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-855">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-856">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-856">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-857">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-857">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-858">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-858">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-859">サービス グループのアプリケーションの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-859">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-860">サービス グループのアプリケーション タイプのバージョン。</span><span class="sxs-lookup"><span data-stu-id="7a036-860">The application type version of the service group.</span></span></para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para><span data-ttu-id="7a036-861">取得するサービスのグループの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-861">The name of the service group type to get.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-862">操作をタイムアウトしました。</span><span class="sxs-lookup"><span data-stu-id="7a036-862">The timeout to the operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-863">操作をキャンセルするかを通知します。</span><span class="sxs-lookup"><span data-stu-id="7a036-863">Notifies the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-864">サービス グループ メンバーのサービス グループの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-864">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-865">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-865">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-866">返されたタスクには、サービスとしてのグループ メンバーの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-866">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-867">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-867">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-868">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-868">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-869">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-869">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-870">サービスを取得するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-870">The name of the application to get services for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-871">アプリケーションの名前 URI で指定されたアプリケーションに属するすべてのサービスに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-871">Gets the information about all services belonging to the application specified by the application name URI.</span></span> <span data-ttu-id="7a036-872">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-872">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-873">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-873">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-874">返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-874">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-875">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-875">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-876">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-876">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-877">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-877">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-878">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-878">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-879">サービスを取得するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-879">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-880">詳細を取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-880">The name of the services to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-881">アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-881">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="7a036-882">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-882">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-883">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-883">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-884">返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-884">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-885">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-885">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-886">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-886">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-887">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-887">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-888">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-888">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri, continuationToken As String) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-889">サービスを取得するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-889">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-890">詳細を取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-890">The name of the services to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-891">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-891">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-892">アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-892">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="7a036-893">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-893">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-894">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-894">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-895">返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-895">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-896">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-896">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-897">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-897">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-898">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-898">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-899">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-899">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-900">サービスを取得するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-900">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-901">詳細を取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-901">The name of the services to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-902">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-902">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-903">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-903">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-904">アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-904">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="7a036-905">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-905">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-906">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-906">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-907">返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-907">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-908">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-908">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-909">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-909">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-910">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-910">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="7a036-911">サービスを取得するアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-911">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="7a036-912">詳細を取得するサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="7a036-912">The name of the services to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="7a036-913">前のクエリから取得された継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="7a036-913">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-914">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-914">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-915">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-915">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="7a036-916">アプリケーションのすべてのサービスまたは指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-916">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="7a036-917">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-917">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-918">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-918">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="7a036-919">返されるタスクには、サービスとしての一覧が含まれています<see cref="T:System.Fabric.Query.ServiceList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-919">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-920">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-920">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-921">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-921">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-922">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-922">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceNameAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceNameAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;" Usage="queryClient.GetServiceNameAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-923">サービス名を取得するパーティションの id。</span><span class="sxs-lookup"><span data-stu-id="7a036-923">The id of the partition to get the service name for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-924">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-924">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-925">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-925">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-926">指定したパーティションのサービス名を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-926">Gets the service name for the specified partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-927">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-927">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-928">返されたタスクには、として、サービス名が含まれています。<see cref="T:System.Fabric.Query.ServiceNameResult" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-928">The returned task contains the service name as <see cref="T:System.Fabric.Query.ServiceNameResult" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-929">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-929">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-930">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-930">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-931">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-931">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync serviceQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><span data-ttu-id="7a036-932"><see cref="T:System.Fabric.Description.ServiceQueryDescription" />を決定するどのサービスを照会する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a036-932">The <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> that determines which services should be queried.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-933">アプリケーションのすべてのサービスまたは (指定されている場合)、クエリの説明で指定されたフィルターに一致する指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-933">Gets the details for all services of an application or just the specified services that match filters specified in query description (if any).</span></span> <span data-ttu-id="7a036-934">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-934">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-935">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-935">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="7a036-936">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ServiceList" />内のフィルターを適用するサービスの一覧を表す、<see cref="T:System.Fabric.Query.ServiceList" />ページに合わせてとします。</span><span class="sxs-lookup"><span data-stu-id="7a036-936">The value of TResult parameter is a <see cref="T:System.Fabric.Query.ServiceList" /> that represents the list of services that respect the filters in the <see cref="T:System.Fabric.Query.ServiceList" /> and fit the page.</span></span>
            <span data-ttu-id="7a036-937">指定されたクエリの説明に一致するサービスがあるない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-937">If the provided query description has no matching services, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-938">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-938">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-939">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-939">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-940">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-940">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync (serviceQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><span data-ttu-id="7a036-941"><see cref="T:System.Fabric.Description.ServiceQueryDescription" />を決定するどのサービスを照会する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7a036-941">The <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> that determines which services should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-942">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-942">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-943">操作を取り消す必要がある通知を伝達します。</span><span class="sxs-lookup"><span data-stu-id="7a036-943">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-944">アプリケーションのすべてのサービスまたは (指定されている場合)、クエリの説明で指定されたフィルターに一致する指定したサービスだけの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-944">Gets the details for all services of an application or just the specified services that match filters specified in query description (if any).</span></span> <span data-ttu-id="7a036-945">サービスは、ページに収まり切らない、次のページを取得するために使用する継続トークンと結果の 1 つのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="7a036-945">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-946">A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="7a036-946">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="7a036-947">TResult のパラメーターの値は、<see cref="T:System.Fabric.Query.ServiceList" />内のフィルターを適用するサービスの一覧を表す、<see cref="T:System.Fabric.Query.ServiceList" />ページに合わせてとします。</span><span class="sxs-lookup"><span data-stu-id="7a036-947">The value of TResult parameter is a <see cref="T:System.Fabric.Query.ServiceList" /> that represents the list of services that respect the filters in the <see cref="T:System.Fabric.Query.ServiceList" /> and fit the page.</span></span>
            <span data-ttu-id="7a036-948">指定されたクエリの説明に一致するサービスがあるない場合は、エントリ数が 0 の一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-948">If the provided query description has no matching services, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-949">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-949">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-950">参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-950">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-951">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-951">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-952">サービスの種類を取得するアプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="7a036-952">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-953">アプリケーション タイプのバージョンのサービス型を取得するには。</span><span class="sxs-lookup"><span data-stu-id="7a036-953">The application type version to get service types for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-954">サービスの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-954">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-955">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-955">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-956">返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-956">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-957">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-957">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-958">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-958">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-959">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-959">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceTypeNameFilter As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-960">サービスの種類を取得するアプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="7a036-960">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-961">アプリケーション タイプのバージョンのサービス型を取得するには。</span><span class="sxs-lookup"><span data-stu-id="7a036-961">The application type version to get service types for.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="7a036-962">詳細を取得するサービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-962">The name of the service type to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-963">サービスの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-963">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-964">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-964">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-965">返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-965">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-966">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-966">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-967">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-967">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-968">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-968">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-969">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-969">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="7a036-970">サービスの種類を取得するアプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="7a036-970">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="7a036-971">アプリケーション タイプのバージョンのサービス型を取得するには。</span><span class="sxs-lookup"><span data-stu-id="7a036-971">The application type version to get service types for.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="7a036-972">詳細を取得するサービスの種類の名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-972">The name of the service type to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-973">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-973">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-974">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-974">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-975">サービスの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-975">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-976">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-976">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-977">返されたタスクには、としてサービスの種類の一覧が含まれています。<see cref="T:System.Fabric.Query.ServiceTypeList" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-977">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-978">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-978">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-979">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-979">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-980">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-980">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUnplacedReplicaInformationAsync (serviceName As String, partitionId As Guid, onlyQueryPrimaries As Boolean) As Task(Of UnplacedReplicaInformation)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-981">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-981">The name of the service.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-982">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="7a036-982">The partition ID.</span></span></para>
        </param>
        <param name="onlyQueryPrimaries">
          <para><span data-ttu-id="7a036-983">出力を制限するためにのみ、unplaced レプリカの診断を実行しようとしたプライマリ レプリカの配置のみを返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-983">Return only the unplaced replica diagnostics for only the attempted primary replica placements in order to limit output.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-984">Unplaced レプリカとサービスに関する診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-984">Get diagnostics information about services with unplaced replicas.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-985">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-985">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-986">返されたタスクが未配置レプリカとしての情報を含む<see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-986">The returned task contains the information of an unplaced replica as <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-987">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-987">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="7a036-988">この操作では、60 秒のタイムアウトがあります。</span><span class="sxs-lookup"><span data-stu-id="7a036-988">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="7a036-989">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-989">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-990">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-990">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="7a036-991">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="7a036-991">The name of the service.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="7a036-992">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="7a036-992">The partition ID.</span></span></para>
        </param>
        <param name="onlyQueryPrimaries">
          <para><span data-ttu-id="7a036-993">出力を制限するためにのみ、unplaced レプリカの診断を実行しようとしたプライマリ レプリカの配置のみを返します。</span><span class="sxs-lookup"><span data-stu-id="7a036-993">Return only the unplaced replica diagnostics for only the attempted primary replica placements in order to limit output.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="7a036-994">この操作がタイムアウトするまでに完了する必要がある期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="7a036-994">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="7a036-995">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="7a036-995">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="7a036-996">Unplaced レプリカとサービスに関する診断情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="7a036-996">Get diagnostics information about services with unplaced replicas.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="7a036-997">非同期クエリ操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="7a036-997">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="7a036-998">返されたタスクが未配置レプリカとしての情報を含む<see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />です。</span><span class="sxs-lookup"><span data-stu-id="7a036-998">The returned task contains the information of an unplaced replica as <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="7a036-999">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-999">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="7a036-1000">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-1000">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="7a036-1001">関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="7a036-1001">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>