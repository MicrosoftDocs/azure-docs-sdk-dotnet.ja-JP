<Type Name="ODATADetailLevel" FullName="Microsoft.Azure.Batch.ODATADetailLevel">
  <TypeSignature Language="C#" Value="public class ODATADetailLevel : Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ODATADetailLevel extends Microsoft.Azure.Batch.DetailLevel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ODATADetailLevel" />
  <TypeSignature Language="VB.NET" Value="Public Class ODATADetailLevel&#xA;Inherits DetailLevel" />
  <TypeSignature Language="F#" Value="type ODATADetailLevel = class&#xA;    inherit DetailLevel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.DetailLevel</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="c9a79-101">一覧表示するか、OData のクエリ句を使用して、リソースを取得するときに Azure Batch のサービスから要求される詳細情報の量を制御します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-101">Controls the amount of detail requested from the Azure Batch service when listing or retrieving resources, using OData query clauses.</span></span>
             </summary>
    <remarks>
      <para><span data-ttu-id="c9a79-102">Azure Batch は、一覧操作で返されるどのリソースを制御することでクエリのパフォーマンスをより細かく制御を取得するためにクライアントを許可するは、OData クエリをサポートしています (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />)、リスト、Get または更新の各リソースのプロパティが返されます操作 (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />と<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />)。</span><span class="sxs-lookup"><span data-stu-id="c9a79-102">Azure Batch supports OData queries, which allow the client to gain finer control over query performance by controlling which resources are returned in List operations (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />), and which properties of each resource are returned in List, Get or Refresh operations (<see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" /> and <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />).</span></span></para>
      <para><span data-ttu-id="c9a79-103">既定を渡さない場合、<see cref="T:Microsoft.Azure.Batch.DetailLevel" />の一覧を取得または更新操作、バッチ クライアント フィルターを指定されません (すべてのレコードが返されます)、展開句の select 句のない (すべての単純なプロパティが返されます) と いいえ (関連付けられているエンティティは返されません)。</span><span class="sxs-lookup"><span data-stu-id="c9a79-103">By default, if you do not pass a <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> to a List, Get or Refresh operation, the Batch client specifies no filter (all records are returned), no select clause (all simple properties are returned) and no expand clause (associated entities are not returned).</span></span>  <span data-ttu-id="c9a79-104">その結果、既定では、関連付けられているエンティティ プロパティは、その他のプロパティと同様に登録されているのではなく、null の場合。</span><span class="sxs-lookup"><span data-stu-id="c9a79-104">Consequently, by default, associated entity properties are null, rather than being populated like other properties.</span></span>  <span data-ttu-id="c9a79-105">個々 のクラスのマニュアルを参照するプロパティが関連付けられているエンティティと見なされ、展開すると、設定する必要がありますを参照してください。</span><span class="sxs-lookup"><span data-stu-id="c9a79-105">Refer to individual class documentation to find out which properties are considered associated entities and need to be expanded to be populated.</span></span></para>
      <para><span data-ttu-id="c9a79-106">OData クエリは、REST API に直接渡されるため句文字列では JSON 属性の名前から、REST API ではない常に .NET プロパティの名前と同じを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-106">Because the OData queries are passed directly to the REST API, clause strings must use the JSON attribute names from the REST API, which are not always the same as .NET property names.</span></span>  <span data-ttu-id="c9a79-107">たとえば、.NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see>プロパティは、REST API の vmSize 属性に対応していますそのため、VM のサイズによってプールの一覧操作をフィルターするにはする必要 VirtualMachineSize ではなく vmSize 記述。で、フィルター文字列。</span><span class="sxs-lookup"><span data-stu-id="c9a79-107">For example, the .NET <see cref="P:Microsoft.Azure.Batch.CloudPool.VirtualMachineSize">CloudPool.VirtualMachineSize</see> property corresponds to the vmSize attribute in the REST API; therefore, to filter a pool list operations by VM size, you would need to write vmSize rather than VirtualMachineSize in your filter string.</span></span>  <span data-ttu-id="c9a79-108">.NET プロパティに対応する JSON 属性名を見つけるに REST API のドキュメントを参照してください。</span><span class="sxs-lookup"><span data-stu-id="c9a79-108">Refer to the REST API documentation to find out the JSON attribute name corresponding to a .NET property.</span></span></para>
      <para><span data-ttu-id="c9a79-109">OData を使用して、Azure Batch サービスを効率的にクエリする方法の詳細については、次を参照してください。<a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">効率的なリスト クエリ</a>msdn です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-109">For additional information about using OData to efficiently query the Azure Batch service, see <a href="https://azure.microsoft.com/en-us/documentation/articles/batch-efficient-list-queries/">Efficient List Queries</a> on MSDN.</span></span></para>
    </remarks>
    <example>
             <span data-ttu-id="c9a79-110">このサンプルは、唯一アクティブを一覧表示する ODataDetailLevel を指定する方法を示します<see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>、のみを取得し、 <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />、<see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" />プールごとに (たとえば、レポート ユーザーに表示インターフェイス) です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-110">This sample shows how to specify an ODataDetailLevel that lists only active <see cref="T:Microsoft.Azure.Batch.CloudPool">CloudPools</see>, and retrieves only the <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />, <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> for each pool (for example, for display in a reporting user interface).</span></span>
             <code>
             var detailLevel = new ODATADetailLevel(
             filterClause: "state eq 'active'",
             selectClause: "id,displayName,stats",
                 expandClause: "stats"
                 );
                 
             var pools = batchClient.PoolOperations.ListPools(detailLevel);
            </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c9a79-111">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" />空句を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c9a79-111">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> class with empty clauses.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ODATADetailLevel (string filterClause = null, string selectClause = null, string expandClause = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filterClause, string selectClause, string expandClause) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ODATADetailLevel.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional filterClause As String = null, Optional selectClause As String = null, Optional expandClause As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ODATADetailLevel : string * string * string -&gt; Microsoft.Azure.Batch.ODATADetailLevel" Usage="new Microsoft.Azure.Batch.ODATADetailLevel (filterClause, selectClause, expandClause)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filterClause" Type="System.String" />
        <Parameter Name="selectClause" Type="System.String" />
        <Parameter Name="expandClause" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterClause"><span data-ttu-id="c9a79-112">フィルター句。</span><span class="sxs-lookup"><span data-stu-id="c9a79-112">The filter clause.</span></span></param>
        <param name="selectClause"><span data-ttu-id="c9a79-113">select 句。</span><span class="sxs-lookup"><span data-stu-id="c9a79-113">The select clause.</span></span></param>
        <param name="expandClause"><span data-ttu-id="c9a79-114">展開句。</span><span class="sxs-lookup"><span data-stu-id="c9a79-114">The expand clause.</span></span></param>
        <summary>
            <span data-ttu-id="c9a79-115">新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" />指定した句を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="c9a79-115">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ODATADetailLevel" /> class with the specified clauses.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpandClause">
      <MemberSignature Language="C#" Value="public string ExpandClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExpandClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpandClause As String" />
      <MemberSignature Language="F#" Value="member this.ExpandClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9a79-116">取得または設定、OData は、句を展開します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-116">Gets or sets the OData expand clause.</span></span> <span data-ttu-id="c9a79-117">取得するメインのエンティティの関連付けられているエンティティを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-117">Used to retrieve associated entities of the main entity being retrieved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="c9a79-118">これは省略可能な OData $ 式の文字列を展開して<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(OData の仕様を参照してください)</a>です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-118">This is an optional OData $expand expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398162">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="c9a79-119">関連付けられているエンティティを含むプロパティは、ExpandClause に含まれている場合を除き、null になります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-119">Properties containing associated entities will be null unless included in an ExpandClause.</span></span>
            <span data-ttu-id="c9a79-120">具体的には、一覧に、実行する場合を取得または更新を指定しないと、ExpandClause 関連付けられているエンティティのすべてのプロパティは null になります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-120">Specifically, if you perform a List, Get or Refresh and do not specify an ExpandClause, then all associated entity properties will be null.</span></span>  <span data-ttu-id="c9a79-121">たとえばを実行する場合、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />せず、ExpandClause 操作、<see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" />プロパティは null になります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-121">For example, if you perform a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation without an ExpandClause then the <see cref="P:Microsoft.Azure.Batch.CloudPool.Statistics" /> property will be null.</span></span>  <span data-ttu-id="c9a79-122">Statistics プロパティを設定するには、ExpandClause を指定する必要があります<c>stats</c>です。個々 のクラスのマニュアルを参照するプロパティが関連付けられているエンティティと見なされますを参照してください。</span><span class="sxs-lookup"><span data-stu-id="c9a79-122">To populate the Statistics property you must supply an ExpandClause of <c>stats</c>.  Refer to individual class documentation to find out which properties are considered associated entities.</span></span></para>
          <para><span data-ttu-id="c9a79-123">両方、ExpandClause を指定する場合、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />、ExpandClause に表示されるプロパティは、(サービスの応答、SelectClause に示したプロパティのみが含まれている) ために、SelectClause で繰り返す必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-123">If you specify both an ExpandClause and a <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />, then properties listed in the ExpandClause must be repeated in the SelectClause (because only properties listed in the SelectClause are included in the service response).</span></span>  <span data-ttu-id="c9a79-124">(この要件はありません、SelectClause が指定されていない場合ことを意味 'が含まれるためすべてのプロパティで応答します ')</span><span class="sxs-lookup"><span data-stu-id="c9a79-124">(This requirement does not arise if you do not specify a SelectClause, because that means 'include all properties in the response.')</span></span></para>
          <para><span data-ttu-id="c9a79-125">展開は、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-125">Expansions must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="c9a79-126">既定ではない式、つまり、関連付けられているオブジェクトは返されませんを展開して (および対応するプロパティが null)。</span><span class="sxs-lookup"><span data-stu-id="c9a79-126">The default is no expand expression, which means no associated objects are returned (and the corresponding properties are null).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterClause">
      <MemberSignature Language="C#" Value="public string FilterClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterClause As String" />
      <MemberSignature Language="F#" Value="member this.FilterClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.FilterClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9a79-127">取得または OData フィルター句を設定します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-127">Gets or sets the OData filter clause.</span></span> <span data-ttu-id="c9a79-128">指定した条件に一致する項目を一覧表示操作を制限するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-128">Used to restrict a list operation to items that match specified criteria.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="c9a79-129">これは省略可能な OData $filter 式の文字列<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(OData の仕様を参照してください)</a>です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-129">This is an optional OData $filter expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398094">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="c9a79-130">たとえば、制限することができます、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />を式にアクティブなプールのみを返す操作<c>状態 eq 'アクティブ'</c>です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-130">For example, you can restrict a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation to return only active pools with the expression <c>state eq 'active'</c>.</span></span></para>
          <para><span data-ttu-id="c9a79-131">フィルターは、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-131">Filters must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="c9a79-132">既定値には、フィルター式は、すべてのリソースが返されることを意味はありません。</span><span class="sxs-lookup"><span data-stu-id="c9a79-132">The default is no filter expression, which means all resources are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectClause">
      <MemberSignature Language="C#" Value="public string SelectClause { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelectClause" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectClause As String" />
      <MemberSignature Language="F#" Value="member this.SelectClause : string with get, set" Usage="Microsoft.Azure.Batch.ODATADetailLevel.SelectClause" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9a79-133">取得または OData select 句を設定します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-133">Gets or sets the OData select clause.</span></span> <span data-ttu-id="c9a79-134">すべてのオブジェクトのプロパティではなく特定のプロパティだけを取得するために使用します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-134">Used to retrieve only specific properties instead of all object properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="c9a79-135">これは省略可能な OData $select 式の文字列<a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(OData の仕様を参照してください)</a>です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-135">This is an optional OData $select expression string <a href="http://docs.oasis-open.org/odata/odata/v4.0/errata02/os/complete/part2-url-conventions/odata-v4.0-errata02-os-part2-url-conventions-complete.html#_Toc406398163">(see the OData specification)</a>.</span></span>
            <span data-ttu-id="c9a79-136">SelectClause を提供する場合<b>のみ</b>その句のリストにプロパティが設定されてです。 その他のプロパティに既定値 (通常 null)。</span><span class="sxs-lookup"><span data-stu-id="c9a79-136">If you provide a SelectClause, then <b>only</b> the properties listed in that clause are populated; other properties have their default values (typically null).</span></span>  <span data-ttu-id="c9a79-137">実行する場合など、<see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />の SelectClause で操作<c>id、displayName</c>、し、各<see cref="T:Microsoft.Azure.Batch.CloudPool" />がその<see cref="P:Microsoft.Azure.Batch.CloudPool.Id" />と<see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" />が作成されますが、プロパティ、などその他のプロパティ<see cref="P:Microsoft.Azure.Batch.CloudPool.State" />は取得されませんし、その結果、既定値 (通常 null) が与えられます。</span><span class="sxs-lookup"><span data-stu-id="c9a79-137">For example, if you perform a <see cref="M:Microsoft.Azure.Batch.PoolOperations.ListPools(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> operation with a SelectClause of <c>id,displayName</c>, then each <see cref="T:Microsoft.Azure.Batch.CloudPool" /> will have its <see cref="P:Microsoft.Azure.Batch.CloudPool.Id" /> and <see cref="P:Microsoft.Azure.Batch.CloudPool.DisplayName" /> properties populated, but other properties such as <see cref="P:Microsoft.Azure.Batch.CloudPool.State" /> will not be retrieved and therefore will have their default values (typically null).</span></span></para>
          <para><span data-ttu-id="c9a79-138">含まれていませんまたは複数のプロパティを一意になる SelectClause を指定したオブジェクトの識別、ときに、エンティティが取得された場合は (一覧を取得または更新) 経由で (通常、Id プロパティが、<see cref="T:Microsoft.Azure.Batch.Certificate" />サムプリントと ThumbprintAlgorithm次に データの取得や操作を実行するバッチ サービスにアクセスするすべてのメソッドは失敗します。</span><span class="sxs-lookup"><span data-stu-id="c9a79-138">If, when an entity was retrieved (via a List, Get or Refresh), you specifed a SelectClause which did not include the property or properties that uniquely identify the object (usually the Id property, but for <see cref="T:Microsoft.Azure.Batch.Certificate" /> the Thumbprint and ThumbprintAlgorithm properties, then any methods that access the Batch service to retrieve data or perform operations will fail.</span></span>
            <span data-ttu-id="c9a79-139">これには、オブジェクトのほとんどのメソッドが含まれますなど<see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />と<see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="c9a79-139">This includes most methods on the object, including <see cref="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" /> and <see cref="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span>
            <span data-ttu-id="c9a79-140">(ただし、SelectClause に含まれているプロパティのみが設定されます) プロパティにアクセスすることができます。</span><span class="sxs-lookup"><span data-stu-id="c9a79-140">You can still access properties (though only properties included in the SelectClause will be populated).</span></span></para>
          <para><span data-ttu-id="c9a79-141">選択内容は、REST API の属性名、.NET プロパティ名ではなくを使用して指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c9a79-141">Selections must be specified using REST API attribute names, not .NET property names.</span></span></para>
          <para><span data-ttu-id="c9a79-142">既定値には、select 式は、すべてのプロパティが返されることを意味はありません。</span><span class="sxs-lookup"><span data-stu-id="c9a79-142">The default is no select expression, which means all properties are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>