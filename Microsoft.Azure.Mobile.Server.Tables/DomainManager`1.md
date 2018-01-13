<Type Name="DomainManager&lt;TData&gt;" FullName="Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;TData&gt;">
  <TypeSignature Language="C#" Value="public abstract class DomainManager&lt;TData&gt; : Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt; where TData : class, ITableData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit DomainManager`1&lt;class (class Microsoft.Azure.Mobile.Server.Tables.ITableData) TData&gt; extends System.Object implements class Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1&lt;!TData&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class DomainManager(Of TData)&#xA;Implements IDomainManager(Of TData)" />
  <TypeSignature Language="F#" Value="type DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt; = class&#xA;    interface IDomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; ITableData)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TData">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.ITableData</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Tables.IDomainManager&lt;TData&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TData"><span data-ttu-id="3b2b3-101">データ オブジェクト (DTO) を入力します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-101">The data object (DTO) type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="3b2b3-102">提供のバックエンド ストアにアクセスするための抽象、<see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-102">Provides an abstraction for accessing a backend store for a <see cref="T:Microsoft.Azure.Mobile.Server.TableController`1" />.</span></span>
            <span data-ttu-id="3b2b3-103">抽象型は、バックエンド ストアの能力に応じて、2 つの方法のいずれかで実装できます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-103">The abstraction can be implemented in one of two ways depending on the capabilities of the backend store.</span></span> <span data-ttu-id="3b2b3-104">格納をサポートする、 <see cref="T:System.Linq.IQueryable`1" />-ベースのモデルを実装できます、<see cref="M:Query" />と<see cref="M:Lookup" />メソッドをサポートしていないストア<see cref="T:System.Linq.IQueryable" />直接またはここではそれらにアクセスする方法として推奨を実装できます、<see cref="M:QueryAsync" />と<see cref="M:LookupAsync" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-104">Stores that support a <see cref="T:System.Linq.IQueryable`1" />-based model can implement the <see cref="M:Query" /> and <see cref="M:Lookup" /> methods whereas stores that don't support <see cref="T:System.Linq.IQueryable" /> directly or where it is not the preferred way of accessing them can implement the <see cref="M:QueryAsync" /> and <see cref="M:LookupAsync" /> methods.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DomainManager (System.Net.Http.HttpRequestMessage request, bool enableSoftDelete);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpRequestMessage request, bool enableSoftDelete) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.#ctor(System.Net.Http.HttpRequestMessage,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (request As HttpRequestMessage, enableSoftDelete As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; : System.Net.Http.HttpRequestMessage * bool -&gt; Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="new Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; (request, enableSoftDelete)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="enableSoftDelete" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="request">
            <span data-ttu-id="3b2b3-105"><see cref="T:System.Net.Http.HttpRequestMessage" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-105">An instance of <see cref="T:System.Net.Http.HttpRequestMessage" /></span></span></param>
        <param name="enableSoftDelete">
            <span data-ttu-id="3b2b3-106">行を削除または削除済みとしてマークがハードかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-106">Determines whether rows are hard deleted or marked as deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b2b3-107">新しいインスタンスを作成します。<see cref="T:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1" /></span><span class="sxs-lookup"><span data-stu-id="3b2b3-107">Creates a new instance of <see cref="T:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;bool&gt; DeleteAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.DeleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function DeleteAsync (id As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="domainManager.DeleteAsync id" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.DeleteAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-108">削除する項目の id。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-108">The id of the item to delete.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-109">既存の項目を削除します</span><span class="sxs-lookup"><span data-stu-id="3b2b3-109">Deletes an existing item</span></span>
            </summary>
        <returns>
          <span data-ttu-id="3b2b3-110"><c>true</c>項目が削除されたそれ以外の場合<c>false</c></span><span class="sxs-lookup"><span data-stu-id="3b2b3-110"><c>true</c> if item was deleted; otherwise <c>false</c></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSoftDelete">
      <MemberSignature Language="C#" Value="public bool EnableSoftDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableSoftDelete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.EnableSoftDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSoftDelete As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableSoftDelete : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;.EnableSoftDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b2b3-111">行を削除または削除済みとしてマークがハードかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-111">Determines whether rows are hard deleted or marked as deleted.</span></span> <span data-ttu-id="3b2b3-112">既定では false です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-112">False by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeDeleted">
      <MemberSignature Language="C#" Value="public bool IncludeDeleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeDeleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.IncludeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeDeleted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeDeleted : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;.IncludeDeleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b2b3-113">ソフト削除されたレコードがクエリの結果に含めるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-113">Determines whether soft deleted records are included in query results.</span></span> <span data-ttu-id="3b2b3-114">既定では true です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-114">True by default.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;TData&gt; InsertAsync (TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; InsertAsync(!TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function InsertAsync (data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.InsertAsync data" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.InsertAsync(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="data"><span data-ttu-id="3b2b3-115">データを挿入します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-115">The data to be inserted</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-116">バックエンド ストアに項目を挿入します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-116">Inserts an item to the backend store.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-117">挿入されたアイテムです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-117">The inserted item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lookup">
      <MemberSignature Language="C#" Value="public abstract System.Web.Http.SingleResult&lt;TData&gt; Lookup (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Web.Http.SingleResult`1&lt;!TData&gt; Lookup(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.Lookup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Lookup (id As String) As SingleResult(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Lookup : string -&gt; System.Web.Http.SingleResult&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.Lookup id" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Lookup(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Web.Http.SingleResult&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-118">項目を表す id です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-118">The id representing the item.</span></span> <span data-ttu-id="3b2b3-119">一部として、id が指定される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />され、クライアントに表示されます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-119">The id is provided as part of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> and is visible to the client.</span></span>
            <span data-ttu-id="3b2b3-120">ただし、によっては、バックエンド ストアとドメイン モデルでは、特定の実装では、可能性があります id にマップの他の何らかの一意識別子。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-120">However, depending on the backend store and the domain model, the particular implementation may map the id to some other form of unique identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-121">ビルド、<see cref="T:System.Linq.IQueryable`1" />サポートするストアに対して実行される<see cref="T:System.Linq.IQueryable`1" />1 つの項目を検索するためです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-121">Builds an <see cref="T:System.Linq.IQueryable`1" /> to be executed against a store supporting <see cref="T:System.Linq.IQueryable`1" /> for looking up a single item.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-122">A<see cref="T:System.Web.Http.SingleResult`1" />を含む、<see cref="T:System.Linq.IQueryable`1" />がまだ実行されていません。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-122">A <see cref="T:System.Web.Http.SingleResult`1" /> containing the <see cref="T:System.Linq.IQueryable`1" /> which has not yet been executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="3b2b3-123">関連項目<see cref="M:Query" />コンパニオン メソッドを作成するためである、<see cref="T:System.Linq.IQueryable`1" />複数の項目を表すです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-123">See also <see cref="M:Query" /> which is the companion method for creating an <see cref="T:System.Linq.IQueryable`1" /> representing multiple items.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.SingleResult`1&lt;!TData&gt;&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function LookupAsync (id As String) As Task(Of SingleResult(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;'Data&gt;&gt;" Usage="domainManager.LookupAsync id" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.LookupAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.SingleResult&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-124">項目を表す id です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-124">The id representing the item.</span></span> <span data-ttu-id="3b2b3-125">一部として、id が指定される、<see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" />され、クライアントに表示されます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-125">The id is provided as part of the <see cref="T:Microsoft.Azure.Mobile.Server.Tables.ITableData" /> and is visible to the client.</span></span>
            <span data-ttu-id="3b2b3-126">ただし、によっては、バックエンド ストアとドメイン モデルでは、特定の実装では、可能性があります id にマップの他の何らかの一意識別子。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-126">However, depending on the backend store and the domain model, the particular implementation may map the id to some other form of unique identifier.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-127">バックエンド ストアの 1 つの項目を検索します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-127">Looks up a single item in the backend store.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-128">A<see cref="T:System.Web.Http.SingleResult`1" />検索の結果を表すです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-128">A <see cref="T:System.Web.Http.SingleResult`1" /> representing the result of the lookup.</span></span> <span data-ttu-id="3b2b3-129">A<see cref="T:System.Web.Http.SingleResult`1" />を表す、 <see cref="T:System.Linq.IQueryable" /> 0 個または 1 つのエンティティを含むです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-129">A <see cref="T:System.Web.Http.SingleResult`1" /> represents an <see cref="T:System.Linq.IQueryable" /> containing zero or one entities.</span></span> <span data-ttu-id="3b2b3-130">これにより、さらにクエリなどを実行するとで構成される<c>$select</c>です。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-130">This allows it to be composed with further querying such as <c>$select</c>.</span></span></returns>
        <remarks>
            <span data-ttu-id="3b2b3-131">関連項目<see cref="M:QueryAsync" />複数の項目のクエリを実行するコンパニオン メソッドであります。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-131">See also <see cref="M:QueryAsync" /> which is the companion method for executing a query for multiple items.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public abstract System.Linq.IQueryable&lt;TData&gt; Query ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Linq.IQueryable`1&lt;!TData&gt; Query() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Query () As IQueryable(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member Query : unit -&gt; System.Linq.IQueryable&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.Query " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.Query</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3b2b3-132">ビルド、<see cref="T:System.Linq.IQueryable`1" />サポートするストアに対して実行される<see cref="T:System.Linq.IQueryable`1" />データを照会するためです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-132">Builds an <see cref="T:System.Linq.IQueryable`1" /> to be executed against a store supporting <see cref="T:System.Linq.IQueryable`1" /> for querying data.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-133"><see cref="T:System.Linq.IQueryable`1" />がまだ実行されていません。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-133">An <see cref="T:System.Linq.IQueryable`1" /> which has not yet been executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="3b2b3-134">参照<see cref="M:Lookup" />コンパニオン メソッドを作成するためである、<see cref="T:System.Linq.IQueryable`1" />を表す 1 つの項目。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-134">See also <see cref="M:Lookup" /> which is the companion method for creating an <see cref="T:System.Linq.IQueryable`1" /> representing a single item.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt; QueryAsync (System.Web.Http.OData.Query.ODataQueryOptions query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!TData&gt;&gt; QueryAsync(class System.Web.Http.OData.Query.ODataQueryOptions query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function QueryAsync (query As ODataQueryOptions) As Task(Of IEnumerable(Of TData))" />
      <MemberSignature Language="F#" Value="abstract member QueryAsync : System.Web.Http.OData.Query.ODataQueryOptions -&gt; System.Threading.Tasks.Task&lt;seq&lt;'Data&gt;&gt;" Usage="domainManager.QueryAsync query" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.QueryAsync(System.Web.Http.OData.Query.ODataQueryOptions)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;TData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="System.Web.Http.OData.Query.ODataQueryOptions" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="3b2b3-135"><see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" />クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-135">The <see cref="T:System.Web.Http.OData.Query.ODataQueryOptions" /> query to execute.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-136">指定された実行<paramref name="query" />ストアに対してです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-136">Executes the provided <paramref name="query" /> against a store.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-137"><see cref="T:System.Collections.Generic.IEnumerable`1" />クエリの結果を表すです。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-137">An <see cref="T:System.Collections.Generic.IEnumerable`1" /> representing the result of the query.</span></span></returns>
        <remarks>
            <span data-ttu-id="3b2b3-138">関連項目<see cref="M:LookupAsync" />1 つの項目の参照を実行するためのコンパニオン メソッドであります。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-138">See also <see cref="M:LookupAsync" /> which is the companion method for executing a lookup for a single item.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;TData&gt; ReplaceAsync (string id, TData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; ReplaceAsync(string id, !TData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.ReplaceAsync(System.String,`0)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceAsync (id As String, data As TData) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceAsync : string * 'Data -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.ReplaceAsync (id, data)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.ReplaceAsync(System.String,`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="data" Type="TData" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-139">置換する項目の id。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-139">The id of the item to replace.</span></span></param>
        <param name="data"><span data-ttu-id="3b2b3-140">置換</span><span class="sxs-lookup"><span data-stu-id="3b2b3-140">The replacement</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-141">既存の項目を完全に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-141">Completely replaces an existing item.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-142">置き換えられる項目</span><span class="sxs-lookup"><span data-stu-id="3b2b3-142">The replaced item</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Request">
      <MemberSignature Language="C#" Value="public System.Net.Http.HttpRequestMessage Request { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Net.Http.HttpRequestMessage Request" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.Request" />
      <MemberSignature Language="VB.NET" Value="Public Property Request As HttpRequestMessage" />
      <MemberSignature Language="F#" Value="member this.Request : System.Net.Http.HttpRequestMessage with get, set" Usage="Microsoft.Azure.Mobile.Server.Tables.DomainManager&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;.Request" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpRequestMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3b2b3-143">インスタンス<see cref="T:System.Net.Http.HttpRequestMessage" /></span><span class="sxs-lookup"><span data-stu-id="3b2b3-143">Instance of <see cref="T:System.Net.Http.HttpRequestMessage" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;TData&gt; UndeleteAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UndeleteAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.UndeleteAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UndeleteAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.UndeleteAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-144">削除を取り消す項目の id。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-144">The id of the item to undelete.</span></span></param>
        <param name="patch"><span data-ttu-id="3b2b3-145">適用する修正プログラム。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-145">The patch to apply.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-146">復元し、必要に応じて適用することにより、ソフト削除された項目を更新、<see cref="T:System.Web.Http.OData.Delta`1" />に修正プログラム。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-146">Undeletes and optionally updates a soft deleted item by applying a <see cref="T:System.Web.Http.OData.Delta`1" /> patch to it.</span></span> <span data-ttu-id="3b2b3-147"><see cref="T:System.Web.Http.OData.Delta`1" />抽象化を追跡するプロパティが変更された既定値と、同様の問題を回避できます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-147">The <see cref="T:System.Web.Http.OData.Delta`1" /> abstraction keeps track of which properties have changed which avoids problems with default values and the like.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-148">削除されない項目。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-148">The undeleted item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;TData&gt; UpdateAsync (string id, System.Web.Http.OData.Delta&lt;TData&gt; patch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TData&gt; UpdateAsync(string id, class System.Web.Http.OData.Delta`1&lt;!TData&gt; patch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Tables.DomainManager`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateAsync (id As String, patch As Delta(Of TData)) As Task(Of TData)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * System.Web.Http.OData.Delta&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt; -&gt; System.Threading.Tasks.Task&lt;'Data (requires 'Data : null and 'Data :&gt; Microsoft.Azure.Mobile.Server.Tables.ITableData)&gt;" Usage="domainManager.UpdateAsync (id, patch)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Tables.IDomainManager`1.UpdateAsync(System.String,System.Web.Http.OData.Delta{`0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Tables</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="patch" Type="System.Web.Http.OData.Delta&lt;TData&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="3b2b3-149">修正プログラムを項目の id。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-149">The id of the item to patch.</span></span></param>
        <param name="patch"><span data-ttu-id="3b2b3-150">適用する修正プログラム。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-150">The patch to apply.</span></span></param>
        <summary>
            <span data-ttu-id="3b2b3-151">適用することで既存の項目を更新、<see cref="T:System.Web.Http.OData.Delta`1" />に修正プログラム。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-151">Updates an existing item by applying a <see cref="T:System.Web.Http.OData.Delta`1" /> patch to it.</span></span> <span data-ttu-id="3b2b3-152"><see cref="T:System.Web.Http.OData.Delta`1" />抽象化を追跡するプロパティが変更された既定値と、同様の問題を回避できます。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-152">The <see cref="T:System.Web.Http.OData.Delta`1" /> abstraction keeps track of which properties have changed which avoids problems with default values and the like.</span></span>
            </summary>
        <returns><span data-ttu-id="3b2b3-153">パッチが適用された項目。</span><span class="sxs-lookup"><span data-stu-id="3b2b3-153">The patched item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>