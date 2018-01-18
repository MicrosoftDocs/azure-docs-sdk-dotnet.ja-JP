<Type Name="ManagementGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagementGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagementGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagementGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="3e77a-101">ManagementGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3e77a-101">Extension methods for ManagementGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy Get (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand = null, Nullable&lt;bool&gt; recurse = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy Get(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand, valuetype System.Nullable`1&lt;bool&gt; recurse) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IManagementGroupsOperations, Optional expand As String = null, Optional recurse As Nullable(Of Boolean) = null) As ManagementGroupWithHierarchy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.Get (operations, expand, recurse)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-102">The operations group for this extension method.</span></span>
             </param>
        <param name="expand">
             <span data-ttu-id="3e77a-103">$展開クエリ文字列パラメーターにより、応答のペイロード内の子を含めることを要求するクライアントの子を = です。</span><span class="sxs-lookup"><span data-stu-id="3e77a-103">The $expand=children query string parameter allows clients to request inclusion of children in the response payload.</span></span> <span data-ttu-id="3e77a-104">使用可能な値が含まれます: '子'</span><span class="sxs-lookup"><span data-stu-id="3e77a-104">Possible values include: 'children'</span></span>
             </param>
        <param name="recurse">
             <span data-ttu-id="3e77a-105">$Recurse = true のクエリ文字列パラメーターを使用してクライアントを応答ペイロードの階層全体を含めることを要求します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-105">The $recurse=true query string parameter allows clients to request inclusion of entire hierarchy in the response payload.</span></span>
             </param>
        <summary>
             <span data-ttu-id="3e77a-106">管理グループの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-106">Get the details of the management group.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand = null, Nullable&lt;bool&gt; recurse = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string expand, valuetype System.Nullable`1&lt;bool&gt; recurse, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.GetAsync (operations, expand, recurse, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupWithHierarchy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="recurse" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-107">The operations group for this extension method.</span></span>
             </param>
        <param name="expand">
             <span data-ttu-id="3e77a-108">$展開クエリ文字列パラメーターにより、応答のペイロード内の子を含めることを要求するクライアントの子を = です。</span><span class="sxs-lookup"><span data-stu-id="3e77a-108">The $expand=children query string parameter allows clients to request inclusion of children in the response payload.</span></span> <span data-ttu-id="3e77a-109">使用可能な値が含まれます: '子'</span><span class="sxs-lookup"><span data-stu-id="3e77a-109">Possible values include: 'children'</span></span>
             </param>
        <param name="recurse">
             <span data-ttu-id="3e77a-110">$Recurse = true のクエリ文字列パラメーターを使用してクライアントを応答ペイロードの階層全体を含めることを要求します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-110">The $recurse=true query string parameter allows clients to request inclusion of entire hierarchy in the response payload.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="3e77a-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e77a-111">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="3e77a-112">管理グループの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-112">Get the details of the management group.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; List (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; List(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IManagementGroupsOperations, Optional skiptoken As String = null) As IPage(Of ManagementGroupInfo)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.List (operations, skiptoken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="skiptoken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-113">The operations group for this extension method.</span></span>
             </param>
        <param name="skiptoken">
             <span data-ttu-id="3e77a-114">ページ継続トークンは、前の操作には、部分的な結果が返された場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-114">Page continuation token is only used if a previous operation returned a partial result.</span></span>
             <span data-ttu-id="3e77a-115">前の応答には、nextLink 要素が含まれています、nextLink 要素の値により、後続の呼び出しに使用する開始位置を指定するトークンのパラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3e77a-115">If a previous response contains a nextLink element, the value of the nextLink element will include a token parameter that specifies a starting point to use for subsequent calls.</span></span>
             
             </param>
        <summary>
             <span data-ttu-id="3e77a-116">認証されたユーザーの管理グループを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-116">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string skiptoken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListAsync (operations, skiptoken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-117">The operations group for this extension method.</span></span>
             </param>
        <param name="skiptoken">
             <span data-ttu-id="3e77a-118">ページ継続トークンは、前の操作には、部分的な結果が返された場合にのみ使用します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-118">Page continuation token is only used if a previous operation returned a partial result.</span></span>
             <span data-ttu-id="3e77a-119">前の応答には、nextLink 要素が含まれています、nextLink 要素の値により、後続の呼び出しに使用する開始位置を指定するトークンのパラメーターが含まれます。</span><span class="sxs-lookup"><span data-stu-id="3e77a-119">If a previous response contains a nextLink element, the value of the nextLink element will include a token parameter that specifies a starting point to use for subsequent calls.</span></span>
             
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="3e77a-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e77a-120">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="3e77a-121">認証されたユーザーの管理グループを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-121">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IManagementGroupsOperations, nextPageLink As String) As IPage(Of ManagementGroupInfo)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-122">The operations group for this extension method.</span></span>
             </param>
        <param name="nextPageLink">
             <span data-ttu-id="3e77a-123">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3e77a-123">The NextLink from the previous successful call to List operation.</span></span>
             </param>
        <summary>
             <span data-ttu-id="3e77a-124">認証されたユーザーの管理グループを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-124">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementGroupInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
             <span data-ttu-id="3e77a-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e77a-125">The operations group for this extension method.</span></span>
             </param>
        <param name="nextPageLink">
             <span data-ttu-id="3e77a-126">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3e77a-126">The NextLink from the previous successful call to List operation.</span></span>
             </param>
        <param name="cancellationToken">
             <span data-ttu-id="3e77a-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e77a-127">The cancellation token.</span></span>
             </param>
        <summary>
             <span data-ttu-id="3e77a-128">認証されたユーザーの管理グループを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="3e77a-128">List management groups for the authenticated user.</span></span>
            
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>