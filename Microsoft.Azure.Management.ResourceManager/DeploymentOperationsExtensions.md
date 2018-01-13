<Type Name="DeploymentOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeploymentOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeploymentOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeploymentOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeploymentOperationsExtensions = class" />
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
            <span data-ttu-id="e0f59-101">DeploymentOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="e0f59-101">Extension methods for DeploymentOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation Get (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation Get(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDeploymentOperations, resourceGroupName As String, deploymentName As String, operationId As String) As DeploymentOperation" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.Get (operations, resourceGroupName, deploymentName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0f59-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-103">The name of the resource group.</span></span> <span data-ttu-id="e0f59-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-104">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="e0f59-105">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-105">The name of the deployment.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="e0f59-106">取得する操作の ID。</span><span class="sxs-lookup"><span data-stu-id="e0f59-106">The ID of the operation to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-107">展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-107">Gets a deployments operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.GetAsync (operations, resourceGroupName, deploymentName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0f59-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-109">The name of the resource group.</span></span> <span data-ttu-id="e0f59-110">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-110">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="e0f59-111">デプロイの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-111">The name of the deployment.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="e0f59-112">取得する操作の ID。</span><span class="sxs-lookup"><span data-stu-id="e0f59-112">The ID of the operation to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0f59-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e0f59-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-114">展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-114">Gets a deployments operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; List (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; List(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDeploymentOperations, resourceGroupName As String, deploymentName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of DeploymentOperation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.List (operations, resourceGroupName, deploymentName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0f59-116">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-116">The name of the resource group.</span></span> <span data-ttu-id="e0f59-117">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-117">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="e0f59-118">デプロイを取得する操作の名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-118">The name of the deployment with the operation to get.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="e0f59-119">返される結果の数。</span><span class="sxs-lookup"><span data-stu-id="e0f59-119">The number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-120">展開のすべての展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-120">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string resourceGroupName, string deploymentName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListAsync (operations, resourceGroupName, deploymentName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e0f59-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-122">The name of the resource group.</span></span> <span data-ttu-id="e0f59-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-123">The name is case insensitive.</span></span>
            </param>
        <param name="deploymentName">
            <span data-ttu-id="e0f59-124">デプロイを取得する操作の名前。</span><span class="sxs-lookup"><span data-stu-id="e0f59-124">The name of the deployment with the operation to get.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="e0f59-125">返される結果の数。</span><span class="sxs-lookup"><span data-stu-id="e0f59-125">The number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0f59-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e0f59-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-127">展開のすべての展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-127">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDeploymentOperations, nextPageLink As String) As IPage(Of DeploymentOperation)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-128">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e0f59-129">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e0f59-129">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-130">展開のすべての展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-130">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IDeploymentOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IDeploymentOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IDeploymentOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.DeploymentOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.DeploymentOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IDeploymentOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e0f59-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e0f59-131">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e0f59-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="e0f59-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e0f59-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e0f59-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e0f59-134">展開のすべての展開操作を取得します。</span><span class="sxs-lookup"><span data-stu-id="e0f59-134">Gets all deployments operations for a deployment.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>