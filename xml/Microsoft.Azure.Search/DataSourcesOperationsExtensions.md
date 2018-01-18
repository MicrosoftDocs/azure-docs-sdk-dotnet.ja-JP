<Type Name="DataSourcesOperationsExtensions" FullName="Microsoft.Azure.Search.DataSourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.DataSourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourcesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="446f6-101">データ ソースを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="446f6-101">Operations for managing datasources.</span></span> 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Indexer-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource Create (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource Create(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Create(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Create (operations, dataSource, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-103">作成するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-103">The definition of the datasource to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-105">新しい Azure Search データソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="446f6-105">Creates a new Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateAsync (operations, dataSource, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-106">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-107">作成するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-107">The definition of the datasource to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-108">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-110">新しい Azure Search データソースを作成します。</span><span class="sxs-lookup"><span data-stu-id="446f6-110">Creates a new Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate (operations, dataSource, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-111">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-112">作成または更新するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-112">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-113">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-113">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-114">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-114">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-115">新しい Azure Search データソースを作成または、既に存在する場合、データ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="446f6-115">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate (operations, dataSourceName, dataSource, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-116">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-117">作成または更新するデータソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="446f6-117">The name of the datasource to create or update.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-118">作成または更新するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-118">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-119">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-120">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-120">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-121">新しい Azure Search データソースを作成または、既に存在する場合、データ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="446f6-121">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, dataSource, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-122">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-123">作成または更新するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-123">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-124">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-124">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-125">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-127">新しい Azure Search データソースを作成または、既に存在する場合、データ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="446f6-127">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, dataSourceName, dataSource, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-128">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-129">作成または更新するデータソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="446f6-129">The name of the datasource to create or update.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="446f6-130">作成または更新するデータソースの定義。</span><span class="sxs-lookup"><span data-stu-id="446f6-130">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-131">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-131">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-132">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-132">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-134">新しい Azure Search データソースを作成または、既に存在する場合、データ ソースを更新します。</span><span class="sxs-lookup"><span data-stu-id="446f6-134">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Delete(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Delete (operations, dataSourceName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-135">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-136">削除するデータソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-136">The name of the datasource to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-137">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-137">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-138">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-138">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-139">Azure Search データソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="446f6-139">Deletes an Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Data-Source" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.DeleteAsync (operations, dataSourceName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-140">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-141">削除するデータソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-141">The name of the datasource to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-142">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="446f6-143">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-143">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-145">Azure Search データソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="446f6-145">Deletes an Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Exists(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Exists (operations, dataSourceName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-146">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-147">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-147">The name of the data source.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-148">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-149">Azure Search サービスで、指定されたデータ ソースが存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="446f6-149">Determines whether or not the given data source exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="446f6-150"><c>true</c>データ ソースが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="446f6-150"><c>true</c> if the data source exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.ExistsAsync (operations, dataSourceName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-151">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-152">データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-152">The name of the data source.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-153">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-153">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-155">Azure Search サービスで、指定されたデータ ソースが存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="446f6-155">Determines whether or not the given data source exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="446f6-156"><c>true</c>データ ソースが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="446f6-156"><c>true</c> if the data source exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource Get (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource Get(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Get(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Get (operations, dataSourceName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-157">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-158">取得するデータソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-158">The name of the datasource to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-159">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-160">Azure Search からデータソース定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="446f6-160">Retrieves a datasource definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; GetAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; GetAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.GetAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.GetAsync (operations, dataSourceName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-161">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="446f6-162">取得するデータソースの名前。</span><span class="sxs-lookup"><span data-stu-id="446f6-162">The name of the datasource to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-163">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-163">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-165">Azure Search からデータソース定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="446f6-165">Retrieves a datasource definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSourceListResult List (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSourceListResult List(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.List(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSourceListResult" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-166">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-167">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-168">Azure Search サービスの使用可能なすべてのデータ ソースを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="446f6-168">Lists all datasources available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Data-Sources" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt; ListAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSourceListResult&gt; ListAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.ListAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="446f6-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="446f6-169">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="446f6-170">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="446f6-170">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="446f6-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="446f6-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="446f6-172">Azure Search サービスの使用可能なすべてのデータ ソースを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="446f6-172">Lists all datasources available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Data-Sources" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>