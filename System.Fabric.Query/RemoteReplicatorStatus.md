<Type Name="RemoteReplicatorStatus" FullName="System.Fabric.Query.RemoteReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorStatus" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorStatus = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>セカンダリのレプリケーター プライマリ レプリケーターの視点からの状態を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInBuild">
      <MemberSignature Language="C#" Value="public bool IsInBuild { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInBuild" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInBuild : bool" Usage="System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>セカンダリ レプリカがビルドの処理中かどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>場合、セカンダリ レプリカは、それ以外のビルド処理を行って<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAcknowledgementProcessedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastAcknowledgementProcessedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAcknowledgementProcessedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastAcknowledgementProcessedTimeUtc : DateTime" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>最後のタイムスタンプを取得 (UTC) のセカンダリに複製物作成会社からの受信確認をプライマリに処理された日時。</para>
        </summary>
        <value>
          <para>プライマリとセカンダリの複製物作成会社からの受信確認の最後のタイムスタンプが処理されました。</para>
        </value>
        <remarks>
          <para>0 (utc) では、処理ことを示す受信確認メッセージがこれまでなしに無効な値を表します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
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
          <para>セカンダリがその状態に適用される最高コピー操作のシーケンス番号を取得します。</para>
        </summary>
        <value>
          <para>最大コピー操作のシーケンス番号、セカンダリの状態が適用されます。</para>
        </value>
        <remarks>
          <para>コピー処理が完了したことを示します、-1 の値を無視できます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
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
          <para>セカンダリがその状態に適用される最高レプリケーション操作のシーケンス番号を取得します。</para>
        </summary>
        <value>
          <para>最大レプリケーション操作のシーケンス番号、セカンダリの状態が適用されます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
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
          <para>セカンダリがプライマリから受信した最大コピー操作のシーケンス番号を取得します。</para>
        </summary>
        <value>
          <para>最大コピー操作のシーケンス番号、セカンダリがプライマリから受信しました。</para>
        </value>
        <remarks>
          <para>コピー処理が完了したことを示します、-1 の値を無視できます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
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
          <para>セカンダリがプライマリから受信したが最も高いレプリケーション操作のシーケンス番号を取得します。</para>
        </summary>
        <value>
          <para>最大レプリケーション操作のシーケンス番号、セカンダリがプライマリから受信しました。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteReplicatorAcknowledgementStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteReplicatorAcknowledgementStatus As RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="F#" Value="member this.RemoteReplicatorAcknowledgementStatus : System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" Usage="System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.RemoteReplicatorAcknowledgementStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>リモートのレプリケーターの各受信確認番号が含まれています</para>
          <para>値は、レプリカの状態に依存します。 Inbuild レプリカ active replias がない状態でコピーに関連する値が含まれます。</para>
        </summary>
        <value>
          <para>レプリケーションのコピーとストリームの受信確認に関する詳細情報を含む RemoteReplicatorAcknowledgementStatus オブジェクト。 詳細については、「 <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" /> 」を参照してください。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
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
          <para>セカンダリのレプリカの ID を取得します。</para>
        </summary>
        <value>
          <para>レプリカ ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>