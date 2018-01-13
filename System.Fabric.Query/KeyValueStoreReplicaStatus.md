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
            レプリカ キーと値のストアの状態をクエリします。
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
            中に列挙体に適用される最新のキーのプレフィックス フィルターを示す値を取得、<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />コールバック。 保留中のコールバックが存在しない場合は null です。
            </summary>
        <value>キーのプレフィックス フィルターです。</value>
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
            中に列挙するキーの最新の数を示す値を取得、<see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />コールバック。 保留中のコールバックが存在しない場合は 0 を返します。
            </summary>
        <value>キーの数。</value>
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
            基になるデータベースの推定の論理サイズを示す値を取得します。
            </summary>
        <value>バイト単位の論理データベースの推定サイズ。</value>
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
            基になるデータベース内の行の推定数を示す値を取得します。
            </summary>
        <value>行の推定数。</value>
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
            (存在する場合)、現在の状態の詳細を示す値を取得、レプリカのです。
            </summary>
        <value>ステータス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>