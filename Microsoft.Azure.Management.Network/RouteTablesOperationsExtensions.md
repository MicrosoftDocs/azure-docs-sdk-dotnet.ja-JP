<Type Name="RouteTablesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteTablesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteTablesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteTablesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteTablesOperationsExtensions = class" />
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
            <span data-ttu-id="1c391-101">RouteTablesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1c391-101">Extension methods for RouteTablesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteTable BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.RouteTable parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteTable BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.RouteTable parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteTable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String, parameters As RouteTable) As RouteTable" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteTable -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, routeTableName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.RouteTable" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-103">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-104">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-104">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-105">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-105">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-106">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="1c391-106">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.RouteTable parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.RouteTable parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteTable,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteTable * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.RouteTable" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-108">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-109">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-109">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-110">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-110">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-112">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="1c391-112">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginDelete (operations, resourceGroupName, routeTableName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-114">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-115">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-115">The name of the route table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-116">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c391-116">Deletes the specified route table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-118">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-119">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-119">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-121">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c391-121">Deletes the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteTable BeginUpdateTags (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteTable BeginUpdateTags(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String, parameters As TagsObject) As RouteTable" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, routeTableName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-123">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-124">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-124">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-125">ルート テーブルのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-125">Parameters supplied to update route table tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-126">ルート テーブルのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c391-126">Updates a route table tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-128">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-129">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-129">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-130">ルート テーブルのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-130">Parameters supplied to update route table tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-132">ルート テーブルのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c391-132">Updates a route table tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteTable CreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.RouteTable parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteTable CreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.RouteTable parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteTable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String, parameters As RouteTable) As RouteTable" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteTable -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, routeTableName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.RouteTable" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-134">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-135">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-135">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-136">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-136">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-137">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="1c391-137">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.RouteTable parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.RouteTable parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteTable,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteTable * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.RouteTable" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-139">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-140">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-140">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-141">作成または更新のルート テーブル操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-141">Parameters supplied to the create or update route table operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-143">作成するか、指定されたリソース グループ内のテーブルを更新するルート。</span><span class="sxs-lookup"><span data-stu-id="1c391-143">Create or updates a route table in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.Delete (operations, resourceGroupName, routeTableName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-145">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-145">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-146">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-146">The name of the route table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-147">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c391-147">Deletes the specified route table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-149">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-150">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-150">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-152">指定したルート テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="1c391-152">Deletes the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteTable Get (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteTable Get(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String, Optional expand As String = null) As RouteTable" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.Get (operations, resourceGroupName, routeTableName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-154">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-155">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-155">The name of the route table.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="1c391-156">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="1c391-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-157">指定したルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-157">Gets the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; GetAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; GetAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.GetAsync (operations, resourceGroupName, routeTableName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-159">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-160">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-160">The name of the route table.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="1c391-161">参照されているリソースを展開します。</span><span class="sxs-lookup"><span data-stu-id="1c391-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-163">指定したルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-163">Gets the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; List (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; List(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.List(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRouteTablesOperations, resourceGroupName As String) As IPage(Of RouteTable)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IRouteTablesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-165">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-166">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-166">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListAll (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListAll(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IRouteTablesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IRouteTablesOperations) As IPage(Of RouteTable)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IRouteTablesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-167">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-168">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-168">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;ListAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-169">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-171">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-171">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListAllNext (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListAllNext(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IRouteTablesOperations, nextPageLink As String) As IPage(Of RouteTable)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IRouteTablesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c391-173">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1c391-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-174">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-174">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;ListAllNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c391-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1c391-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-178">サブスクリプションのすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-178">Gets all route tables in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;ListAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-180">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-180">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-182">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-182">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListNext (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; ListNext(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRouteTablesOperations, nextPageLink As String) As IPage(Of RouteTable)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IRouteTablesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c391-184">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1c391-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-185">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-185">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1c391-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1c391-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-189">リソース グループ内のすべてのルート テーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="1c391-189">Gets all route tables in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteTable UpdateTags (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteTable UpdateTags(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IRouteTablesOperations, resourceGroupName As String, routeTableName As String, parameters As TagsObject) As RouteTable" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.RouteTable" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.UpdateTags (operations, resourceGroupName, routeTableName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-191">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-192">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-192">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-193">ルート テーブルのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-193">Parameters supplied to update route table tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-194">ルート テーブルのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c391-194">Updates a route table tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteTable&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IRouteTablesOperations operations, string resourceGroupName, string routeTableName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IRouteTablesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IRouteTablesOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;" Usage="Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, routeTableName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteTablesOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteTablesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1c391-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1c391-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1c391-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1c391-196">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="1c391-197">ルート テーブルの名前です。</span><span class="sxs-lookup"><span data-stu-id="1c391-197">The name of the route table.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1c391-198">ルート テーブルのタグを更新する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="1c391-198">Parameters supplied to update route table tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c391-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1c391-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c391-200">ルート テーブルのタグを更新します。</span><span class="sxs-lookup"><span data-stu-id="1c391-200">Updates a route table tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>