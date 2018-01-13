<Type Name="SafetyCheckKind" FullName="System.Fabric.SafetyCheckKind">
  <TypeSignature Language="C#" Value="public enum SafetyCheckKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SafetyCheckKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.SafetyCheckKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum SafetyCheckKind" />
  <TypeSignature Language="F#" Value="type SafetyCheckKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Service Fabric 列挙を示す、アップグレードの安全性チェックが実行されます。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnsureAvailability">
      <MemberSignature Language="C#" Value="EnsureAvailability" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsureAvailability = int32(7)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsureAvailability" />
      <MemberSignature Language="VB.NET" Value="EnsureAvailability" />
      <MemberSignature Language="F#" Value="EnsureAvailability = 7" Usage="System.Fabric.SafetyCheckKind.EnsureAvailability" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
          <para>
            1 つのインスタンスを持つノードにステートレスのサービス パーティションがあるか、対象のパーティションがクォーラム損失ノードにプライマリ レプリカがあることを示します。 どちらの場合も、によって、レプリカがダウンと、可用性の低下が発生します。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsurePartitionQuorum">
      <MemberSignature Language="C#" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsurePartitionQuorum = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsurePartitionQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsurePartitionQuorum" />
      <MemberSignature Language="F#" Value="EnsurePartitionQuorum = 2" Usage="System.Fabric.SafetyCheckKind.EnsurePartitionQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>
            対象の場合は、ノード上のレプリカを停止生じますそのパーティションのクォーラム損失にパーティションがあることを示します。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="EnsureSeedNodeQuorum">
      <MemberSignature Language="C#" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind EnsureSeedNodeQuorum = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberSignature Language="VB.NET" Value="EnsureSeedNodeQuorum" />
      <MemberSignature Language="F#" Value="EnsureSeedNodeQuorum = 1" Usage="System.Fabric.SafetyCheckKind.EnsureSeedNodeQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            ノードを停止している場合、これになるグローバル シード ノードのクォーラムの損失を示します。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.SafetyCheckKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            アップグレードの安全性チェックの種類が無効であることを示します。 この値は使用されません。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForInBuildReplica">
      <MemberSignature Language="C#" Value="WaitForInBuildReplica" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForInBuildReplica = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForInBuildReplica" />
      <MemberSignature Language="VB.NET" Value="WaitForInBuildReplica" />
      <MemberSignature Language="F#" Value="WaitForInBuildReplica = 6" Usage="System.Fabric.SafetyCheckKind.WaitForInBuildReplica" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para>
            コピーを通過するノードで、いずれかのレプリカがあるかはその他のレプリカにデータをコピーするノードでプライマリ レプリカがあることを示します。 どちらの場合は、によって、ノード上のレプリカがダウンにコピーが中止されます。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimaryPlacement">
      <MemberSignature Language="C#" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForPrimaryPlacement = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimaryPlacement" />
      <MemberSignature Language="F#" Value="WaitForPrimaryPlacement = 3" Usage="System.Fabric.SafetyCheckKind.WaitForPrimaryPlacement" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>
            このノードから移動されたノード上のレプリカがあることを示します。 Service Fabric は、プライマリへのこのノードに移動する待機しています。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForPrimarySwap">
      <MemberSignature Language="C#" Value="WaitForPrimarySwap" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForPrimarySwap = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForPrimarySwap" />
      <MemberSignature Language="VB.NET" Value="WaitForPrimarySwap" />
      <MemberSignature Language="F#" Value="WaitForPrimarySwap = 4" Usage="System.Fabric.SafetyCheckKind.WaitForPrimarySwap" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>
            Service Fabric がプライマリ レプリカ ノード外に移動するを待機していることを示します。
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitForReconfiguration">
      <MemberSignature Language="C#" Value="WaitForReconfiguration" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.SafetyCheckKind WaitForReconfiguration = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.SafetyCheckKind.WaitForReconfiguration" />
      <MemberSignature Language="VB.NET" Value="WaitForReconfiguration" />
      <MemberSignature Language="F#" Value="WaitForReconfiguration = 5" Usage="System.Fabric.SafetyCheckKind.WaitForReconfiguration" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SafetyCheckKind</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para>
            再構成に含まれるノードにいくつかのレプリカがあり、Service Fabric が、完了される再構成を待機していることを示します。
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>