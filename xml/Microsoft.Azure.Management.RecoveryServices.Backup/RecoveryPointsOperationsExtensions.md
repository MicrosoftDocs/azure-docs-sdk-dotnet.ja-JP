<Type Name="RecoveryPointsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecoveryPointsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecoveryPointsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecoveryPointsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bd7fb-101">RecoveryPointsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-101">Extension methods for RecoveryPointsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRecoveryPointsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, recoveryPointId As String) As RecoveryPointResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd7fb-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd7fb-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="bd7fb-105">関連付けられているファブリック名は、項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-105">Fabric name associated with backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="bd7fb-106">関連付けられたコンテナー名は、項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-106">Container name associated with backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="bd7fb-107">項目の名前を取得する必要があるバックアップ データをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-107">Backed up item name whose backup data needs to be fetched.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="bd7fb-108">RecoveryPointID は、取得するデータをバックアップ対象を表します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-108">RecoveryPointID represents the backed up data to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-109">バックアップされたデータを RecoveryPointID を使用して特定の情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-109">Provides the information of the backed up data identified using RecoveryPointID.</span></span> <span data-ttu-id="bd7fb-110">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-110">This is an asynchronous operation.</span></span> <span data-ttu-id="bd7fb-111">操作の状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-111">To know the status of the operation, call the GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string recoveryPointId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, recoveryPointId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd7fb-113">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd7fb-114">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="bd7fb-115">関連付けられているファブリック名は、項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-115">Fabric name associated with backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="bd7fb-116">関連付けられたコンテナー名は、項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-116">Container name associated with backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="bd7fb-117">項目の名前を取得する必要があるバックアップ データをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-117">Backed up item name whose backup data needs to be fetched.</span></span>
            </param>
        <param name="recoveryPointId">
            <span data-ttu-id="bd7fb-118">RecoveryPointID は、取得するデータをバックアップ対象を表します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-118">RecoveryPointID represents the backed up data to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bd7fb-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-120">バックアップされたデータを RecoveryPointID を使用して特定の情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-120">Provides the information of the backed up data identified using RecoveryPointID.</span></span> <span data-ttu-id="bd7fb-121">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-121">This is an asynchronous operation.</span></span> <span data-ttu-id="bd7fb-122">操作の状態を確認するには、GetProtectedItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-122">To know the status of the operation, call the GetProtectedItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; List (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; List(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.List(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRecoveryPointsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, Optional odataQuery As ODataQuery(Of BMSRPQueryObject) = null) As IPage(Of RecoveryPointResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.List (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-123">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd7fb-124">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd7fb-125">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-125">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="bd7fb-126">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-126">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="bd7fb-127">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-127">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="bd7fb-128">フェッチするアイテムのバックアップ コピーをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-128">Backed up item whose backup copies are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bd7fb-129">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-129">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-130">バックアップ項目のバックアップ コピーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-130">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.BMSRPQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-131">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="bd7fb-132">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-132">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bd7fb-133">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-133">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="bd7fb-134">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-134">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="bd7fb-135">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-135">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="bd7fb-136">フェッチするアイテムのバックアップ コピーをバックアップします。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-136">Backed up item whose backup copies are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bd7fb-137">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-137">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bd7fb-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-139">バックアップ項目のバックアップ コピーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-139">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; ListNext (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt; ListNext(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNext(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRecoveryPointsOperations, nextPageLink As String) As IPage(Of RecoveryPointResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-140">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bd7fb-141">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-141">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-142">バックアップ項目のバックアップ コピーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-142">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.RecoveryPointsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.RecoveryPointResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IRecoveryPointsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bd7fb-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bd7fb-144">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bd7fb-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bd7fb-146">バックアップ項目のバックアップ コピーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="bd7fb-146">Lists the backup copies for the backed up item.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>