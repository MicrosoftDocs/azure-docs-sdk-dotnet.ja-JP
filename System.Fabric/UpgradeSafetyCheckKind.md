<Type Name="UpgradeSafetyCheckKind" FullName="System.Fabric.UpgradeSafetyCheckKind">
  <TypeSignature Language="C#" Value="public enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeSafetyCheckKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeSafetyCheckKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeSafetyCheckKind" />
  <TypeSignature Language="F#" Value="type UpgradeSafetyCheckKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>列挙、<see cref="T:System.Fabric.UpgradeSafetyCheck" />が実行されるノードのアップグレード中にします。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnsureAvailability">
      <MemberSignature Language="C#" Value="EnsureAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureAvailability = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberSignature Language="VB.NET" Value="EnsureAvailability" />
      <MemberSignature Language="F#" Value="EnsureAvailability = 7" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>1 つのインスタンスを持つノードにステートレスのサービス パーティションがあるか、対象のパーティションがクォーラム損失ノードにプライマリ レプリカがあることを示します。 どちらの場合にアップグレードするためのレプリカ ダウンと、可用性の低下が発生します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsurePartitionQuorum">
      <MemberSignature Language="C#" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsurePartitionQuorum = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="F#" Value="EnsurePartitionQuorum = 2" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsurePartitionQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>対象の場合は、ノード上のレプリカを停止生じますそのパーティションのクォーラム損失にパーティションがあることを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsureSeedNodeQuorum">
      <MemberSignature Language="C#" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind EnsureSeedNodeQuorum = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="F#" Value="EnsureSeedNodeQuorum = 1" Usage="System.Fabric.UpgradeSafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>ノードを停止している場合、これになるグローバル シード ノードのクォーラムの損失を示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeSafetyCheckKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードの安全性チェックの種類が無効であることを示します。 この値は使用されません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForInbuildReplica">
      <MemberSignature Language="C#" Value="WaitForInbuildReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForInbuildReplica = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberSignature Language="VB.NET" Value="WaitForInbuildReplica" />
      <MemberSignature Language="F#" Value="WaitForInbuildReplica = 6" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForInbuildReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>コピーを通過するノードで、いずれかのレプリカがあるかはその他のレプリカにデータをコピーするノードでプライマリ レプリカがあることを示します。 どちらの場合をアップグレードするため、ノード上のレプリカを停止することに、コピーが中止されます。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimaryPlacement">
      <MemberSignature Language="C#" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimaryPlacement = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="F#" Value="WaitForPrimaryPlacement = 3" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>アップグレードするためには、このノードから移動されたノード上のレプリカがあることを示します。 Service Fabric は、プライマリへのこのノードに移動する待機しています。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimarySwap">
      <MemberSignature Language="C#" Value="WaitForPrimarySwap" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForPrimarySwap = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimarySwap" />
      <MemberSignature Language="F#" Value="WaitForPrimarySwap = 4" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForPrimarySwap" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>Service Fabric がそのノードでアップグレードを開始する前に、ノードから移動するプライマリ レプリカを待機していることを示します。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForReconfiguration">
      <MemberSignature Language="C#" Value="WaitForReconfiguration" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForReconfiguration = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberSignature Language="VB.NET" Value="WaitForReconfiguration" />
      <MemberSignature Language="F#" Value="WaitForReconfiguration = 5" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForReconfiguration" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>再構成に関係するノード上のレプリカがあることを示します。 Service Fabric が、完了される再構成を開始する前に待機しているノード上でアップグレードします。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForResourceAvailability">
      <MemberSignature Language="C#" Value="WaitForResourceAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeSafetyCheckKind WaitForResourceAvailability = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberSignature Language="VB.NET" Value="WaitForResourceAvailability" />
      <MemberSignature Language="F#" Value="WaitForResourceAvailability = 8" Usage="System.Fabric.UpgradeSafetyCheckKind.WaitForResourceAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeSafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para>まだありません、アップグレードを続行する管理対象リソースのメトリックに十分な容量を示します。 これは、サービス パッケージには、リソースの消費量が増加している場合に発生することができます。 Service Fabric は、ノードに十分な容量があることを確認するアクションを確立しています。 </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>