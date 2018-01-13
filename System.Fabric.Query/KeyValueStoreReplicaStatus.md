<Type Name="KeyValueStoreReplicaStatus" FullName="System.Fabric.Query.KeyValueStoreReplicaStatus">
  <TypeSignature Language="C#" Value="public sealed class KeyValueStoreReplicaStatus : System.Fabric.Query.ReplicaStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyValueStoreReplicaStatus extends System.Fabric.Query.ReplicaStatus" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.KeyValueStoreReplicaStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyValueStoreReplicaStatus&#xA;Inherits ReplicaStatus" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplicaStatus = class&#xA;    inherit ReplicaStatus" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.ReplicaStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce531-101">レプリカ キーと値のストアの状態をクエリします。</span><span class="sxs-lookup"><span data-stu-id="ce531-101">Query status for a key/value store replica</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyNotificationCurrentKeyFilter">
      <MemberSignature Language="C#" Value="public string CopyNotificationCurrentKeyFilter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CopyNotificationCurrentKeyFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentKeyFilter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyNotificationCurrentKeyFilter As String" />
      <MemberSignature Language="F#" Value="member this.CopyNotificationCurrentKeyFilter : string" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentKeyFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce531-102">中に列挙体に適用される最新のキーのプレフィックス フィルターを示す値を取得、<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />コールバック。</span><span class="sxs-lookup"><span data-stu-id="ce531-102">Gets a value indicating the latest key-prefix filter applied to enumeration during the <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> callback.</span></span> <span data-ttu-id="ce531-103">保留中のコールバックが存在しない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="ce531-103">Null if there is no pending callback.</span></span>
            </summary>
        <value><span data-ttu-id="ce531-104">キーのプレフィックス フィルターです。</span><span class="sxs-lookup"><span data-stu-id="ce531-104">The key prefix filter.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyNotificationCurrentProgress">
      <MemberSignature Language="C#" Value="public long CopyNotificationCurrentProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 CopyNotificationCurrentProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyNotificationCurrentProgress As Long" />
      <MemberSignature Language="F#" Value="member this.CopyNotificationCurrentProgress : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.CopyNotificationCurrentProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce531-105">中に列挙するキーの最新の数を示す値を取得、<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />コールバック。</span><span class="sxs-lookup"><span data-stu-id="ce531-105">Gets a value indicating the latest number of keys enumerated during the <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> callback.</span></span> <span data-ttu-id="ce531-106">保留中のコールバックが存在しない場合は 0 を返します。</span><span class="sxs-lookup"><span data-stu-id="ce531-106">0 if there is no pending callback.</span></span>
            </summary>
        <value><span data-ttu-id="ce531-107">キーの数。</span><span class="sxs-lookup"><span data-stu-id="ce531-107">The number of keys.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseLogicalSizeEstimate">
      <MemberSignature Language="C#" Value="public long DatabaseLogicalSizeEstimate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseLogicalSizeEstimate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseLogicalSizeEstimate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseLogicalSizeEstimate As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseLogicalSizeEstimate : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseLogicalSizeEstimate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce531-108">基になるデータベースの推定の論理サイズを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce531-108">Gets a value indicating the estimated logical size of the underlying database.</span></span>
            </summary>
        <value><span data-ttu-id="ce531-109">バイト単位の論理データベースの推定サイズ。</span><span class="sxs-lookup"><span data-stu-id="ce531-109">The estimated logical database size in bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseRowCountEstimate">
      <MemberSignature Language="C#" Value="public long DatabaseRowCountEstimate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DatabaseRowCountEstimate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseRowCountEstimate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseRowCountEstimate As Long" />
      <MemberSignature Language="F#" Value="member this.DatabaseRowCountEstimate : int64" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.DatabaseRowCountEstimate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce531-110">基になるデータベース内の行の推定数を示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="ce531-110">Gets a value indicating the estimated number of rows in the underlying database.</span></span>
            </summary>
        <value><span data-ttu-id="ce531-111">行の推定数。</span><span class="sxs-lookup"><span data-stu-id="ce531-111">The estimated number of rows.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.KeyValueStoreReplicaStatus.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="System.Fabric.Query.KeyValueStoreReplicaStatus.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce531-112">(存在する場合)、現在の状態の詳細を示す値を取得、レプリカのです。</span><span class="sxs-lookup"><span data-stu-id="ce531-112">Gets a value indicating the current status details (if any) of the replica.</span></span>
            </summary>
        <value><span data-ttu-id="ce531-113">ステータス。</span><span class="sxs-lookup"><span data-stu-id="ce531-113">The status.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>