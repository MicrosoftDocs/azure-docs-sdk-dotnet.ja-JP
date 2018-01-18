<Type Name="SnapshotsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SnapshotsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SnapshotsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SnapshotsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SnapshotsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="74bff-101">SnapshotsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="74bff-101">Extension methods for SnapshotsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-103">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-104">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-104">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-105">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="74bff-105">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-106">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="74bff-106">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-108">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-109">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-109">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-110">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="74bff-110">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-112">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="74bff-112">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDelete (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-114">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-115">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-115">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-116">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="74bff-116">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-118">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-119">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-119">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-121">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="74bff-121">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri BeginGrantAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccess (operations, resourceGroupName, snapshotName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-123">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-124">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-124">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="74bff-125">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="74bff-125">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-126">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="74bff-126">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-128">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-128">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-129">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-129">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="74bff-130">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="74bff-130">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-132">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="74bff-132">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRevokeAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRevokeAccess (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccess (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-134">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-134">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-135">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-135">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-136">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="74bff-136">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-138">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-139">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-139">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-141">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="74bff-141">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot BeginUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot BeginUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-143">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-144">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-144">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-145">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="74bff-145">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-146">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="74bff-146">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-148">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-148">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-149">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-149">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-150">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="74bff-150">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-152">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="74bff-152">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot CreateOrUpdate (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot CreateOrUpdate(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-154">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-155">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-155">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-156">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="74bff-156">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-157">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="74bff-157">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.Snapshot snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.Snapshot,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.Snapshot * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.Snapshot" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-159">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-159">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-160">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-160">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-161">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="74bff-161">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-163">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="74bff-163">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Delete (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-165">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-166">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-166">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-167">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="74bff-167">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.DeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-168">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-169">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-169">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-170">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-170">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-172">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="74bff-172">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot Get (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot Get(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As Snapshot" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Get (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-173">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-174">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-174">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-175">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-175">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-176">スナップショットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="74bff-176">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; GetAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; GetAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GetAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-178">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-179">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-179">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-181">スナップショットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="74bff-181">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.AccessUri GrantAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData)" />
      <MemberSignature Language="F#" Value="static member GrantAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData -&gt; Microsoft.Azure.Management.Compute.Models.AccessUri" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccess (operations, resourceGroupName, snapshotName, grantAccessData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.AccessUri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-183">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-184">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-184">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="74bff-185">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="74bff-185">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-186">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="74bff-186">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.AccessUri&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.GrantAccessData grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.GrantAccessData,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.GrantAccessData * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;GrantAccessAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.AccessUri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Models.GrantAccessData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-188">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-188">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-189">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-189">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="74bff-190">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="74bff-190">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-192">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="74bff-192">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; List (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; List(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.List(Microsoft.Azure.Management.Compute.ISnapshotsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ISnapshotsOperations) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.ISnapshotsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-193">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-194">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-194">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-195">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-197">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-197">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroup (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroup(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As ISnapshotsOperations, resourceGroupName As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-199">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-200">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-200">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-202">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-204">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-204">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As ISnapshotsOperations, nextPageLink As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="74bff-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="74bff-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-207">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-207">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="74bff-209">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="74bff-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-211">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-211">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListNext (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; ListNext(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ISnapshotsOperations, nextPageLink As String) As IPage(Of Snapshot)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-212">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-212">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="74bff-213">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="74bff-213">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-214">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-214">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;ListNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-215">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="74bff-216">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="74bff-216">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-218">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="74bff-218">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccess">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse RevokeAccess(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccess(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RevokeAccess (operations As ISnapshotsOperations, resourceGroupName As String, snapshotName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member RevokeAccess : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccess (operations, resourceGroupName, snapshotName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-219">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-219">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-220">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-220">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-221">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-221">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-222">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="74bff-222">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;RevokeAccessAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-224">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-224">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-225">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-225">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-227">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="74bff-227">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.Snapshot Update (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.Snapshot Update(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Update(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate -&gt; Microsoft.Azure.Management.Compute.Models.Snapshot" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.Update (operations, resourceGroupName, snapshotName, snapshot)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-228">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-229">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-229">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-230">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-230">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-231">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="74bff-231">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-232">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="74bff-232">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.Snapshot&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Models.SnapshotUpdate snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.SnapshotUpdate,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Models.SnapshotUpdate * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;" Usage="Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions.UpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.SnapshotsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.Snapshot&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Models.SnapshotUpdate" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="74bff-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="74bff-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="74bff-234">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-234">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="74bff-235">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="74bff-235">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="74bff-236">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="74bff-236">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="74bff-237">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="74bff-237">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="74bff-238">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="74bff-238">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>