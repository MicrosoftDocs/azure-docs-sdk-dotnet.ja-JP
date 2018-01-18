<Type Name="RouteFiltersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFiltersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFiltersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFiltersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFiltersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7ef09-101">RouteFiltersOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7ef09-101">Extension methods for RouteFiltersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As RouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-103">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-104">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-104">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-105">作成または更新のルート フィルター操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7ef09-105">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-106">作成するか、指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-106">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-108">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-109">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-109">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-110">作成または更新のルート フィルター操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7ef09-110">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-112">作成するか、指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-112">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDelete (operations, resourceGroupName, routeFilterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-114">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-115">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-115">The name of the route filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-116">指定したルート フィルターを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-116">Deletes the specified route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-118">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-119">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-119">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-121">指定したルート フィルターを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-121">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter BeginUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter BeginUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As PatchRouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-123">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-124">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-124">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-125">パラメーターは、更新プログラムのルート フィルターの操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-125">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-126">指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-126">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-128">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-129">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-129">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-130">パラメーターは、更新プログラムのルート フィルターの操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-130">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-132">指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-132">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter CreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter CreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As RouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-134">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-135">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-135">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-136">作成または更新のルート フィルター操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7ef09-136">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-137">作成するか、指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-137">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-139">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-140">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-140">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-141">作成または更新のルート フィルター操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7ef09-141">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-143">作成するか、指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-143">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Delete (operations, resourceGroupName, routeFilterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-145">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-146">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-146">The name of the route filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-147">指定したルート フィルターを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-147">Deletes the specified route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-149">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-150">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-150">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-152">指定したルート フィルターを削除します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-152">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter Get (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter Get(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Get(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, Optional expand As String = null) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Get (operations, resourceGroupName, routeFilterName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-154">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-155">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-155">The name of the route filter.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7ef09-156">参照先の express route bgp ピアリング リソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-156">Expands referenced express route bgp peering resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-157">指定したルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-157">Gets the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; GetAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; GetAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-159">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-160">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-160">The name of the route filter.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="7ef09-161">参照先の express route bgp ピアリング リソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-161">Expands referenced express route bgp peering resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-163">指定したルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-163">Gets the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; List (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; List(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.List(Microsoft.Azure.Management.Network.IRouteFiltersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRouteFiltersOperations) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IRouteFiltersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-164">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-165">サブスクリプションのすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-165">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-166">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-168">サブスクリプションのすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-168">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroup (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroup(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IRouteFiltersOperations, resourceGroupName As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-170">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-170">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-171">リソース グループ内のすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-171">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-173">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-175">リソース グループ内のすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-175">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IRouteFiltersOperations, nextPageLink As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-176">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ef09-177">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ef09-177">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-178">リソース グループ内のすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-178">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ef09-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ef09-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-182">リソース グループ内のすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-182">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListNext (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListNext(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRouteFiltersOperations, nextPageLink As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ef09-184">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ef09-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-185">サブスクリプションのすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-185">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7ef09-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7ef09-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-189">サブスクリプションのすべてのルート フィルターを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-189">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter Update (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter Update(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Update(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As PatchRouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Update (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-191">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-192">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-192">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-193">パラメーターは、更新プログラムのルート フィルターの操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-193">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-194">指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-194">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; UpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; UpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef09-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7ef09-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7ef09-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-196">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="7ef09-197">ルート フィルターの名前。</span><span class="sxs-lookup"><span data-stu-id="7ef09-197">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="7ef09-198">パラメーターは、更新プログラムのルート フィルターの操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-198">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7ef09-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7ef09-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef09-200">指定されたリソース グループ内のルート フィルターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7ef09-200">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>