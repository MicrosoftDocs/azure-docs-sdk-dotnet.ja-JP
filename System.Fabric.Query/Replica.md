<Type Name="Replica" FullName="System.Fabric.Query.Replica">
  <TypeSignature Language="C#" Value="public abstract class Replica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Replica extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Replica" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Replica" />
  <TypeSignature Language="F#" Value="type Replica = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessServiceInstance))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulServiceReplica))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>クエリのレプリカを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Replica (System.Fabric.Query.ServiceKind serviceKind, long id, System.Fabric.Query.ServiceReplicaStatus replicaStatus, System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, TimeSpan lastInBuildDuration);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind, int64 id, valuetype System.Fabric.Query.ServiceReplicaStatus replicaStatus, valuetype System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, valuetype System.TimeSpan lastInBuildDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.Replica.#ctor(System.Fabric.Query.ServiceKind,System.Int64,System.Fabric.Query.ServiceReplicaStatus,System.Fabric.Health.HealthState,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.Replica : System.Fabric.Query.ServiceKind * int64 * System.Fabric.Query.ServiceReplicaStatus * System.Fabric.Health.HealthState * string * string * TimeSpan -&gt; System.Fabric.Query.Replica" Usage="new System.Fabric.Query.Replica (serviceKind, id, replicaStatus, healthState, replicaAddress, nodeName, lastInBuildDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
        <Parameter Name="id" Type="System.Int64" />
        <Parameter Name="replicaStatus" Type="System.Fabric.Query.ServiceReplicaStatus" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
        <Parameter Name="replicaAddress" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="lastInBuildDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para>レプリカの種類</para>
        </param>
        <param name="id">
          <para>レプリカ ID</para>
        </param>
        <param name="replicaStatus">
          <para>状態のレプリカで初期化されます。</para>
        </param>
        <param name="healthState">
          <para>ヘルス状態のレプリカで初期化されます。</para>
        </param>
        <param name="replicaAddress">
          <para>アドレスのレプリカで初期化されます。</para>
        </param>
        <param name="nodeName">
          <para>ノード名のレプリカで初期化されます。</para>
        </param>
        <param name="lastInBuildDuration">
          <para>ビルド時間レプリカ内の最後で初期化されます。</para>
        </param>
        <summary>
          <para>レプリカを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Replica.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカの正常性状態を取得します。</para>
        </summary>
        <value>
          <para>レプリカの正常性状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64 with get, set" Usage="System.Fabric.Query.Replica.Id" />
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
          <para>レプリカの識別子を取得します。</para>
        </summary>
        <value>
          <para>レプリカの識別子です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LastInBuildDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LastInBuildDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastInBuildDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDuration : TimeSpan" Usage="System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>最後にビルドを取得期間。</para>
        </summary>
        <value>
          <para>ビルドの期間内の最後。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDurationInSeconds">
      <MemberSignature Language="C#" Value="protected internal long LastInBuildDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastInBuildDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property LastInBuildDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDurationInSeconds : int64" Usage="System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
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
            ビルド時間を秒単位の最後に取得します。
            </summary>
        <value>最後のビルド時間の秒単位にします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Replica.NodeName" />
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
          <para>レプリカが実行されているノード名を取得します。</para>
        </summary>
        <value>
          <para>ノード名、レプリカがで実行されています。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaAddress">
      <MemberSignature Language="C#" Value="public string ReplicaAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicaAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicaAddress : string" Usage="System.Fabric.Query.Replica.ReplicaAddress" />
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
          <para>レプリカがリッスン アドレスを取得します。</para>
        </summary>
        <value>
          <para>アドレス、レプリカがリッスンします。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ServiceReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ServiceReplicaStatus" Usage="System.Fabric.Query.Replica.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカの状態を取得します。</para>
        </summary>
        <value>
          <para>レプリカの状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Replica.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスの種類を取得します。
            </summary>
        <value>サービスの種類。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>