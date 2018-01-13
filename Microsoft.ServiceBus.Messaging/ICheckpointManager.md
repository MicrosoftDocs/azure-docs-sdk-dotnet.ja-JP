<Type Name="ICheckpointManager" FullName="Microsoft.ServiceBus.Messaging.ICheckpointManager">
  <TypeSignature Language="C#" Value="public interface ICheckpointManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckpointManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckpointManager" />
  <TypeSignature Language="F#" Value="type ICheckpointManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>チェックポイントを非同期的に実行するためのメソッドを提供します。 機能拡張は、オフセットを格納するためのホスト固有の記憶域を指定するものです。 これは、提供時に<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorAsync``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />が呼び出されると、チェックポイントを使用して、オフセット位置に<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CheckpointAsync (Microsoft.ServiceBus.Messaging.Lease lease, string offset, long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CheckpointAsync(class Microsoft.ServiceBus.Messaging.Lease lease, string offset, int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.ICheckpointManager.CheckpointAsync(Microsoft.ServiceBus.Messaging.Lease,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="abstract member CheckpointAsync : Microsoft.ServiceBus.Messaging.Lease * string * int64 -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.CheckpointAsync (lease, offset, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="offset" Type="System.String" />
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="lease">チェックポイントを実行する対象のパーティション情報。</param>
        <param name="offset">ストリームの現在の位置。</param>
        <param name="sequenceNumber">パーティションのシーケンス番号。</param>
        <summary>ホストに固有のストア内の特定のパーティションのオフセットを格納します。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>