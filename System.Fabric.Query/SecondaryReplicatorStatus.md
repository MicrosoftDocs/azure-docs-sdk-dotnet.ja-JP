<Type Name="SecondaryReplicatorStatus" FullName="System.Fabric.Query.SecondaryReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class SecondaryReplicatorStatus : System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SecondaryReplicatorStatus extends System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.SecondaryReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SecondaryReplicatorStatus&#xA;Inherits ReplicatorStatus" />
  <TypeSignature Language="F#" Value="type SecondaryReplicatorStatus = class&#xA;    inherit ReplicatorStatus" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.ReplicatorStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>機能しているときに、Service Fabric レプリケーターに関する統計情報を提供する<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロール。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecondaryReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.SecondaryReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.SecondaryReplicatorStatus" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyQueueStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorQueueStatus CopyQueueStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorQueueStatus CopyQueueStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.CopyQueueStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyQueueStatus As ReplicatorQueueStatus" />
      <MemberSignature Language="F#" Value="member this.CopyQueueStatus : System.Fabric.Query.ReplicatorQueueStatus" Usage="System.Fabric.Query.SecondaryReplicatorStatus.CopyQueueStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorQueueStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>コピー キューの状態を取得します。</para>
        </summary>
        <value>
          <para>コピー キューの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInBuild">
      <MemberSignature Language="C#" Value="public bool IsInBuild { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInBuild" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.IsInBuild" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInBuild : bool" Usage="System.Fabric.Query.SecondaryReplicatorStatus.IsInBuild" />
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
          <para>レプリカが現在作成されているかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>レプリカされている組み込み、それ以外の場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAcknowledgementSentTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastAcknowledgementSentTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastAcknowledgementSentTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastAcknowledgementSentTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAcknowledgementSentTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastAcknowledgementSentTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastAcknowledgementSentTimeUtc" />
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
          <para>最後のタイムスタンプ (UTC) プライマリ レプリケーターに送信された受信確認を取得します。</para>
        </summary>
        <value>
          <para>最後のタイムスタンプ プライマリ レプリケーターに送信された受信確認します。</para>
        </value>
        <remarks>
          <para>0 (utc) では、受信確認メッセージが送信しないことを示す、無効な値を表します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCopyOperationReceivedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastCopyOperationReceivedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastCopyOperationReceivedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastCopyOperationReceivedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCopyOperationReceivedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastCopyOperationReceivedTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastCopyOperationReceivedTimeUtc" />
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
          <para>最後のタイムスタンプ (UTC) には、コピー操作がプライマリからのビルドの一部として受信したを取得します。</para>
        </summary>
        <value>
          <para>最後のタイムスタンプには、コピー操作がプライマリからのビルドの一部として受信しました。</para>
        </value>
        <remarks>
          <para>0 (utc) では、コピー操作のメッセージが受信しないことを示す、無効な値を表します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReplicationOperationReceivedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastReplicationOperationReceivedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastReplicationOperationReceivedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastReplicationOperationReceivedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReplicationOperationReceivedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastReplicationOperationReceivedTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastReplicationOperationReceivedTimeUtc" />
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
          <para>最後のタイムスタンプ (UTC) には、レプリケーション操作がプライマリから受信したを取得します。</para>
        </summary>
        <value>
          <para>最後のタイムスタンプには、レプリケーション操作がプライマリから受信しました。</para>
        </value>
        <remarks>
          <para>0 (utc) では、レプリケーション操作のメッセージが受信しないことを示す、無効な値を表します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationQueueStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationQueueStatus As ReplicatorQueueStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicationQueueStatus : System.Fabric.Query.ReplicatorQueueStatus" Usage="System.Fabric.Query.SecondaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorQueueStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリケーション キューの状態を取得します。</para>
        </summary>
        <value>
          <para>レプリケーション キューの状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>