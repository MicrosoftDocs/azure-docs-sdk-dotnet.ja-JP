<Type Name="RouteTablesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteTablesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteTablesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteTablesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteTablesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3e8ec-101">RouteTablesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-101">Extension methods for RouteTablesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-103">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="3e8ec-104">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-104">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3e8ec-105">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-105">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-107">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-107">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-109">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="3e8ec-110">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-110">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-112">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-112">Deletes the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-114">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="3e8ec-115">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-115">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3e8ec-116">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-116">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-118">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-118">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-120">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="3e8ec-121">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-121">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-123">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-123">Deletes the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.GetAsync (operations, resourceGroupName, routeTableName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-125">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="3e8ec-126">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-126">The name of the route table.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3e8ec-127">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-127">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-129">指定したルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-129">Gets the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;ListAllAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-130">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-132">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-132">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;ListAllNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-133">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3e8ec-134">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-134">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-136">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-136">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3e8ec-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-138">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-140">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-140">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteTablesOperationsExtensions/&lt;ListNextAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteTableInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3e8ec-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-141">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3e8ec-142">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-142">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3e8ec-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3e8ec-144">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="3e8ec-144">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>