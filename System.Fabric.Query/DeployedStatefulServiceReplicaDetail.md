<Type Name="DeployedStatefulServiceReplicaDetail" FullName="System.Fabric.Query.DeployedStatefulServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplicaDetail : System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplicaDetail extends System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplicaDetail&#xA;Inherits DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplicaDetail = class&#xA;    inherit DeployedServiceReplicaDetail" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplicaDetail</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>コード パッケージで実行して、ステートフルなレプリカに関する情報を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplicaDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentReplicatorOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentReplicatorOperation As ReplicatorOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentReplicatorOperation : System.Fabric.Query.ReplicatorOperationName" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリケーターで実行されている現在の Api を取得します。</para>
        </summary>
        <value>
          <para>レプリケーターで実行されている現在の Api。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServiceReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServiceReplica As DeployedStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="member this.DeployedServiceReplica : System.Fabric.Query.DeployedStatefulServiceReplica" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカのロール、ホスト プロセス Id、再構成に関する情報と同様に、展開済みサービス レプリカの追加の詳細を取得します。</para>
          <value>レプリカの詳細です。</value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>現在のこのレプリカの状態の読み取りを取得します。</para>
        </summary>
        <value>
          <para>現在では、このレプリカの状態を読み取る。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
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
          <para>このレプリカのレプリカの ID を取得します。</para>
        </summary>
        <value>
          <para>レプリカ ID</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ReplicaStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在のレプリカの状態を示す値を取得します。
            </summary>
        <value>レプリカの状態。</value>
        <remarks>現時点では、のみのレプリカ型<see cref="T:System.Fabric.KeyValueStoreReplica" />クエリ ステータスの詳細が生成されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorStatus ReplicatorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorStatus ReplicatorStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorStatus As ReplicatorStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicatorStatus : System.Fabric.Query.ReplicatorStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Service Fabric レプリケーター、レプリカが使用されている場合は、レプリケーターに関する情報を取得します。</para>
        </summary>
        <value>
          <para>レプリケーター状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカの現在の書き込みの状態を取得します。</para>
        </summary>
        <value>
          <para>現在では、レプリカの状態を記述します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>