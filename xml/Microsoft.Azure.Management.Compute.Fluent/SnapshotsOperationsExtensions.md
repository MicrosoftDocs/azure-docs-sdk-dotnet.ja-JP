<Type Name="SnapshotsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SnapshotsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SnapshotsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SnapshotsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SnapshotsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4f8ba-101">SnapshotsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-101">Extension methods for SnapshotsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-103">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-104">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-104">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4f8ba-105">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-105">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-107">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-107">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-109">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-110">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-110">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-112">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-112">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; BeginGrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginGrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginGrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginGrantAccessAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-114">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-115">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-115">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4f8ba-116">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-116">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-118">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-118">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginRevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginRevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginRevokeAccessAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-120">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-121">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-121">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-123">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-123">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-125">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-126">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-126">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4f8ba-127">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-127">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-129">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-129">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-131">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-132">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-132">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4f8ba-133">ディスクの Put 操作の本文に指定されているスナップショット オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-133">Snapshot object supplied in the body of the Put disk operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-135">作成するか、スナップショットを更新します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-135">Creates or updates a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.DeleteAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-137">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-137">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-138">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-138">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-140">スナップショットを削除します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-140">Deletes a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GetAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-142">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-143">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-143">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-145">スナップショットに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-145">Gets information about a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GrantAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt; GrantAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner grantAccessData, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GrantAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GrantAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.GrantAccessAsync (operations, resourceGroupName, snapshotName, grantAccessData, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;GrantAccessAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.AccessUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="grantAccessData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-147">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-148">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-148">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="grantAccessData">
            <span data-ttu-id="4f8ba-149">スナップショットの get アクセス操作の本文に指定されているアクセス データ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-149">Access data object supplied in the body of the get snapshot access operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-151">スナップショットへのアクセスを許可します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-151">Grants access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-152">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-154">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-154">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-156">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-158">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-158">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-159">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4f8ba-160">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-162">リソース グループの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-162">Lists snapshots under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;ListNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4f8ba-164">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-166">サブスクリプションの下のスナップショットを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-166">Lists snapshots under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokeAccessAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RevokeAccessAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.RevokeAccessAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RevokeAccessAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.RevokeAccessAsync (operations, resourceGroupName, snapshotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;RevokeAccessAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-168">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-168">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-169">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-169">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-171">スナップショットへのアクセスを取り消します。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-171">Revokes access to a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; UpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt; UpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations operations, string resourceGroupName, string snapshotName, class Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner snapshot, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions.UpdateAsync (operations, resourceGroupName, snapshotName, snapshot, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.SnapshotsOperationsExtensions/&lt;UpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="snapshotName" Type="System.String" />
        <Parameter Name="snapshot" Type="Microsoft.Azure.Management.Compute.Fluent.Models.SnapshotUpdateInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4f8ba-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4f8ba-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-173">The name of the resource group.</span></span>
            </param>
        <param name="snapshotName">
            <span data-ttu-id="4f8ba-174">指定されたサブスクリプションとリソース グループ内でスナップショットの名前。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-174">The name of the snapshot within the given subscription and resource group.</span></span>
            </param>
        <param name="snapshot">
            <span data-ttu-id="4f8ba-175">Patch スナップショット操作の本文に指定されているオブジェクトのスナップショットです。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-175">Snapshot object supplied in the body of the Patch snapshot operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4f8ba-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4f8ba-177">更新プログラム (修正プログラム) スナップショット。</span><span class="sxs-lookup"><span data-stu-id="4f8ba-177">Updates (patches) a snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>