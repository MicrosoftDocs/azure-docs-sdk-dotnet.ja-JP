<Type Name="RoutesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RoutesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RoutesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RoutesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RoutesOperationsExtensions = class" />
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
            <span data-ttu-id="b5d04-101">RoutesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b5d04-101">Extension methods for RoutesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeTableName, routeName, routeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="routeParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-103">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-104">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-104">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="b5d04-105">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-105">The name of the route.</span></span>
            </param>
        <param name="routeParameters">
            <span data-ttu-id="b5d04-106">作成または更新プログラムのルートの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b5d04-106">Parameters supplied to the create or update route operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-108">作成するか、指定したルート テーブル内のルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-108">Creates or updates a route in the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-110">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-111">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-111">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="b5d04-112">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-112">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-114">ルート テーブルから、指定されたルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-114">Deletes the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeTableName, routeName, routeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="routeParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-116">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-117">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-117">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="b5d04-118">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-118">The name of the route.</span></span>
            </param>
        <param name="routeParameters">
            <span data-ttu-id="b5d04-119">作成または更新プログラムのルートの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b5d04-119">Parameters supplied to the create or update route operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-121">作成するか、指定したルート テーブル内のルートを更新します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-121">Creates or updates a route in the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-123">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-124">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-124">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="b5d04-125">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-125">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-127">ルート テーブルから、指定されたルートを削除します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-127">Deletes the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.GetAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-129">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-130">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-130">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="b5d04-131">ルートの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-131">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-133">ルート テーブルから、指定されたルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-133">Gets the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b5d04-135">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5d04-135">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="b5d04-136">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-136">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-138">ルート テーブル内のすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-138">Gets all routes in a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b5d04-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b5d04-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="b5d04-140">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b5d04-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5d04-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5d04-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5d04-142">ルート テーブル内のすべてのルートを取得します。</span><span class="sxs-lookup"><span data-stu-id="b5d04-142">Gets all routes in a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>