<Type Name="PartitionAccessStatus" FullName="System.Fabric.PartitionAccessStatus">
  <TypeSignature Language="C#" Value="public enum PartitionAccessStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed PartitionAccessStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PartitionAccessStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum PartitionAccessStatus" />
  <TypeSignature Language="F#" Value="type PartitionAccessStatus = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>パーティションのアクセスの状態を列挙します。 </para>
    </summary>
    <remarks>
      <para>
        <see cref="T:System.Fabric.PartitionAccessStatus" />読み取りまたは書き込み操作が許可されていること確認に使用されます。 サービス レプリカでは、クライアント要求を処理するときに、システムが、処理を許可する状態を確認します。 チェックして、<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />または<see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />を適切な操作を妨げる条件の必要に応じて、レプリカを通知することができます。 書き込み操作を可能性がありますも例外を参照して、これらの条件のいずれかの複製物作成会社からの間で変わる可能性がある条件、<see cref="P:System.Fabric.IStatefulServicePartition.WriteStatus" />チェックとへの呼び出し<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。 </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Granted">
      <MemberSignature Language="C#" Value="Granted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Granted = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Granted" />
      <MemberSignature Language="VB.NET" Value="Granted" />
      <MemberSignature Language="F#" Value="Granted = 1" Usage="System.Fabric.PartitionAccessStatus.Granted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>読み取りまたは書き込み操作のアクセスが許可される操作が許可されていることを示します。 </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.PartitionAccessStatus.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>読み取りまたは書き込み操作のアクセスの状態が無効であることを示します。 この値は、呼び出し元に返されません。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NotPrimary">
      <MemberSignature Language="C#" Value="NotPrimary" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NotPrimary = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberSignature Language="VB.NET" Value="NotPrimary" />
      <MemberSignature Language="F#" Value="NotPrimary = 3" Usage="System.Fabric.PartitionAccessStatus.NotPrimary" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para>このクライアント要求がプライマリ レプリカではないレプリカによって受信されたことを示します。 このレプリカでは、読み取りまたは書き込み操作を実行できません。 クライアントは、名前付けサービスを使用して正しいプライマリ レプリカを特定しようとする必要があります。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="NoWriteQuorum">
      <MemberSignature Language="C#" Value="NoWriteQuorum" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus NoWriteQuorum = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberSignature Language="VB.NET" Value="NoWriteQuorum" />
      <MemberSignature Language="F#" Value="NoWriteQuorum = 4" Usage="System.Fabric.PartitionAccessStatus.NoWriteQuorum" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para>使用できる書き込みクォーラムがないと、そのため、書き込み操作が受け入れられませんことを示します。 クライアントは、このレプリカで操作を再試行する必要があります。</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ReconfigurationPending">
      <MemberSignature Language="C#" Value="ReconfigurationPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.PartitionAccessStatus ReconfigurationPending = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberSignature Language="VB.NET" Value="ReconfigurationPending" />
      <MemberSignature Language="F#" Value="ReconfigurationPending = 2" Usage="System.Fabric.PartitionAccessStatus.ReconfigurationPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>再構成が進行中のために、クライアントが、後でもう一度試行する必要がありますを示します。 再構成が完了すると、さらに手順を説明する新しい状態が返されます。 クライアントは、このレプリカで操作を再試行してください。</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>