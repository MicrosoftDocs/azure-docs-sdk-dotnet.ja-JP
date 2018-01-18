<Type Name="ProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d2548-101">ProvidersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="d2548-101">Extension methods for ProvidersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Get (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Get(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProvidersOperations, resourceProviderNamespace As String, Optional expand As String = null) As Provider" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Get (operations, resourceProviderNamespace, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-103">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="d2548-103">The namespace of the resource provider.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d2548-104">$ は、クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="d2548-104">The $expand query parameter.</span></span> <span data-ttu-id="d2548-105">たとえば、応答には、プロパティのエイリアスを含める、使用 $展開のリソースの種類/エイリアスを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-105">For example, to include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-106">指定したリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-106">Gets the specified resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.GetAsync (operations, resourceProviderNamespace, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-108">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="d2548-108">The namespace of the resource provider.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d2548-109">$ は、クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="d2548-109">The $expand query parameter.</span></span> <span data-ttu-id="d2548-110">たとえば、応答には、プロパティのエイリアスを含める、使用 $展開のリソースの種類/エイリアスを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-110">For example, to include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2548-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2548-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-112">指定したリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-112">Gets the specified resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; List (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; List(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IProvidersOperations, Optional top As Nullable(Of Integer) = null, Optional expand As String = null) As IPage(Of Provider)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.List (operations, top, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-113">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="d2548-114">返される結果の数。</span><span class="sxs-lookup"><span data-stu-id="d2548-114">The number of results to return.</span></span> <span data-ttu-id="d2548-115">Null が渡される場合は、すべての展開を返します。</span><span class="sxs-lookup"><span data-stu-id="d2548-115">If null is passed returns all deployments.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d2548-116">結果に含めるプロパティです。</span><span class="sxs-lookup"><span data-stu-id="d2548-116">The properties to include in the results.</span></span> <span data-ttu-id="d2548-117">たとえば、使用して&amp;$展開をリソース プロバイダーのメタデータを取得するクエリ文字列内のメタデータを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-117">For example, use &amp;$expand=metadata in the query string to retrieve resource provider metadata.</span></span> <span data-ttu-id="d2548-118">応答には、プロパティのエイリアスを含める、使用 $ 順に展開のリソースの種類/エイリアスを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-118">To include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-119">サブスクリプションのすべてのリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-119">Gets all resource providers for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListAsync (operations, top, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-120">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="d2548-121">返される結果の数。</span><span class="sxs-lookup"><span data-stu-id="d2548-121">The number of results to return.</span></span> <span data-ttu-id="d2548-122">Null が渡される場合は、すべての展開を返します。</span><span class="sxs-lookup"><span data-stu-id="d2548-122">If null is passed returns all deployments.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d2548-123">結果に含めるプロパティです。</span><span class="sxs-lookup"><span data-stu-id="d2548-123">The properties to include in the results.</span></span> <span data-ttu-id="d2548-124">たとえば、使用して&amp;$展開をリソース プロバイダーのメタデータを取得するクエリ文字列内のメタデータを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-124">For example, use &amp;$expand=metadata in the query string to retrieve resource provider metadata.</span></span> <span data-ttu-id="d2548-125">応答には、プロパティのエイリアスを含める、使用 $ 順に展開のリソースの種類/エイリアスを = です。</span><span class="sxs-lookup"><span data-stu-id="d2548-125">To include property aliases in response, use $expand=resourceTypes/aliases.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2548-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2548-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-127">サブスクリプションのすべてのリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-127">Gets all resource providers for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IProvidersOperations, nextPageLink As String) As IPage(Of Provider)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-128">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d2548-129">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d2548-129">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-130">サブスクリプションのすべてのリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-130">Gets all resource providers for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-131">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d2548-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d2548-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2548-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2548-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-134">サブスクリプションのすべてのリソース プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="d2548-134">Gets all resource providers for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Register (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Register(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Register(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Register (operations As IProvidersOperations, resourceProviderNamespace As String) As Provider" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Register (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-136">リソース プロバイダーの登録の名前空間。</span><span class="sxs-lookup"><span data-stu-id="d2548-136">The namespace of the resource provider to register.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-137">リソース プロバイダーにサブスクリプションを登録します。</span><span class="sxs-lookup"><span data-stu-id="d2548-137">Registers a subscription with a resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;RegisterAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-139">リソース プロバイダーの登録の名前空間。</span><span class="sxs-lookup"><span data-stu-id="d2548-139">The namespace of the resource provider to register.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2548-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2548-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-141">リソース プロバイダーにサブスクリプションを登録します。</span><span class="sxs-lookup"><span data-stu-id="d2548-141">Registers a subscription with a resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unregister">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Unregister (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Unregister(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Unregister(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Unregister (operations As IProvidersOperations, resourceProviderNamespace As String) As Provider" />
      <MemberSignature Language="F#" Value="static member Unregister : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Unregister (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-143">登録を解除するリソース プロバイダーの名前空間。</span><span class="sxs-lookup"><span data-stu-id="d2548-143">The namespace of the resource provider to unregister.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-144">リソース プロバイダーからサブスクリプションを登録解除します。</span><span class="sxs-lookup"><span data-stu-id="d2548-144">Unregisters a subscription from a resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; UnregisterAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; UnregisterAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.UnregisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;UnregisterAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d2548-145">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d2548-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="d2548-146">登録を解除するリソース プロバイダーの名前空間。</span><span class="sxs-lookup"><span data-stu-id="d2548-146">The namespace of the resource provider to unregister.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d2548-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d2548-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d2548-148">リソース プロバイダーからサブスクリプションを登録解除します。</span><span class="sxs-lookup"><span data-stu-id="d2548-148">Unregisters a subscription from a resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>