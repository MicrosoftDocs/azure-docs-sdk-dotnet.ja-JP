<Type Name="PagedApplicationTypeQueryDescription" FullName="System.Fabric.Description.PagedApplicationTypeQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PagedApplicationTypeQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PagedApplicationTypeQueryDescription" />
  <TypeSignature Language="F#" Value="type PagedApplicationTypeQueryDescription = class" />
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
      <para><span data-ttu-id="665fc-101">クエリを実行するときに使用されるフィルターのセットを示す<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />です。</span><span class="sxs-lookup"><span data-stu-id="665fc-101">Describes a set of filters used when running the query <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="665fc-102">このクエリの説明の既定値は、結果が最初のページから返され、フィルターは適用されませんを確認します。</span><span class="sxs-lookup"><span data-stu-id="665fc-102">The default values of this query description ensure that results are returned from the first page and apply no filters.</span></span>
            <span data-ttu-id="665fc-103">このクエリの説明は、個々 のプロパティを設定してカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="665fc-103">This query description can be customized by setting individual properties.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PagedApplicationTypeQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="665fc-104"><see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="665fc-104">Initializes a new instance of the <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeDefinitionKindFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeDefinitionKindFilter As ApplicationTypeDefinitionKindFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeDefinitionKindFilter : System.Fabric.Description.ApplicationTypeDefinitionKindFilter with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeDefinitionKindFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="665fc-105">取得または設定の定義の種類が返されるアプリケーションの種類をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="665fc-105">Gets or sets the definition kind used to filter the application types that will be returned.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="665fc-106">定義の種類をアプリケーションの種類をフィルター処理するために使用します。</span><span class="sxs-lookup"><span data-stu-id="665fc-106">The definition kind used to filter the application types.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="665fc-107">ApplicationTypeDefinitionKindFilter が指定されていない場合、結果は定義の種類によってフィルターされません。</span><span class="sxs-lookup"><span data-stu-id="665fc-107">If ApplicationTypeDefinitionKindFilter is not specified, the result would not be filtered by definition kind.</span></span></para>
          <para><span data-ttu-id="665fc-108">ApplicationTypeNameFilter と ApplicationTypeDefinitionKindFilter を同時に指定するはありません。</span><span class="sxs-lookup"><span data-stu-id="665fc-108">ApplicationTypeNameFilter and ApplicationTypeDefinitionKindFilter can not be specified together.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="665fc-109">取得または設定の詳細を取得するアプリケーションの種類。</span><span class="sxs-lookup"><span data-stu-id="665fc-109">Gets or sets the application type to get details for.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="665fc-110">既定値は null の場合、すべてのアプリケーションの種類と一致しています。</span><span class="sxs-lookup"><span data-stu-id="665fc-110">Defaults to null, which matches all the application types.</span></span>
            </para>
          <para>
            <span data-ttu-id="665fc-111">このパラメーターは、プロビジョニングまたはプロビジョニングのアプリケーションのすべての種類のアプリケーション マニフェストで定義されている大文字小文字を区別の正確なアプリケーションの種類名と一致します。</span><span class="sxs-lookup"><span data-stu-id="665fc-111">This parameter matches against the case sensitive exact application type names defined in the application manifest of all provisioned or provisioning application types.</span></span> <span data-ttu-id="665fc-112">たとえば、"Test"の値と一致しません"TestApp"部分的な一致しかになっているためです。</span><span class="sxs-lookup"><span data-stu-id="665fc-112">For example, the value "Test" does not match "TestApp" because it is only a partial match.</span></span>
            <span data-ttu-id="665fc-113">この値は、アプリケーションの種類のバージョンを含めることはできません、同じアプリケーションの種類名のすべてのバージョンと一致します。</span><span class="sxs-lookup"><span data-stu-id="665fc-113">This value should not contain the version of the application type, and matches all versions of the same application type name.</span></span>
            <span data-ttu-id="665fc-114">すべてのアプリケーションの種類がないを要求するには、この値を設定します。</span><span class="sxs-lookup"><span data-stu-id="665fc-114">To request all the application types do not set this value.</span></span>
            </para>
          <para>
            <span data-ttu-id="665fc-115">ApplicationTypeNameFilter と ApplicationTypeDefinitionKindFilter を同時に指定するはありません。</span><span class="sxs-lookup"><span data-stu-id="665fc-115">ApplicationTypeNameFilter and ApplicationTypeDefinitionKindFilter can not be specified together.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersionFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersionFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersionFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeVersionFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersionFilter : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ApplicationTypeVersionFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="665fc-116">取得または設定のアプリケーション タイプ バージョンの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="665fc-116">Gets or sets the application type version to get details for.</span></span>
            </para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="665fc-117">既定値は null の場合、すべてのアプリケーションに一致するバージョンの特定のアプリケーションの種類名を入力します。</span><span class="sxs-lookup"><span data-stu-id="665fc-117">Defaults to null, which matches all the application type versions of a given application type name.</span></span> <span data-ttu-id="665fc-118">アプリケーションの種類の名前フィルターも含まれている場合にのみ、このフィルターを指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="665fc-118">This filter should be provided only if an application type name filter is also provided.</span></span>
            </para>
          <para>
            <span data-ttu-id="665fc-119">このパラメーターは、すべてのアプリケーションのプロビジョニングまたはプロビジョニングの種類のアプリケーション マニフェストで定義されている大文字小文字を区別の正確なアプリケーション タイプ バージョンに対してと一致します。</span><span class="sxs-lookup"><span data-stu-id="665fc-119">This parameter matches against the case sensitive exact application type version defined in the application manifest of all provisioned or provisioning application types.</span></span>
            <span data-ttu-id="665fc-120">たとえば、"v1"バージョンと一致しませんバージョン"v1.0"部分的な一致しかになっているためです。</span><span class="sxs-lookup"><span data-stu-id="665fc-120">For example, version "v1" does not match version "v1.0" because it is only a partial match.</span></span>
            <span data-ttu-id="665fc-121">アプリケーションの種類名のすべてのアプリケーション タイプ バージョンを要求するには、この値を設定しないでください。</span><span class="sxs-lookup"><span data-stu-id="665fc-121">To request all the application type versions of an application type name, do not set this value.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="665fc-122">取得または次のページを取得するために使用する継続トークンを設定します。</span><span class="sxs-lookup"><span data-stu-id="665fc-122">Gets or sets the continuation token which can be used to retrieve the next page.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="665fc-123">既定値は null の場合、クエリ結果のいずれかのページが返されます。</span><span class="sxs-lookup"><span data-stu-id="665fc-123">Defaults to null, which returns page one of query results.</span></span>
            </para>
          <para>
            <span data-ttu-id="665fc-124">フィルターを適用する結果が多すぎる場合、1 つのメッセージに収まらない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="665fc-124">If too many results respect the filter, they may not fit into one message.</span></span>
            <span data-ttu-id="665fc-125">コレクションを分割してこの問題に対応するページングが使用される<see cref="T:System.Fabric.Query.ApplicationType" />別のページにします。</span><span class="sxs-lookup"><span data-stu-id="665fc-125">Paging is used to account for this by splitting the collection of <see cref="T:System.Fabric.Query.ApplicationType" />s into separate pages.</span></span>
            <span data-ttu-id="665fc-126">継続トークンが、前のページ、中断場所を知るため、クエリ自体にのみ意味を実行します。</span><span class="sxs-lookup"><span data-stu-id="665fc-126">The continuation token is used to know where the previous page left off, carrying significance only to the query itself.</span></span>
            <span data-ttu-id="665fc-127">この値は、このクエリを実行してから生成するか、後続のページを取得するために、次のクエリ要求に渡すことができます。</span><span class="sxs-lookup"><span data-stu-id="665fc-127">This value should be generated from running this query, and can be passed into the next query request in order to get subsequent pages.</span></span>
            <span data-ttu-id="665fc-128">Null 以外の継続トークンの値は、後続のページがある場合にのみ、結果の一部として返されます。</span><span class="sxs-lookup"><span data-stu-id="665fc-128">A non-null continuation token value is returned as part of the result only if there is a subsequent page.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeApplicationParameters">
      <MemberSignature Language="C#" Value="public bool ExcludeApplicationParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeApplicationParameters As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeApplicationParameters : bool with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.ExcludeApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="665fc-129">取得またはアプリケーションのパラメーターをクエリ結果から除外するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="665fc-129">Gets or sets whether to exclude application parameters from the query result.</span></span></para>
        </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="665fc-130">既定値は false。</span><span class="sxs-lookup"><span data-stu-id="665fc-130">Defaults to false.</span></span>
            </para>
          <para>
            <span data-ttu-id="665fc-131">この場合は true。 リーフに設定、<see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" />空白。</span><span class="sxs-lookup"><span data-stu-id="665fc-131">Setting this to true leaves the <see cref="P:System.Fabric.Query.ApplicationType.DefaultParameters" /> blank.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="System.Fabric.Description.PagedApplicationTypeQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="665fc-132">取得または設定の数が最大<see cref="T:System.Fabric.Query.ApplicationType" />のページごとに返されることができます。</span><span class="sxs-lookup"><span data-stu-id="665fc-132">Gets or sets the max number of <see cref="T:System.Fabric.Query.ApplicationType" />s that can be returned per page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="665fc-133">既定値は long 型の最大値です。</span><span class="sxs-lookup"><span data-stu-id="665fc-133">Defaults to the max value of type long.</span></span>
            </para>
          <para><span data-ttu-id="665fc-134">これは、アプリケーションの種類が返される、最小値ではない数の上限の境界のみを定義します。</span><span class="sxs-lookup"><span data-stu-id="665fc-134">This defines only the upper bound for the number of application types returned, not a minimum.</span></span>
            <span data-ttu-id="665fc-135">たとえば、ページが収まる最大で 1000 が返される場合構成では、最大メッセージ サイズの制限に従って項目が定義されてし、MaxResults 値に設定されている 2000 では、1000 を超える結果が返されます場合でも、2000 のアプリケーションの種類、クエリの説明に一致します。</span><span class="sxs-lookup"><span data-stu-id="665fc-135">For example, if the page fits at most 1000 returned items according to max message size restrictions defined in the configuration, and the MaxResults value is set to 2000, then only 1000 results are returned, even if 2000 application types match the query description.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.PagedApplicationTypeQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="pagedApplicationTypeQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="665fc-136">クエリの説明のすべてのコンテンツを印刷する ToString() メソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="665fc-136">Overrides ToString() method to print all content of the query description.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="665fc-137">クエリの説明のすべてのプロパティを含む文字列を返します。</span><span class="sxs-lookup"><span data-stu-id="665fc-137">Returns a string containing all the properties of the query description.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>