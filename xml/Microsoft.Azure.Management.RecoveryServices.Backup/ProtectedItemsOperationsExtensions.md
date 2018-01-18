<Type Name="ProtectedItemsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectedItemsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectedItemsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectedItemsOperationsExtensions = class" />
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
            <span data-ttu-id="76f52-101">ProtectedItemsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="76f52-101">Extension methods for ProtectedItemsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static void CreateOrUpdate (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateOrUpdate(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateOrUpdate (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, parameters As ProtectedItemResource)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdate (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-104">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-105">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-105">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-106">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-106">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-107">バックアップする項目の名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-107">Item name to be backed up.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f52-108">リソース アイテムのバックアップ</span><span class="sxs-lookup"><span data-stu-id="76f52-108">resource backed up item</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-109">項目のバックアップを有効またはに既にバックアップ項目のバックアップ ポリシー情報を変更します。</span><span class="sxs-lookup"><span data-stu-id="76f52-109">Enables backup of an item or to modifies the backup policy information of an already backed up item.</span></span> <span data-ttu-id="76f52-110">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-110">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-111">操作の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-111">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateOrUpdateAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateOrUpdateAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.CreateOrUpdateAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-112">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-113">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-113">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-114">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-114">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-115">バックアップ項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-115">Fabric name associated with the backup item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-116">バックアップ アイテムに関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-116">Container name associated with the backup item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-117">バックアップする項目の名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-117">Item name to be backed up.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f52-118">リソース アイテムのバックアップ</span><span class="sxs-lookup"><span data-stu-id="76f52-118">resource backed up item</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76f52-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76f52-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-120">項目のバックアップを有効またはに既にバックアップ項目のバックアップ ポリシー情報を変更します。</span><span class="sxs-lookup"><span data-stu-id="76f52-120">Enables backup of an item or to modifies the backup policy information of an already backed up item.</span></span> <span data-ttu-id="76f52-121">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-121">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-122">操作の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-122">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Delete (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-123">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-124">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-125">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-125">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-126">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-126">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-127">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-127">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-128">削除する項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="76f52-128">Backed up item to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-129">コンテナー内の項目のバックアップを無効にするために使用します。</span><span class="sxs-lookup"><span data-stu-id="76f52-129">Used to disable backup of an item within a container.</span></span> <span data-ttu-id="76f52-130">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-130">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-131">要求の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-131">To know the status of the request, call the GetItemOperationResult API.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.DeleteAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-132">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-133">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-133">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-134">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-134">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-135">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-135">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-136">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-136">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-137">削除する項目をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="76f52-137">Backed up item to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76f52-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76f52-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-139">コンテナー内の項目のバックアップを無効にするために使用します。</span><span class="sxs-lookup"><span data-stu-id="76f52-139">Used to disable backup of an item within a container.</span></span> <span data-ttu-id="76f52-140">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-140">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-141">要求の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-141">To know the status of the request, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectedItemsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, protectedItemName As String, Optional odataQuery As ODataQuery(Of GetProtectedItemQueryObject) = null) As ProtectedItemResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-142">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-143">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-143">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-144">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-144">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-145">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-145">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-146">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-146">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-147">バックアップの詳細については、フェッチするのには項目の名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-147">Backed up item name whose details are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="76f52-148">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f52-148">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-149">バックアップ項目の詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="76f52-149">Provides the details of the backed up item.</span></span> <span data-ttu-id="76f52-150">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-150">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-151">操作の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-151">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, protectedItemName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectedItemsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItemResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.GetProtectedItemQueryObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f52-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="76f52-152">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="76f52-153">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-153">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f52-154">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="76f52-154">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="76f52-155">バックアップされた項目に関連付けられているファブリック名。</span><span class="sxs-lookup"><span data-stu-id="76f52-155">Fabric name associated with the backed up item.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="76f52-156">バックアップされた項目に関連付けられたコンテナー名。</span><span class="sxs-lookup"><span data-stu-id="76f52-156">Container name associated with the backed up item.</span></span>
            </param>
        <param name="protectedItemName">
            <span data-ttu-id="76f52-157">バックアップの詳細については、フェッチするのには項目の名前。</span><span class="sxs-lookup"><span data-stu-id="76f52-157">Backed up item name whose details are to be fetched.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="76f52-158">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f52-158">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="76f52-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="76f52-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f52-160">バックアップ項目の詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="76f52-160">Provides the details of the backed up item.</span></span> <span data-ttu-id="76f52-161">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="76f52-161">This is an asynchronous operation.</span></span> <span data-ttu-id="76f52-162">操作の状態を確認するには、GetItemOperationResult API を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="76f52-162">To know the status of the operation, call the GetItemOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>