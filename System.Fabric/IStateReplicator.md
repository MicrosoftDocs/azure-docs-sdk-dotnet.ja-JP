<Type Name="IStateReplicator" FullName="System.Fabric.IStateReplicator">
  <TypeSignature Language="C#" Value="public interface IStateReplicator" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateReplicator" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateReplicator" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateReplicator" />
  <TypeSignature Language="F#" Value="type IStateReplicator = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>レプリケーションに関連する関数を公開、<see cref="T:System.Fabric.FabricReplicator" />クラスによって使用されている<see cref="T:System.Fabric.IStateProvider" />を高可用性を保証する状態をレプリケートします。 </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetCopyStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetCopyStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetCopyStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetCopyStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>取得では、ストリームをコピーします。</para>
        </summary>
        <returns>
          <para>コピーを返します<see cref="T:System.Fabric.IOperationStream" />です。 </para>
        </returns>
        <remarks>
          <para>返された CopyStream、<see cref="T:System.Fabric.IOperationStream" />を格納している<see cref="T:System.Fabric.OperationData" />を実装するオブジェクト<see cref="T:System.Fabric.IOperation" />です。 <see cref="T:System.Fabric.OperationData" />オブジェクトが、CopyState から取得した<see cref="T:System.Fabric.IOperationDataStream" />から、プライマリ レプリカを返す<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。 レプリカが作成され、遅延を解消するのには、する必要があります、CopyStream を取得し、送信、適用、および承認を実装するオブジェクトのコピーを開始<see cref="T:System.Fabric.IOperation" />です。 並行して、レプリカは、対応する応答<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />と<see cref="M:System.Fabric.IOperationDataStream.GetNextAsync(System.Threading.CancellationToken)" />呼び出しです。 ストリームが空ときに、返された<see cref="T:System.Fabric.IOperation" />メソッドは null です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。 次のいずれかが原因</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationStream">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationStream GetReplicationStream ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationStream GetReplicationStream() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.GetReplicationStream" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicationStream () As IOperationStream" />
      <MemberSignature Language="F#" Value="abstract member GetReplicationStream : unit -&gt; System.Fabric.IOperationStream" Usage="iStateReplicator.GetReplicationStream " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>レプリケーション ストリームを取得します。</para>
        </summary>
        <returns>
          <para>複製を返します<see cref="T:System.Fabric.IOperationStream" />です。</para>
        </returns>
        <remarks>
          <para>ReplicationStream 実装<see cref="T:System.Fabric.IOperationStream" />です。 含まれています、ReplicationStream<see cref="T:System.Fabric.OperationData" />を実装するオブジェクト<see cref="T:System.Fabric.IOperation" />です。 オブジェクトが経由でプライマリ レプリカによって提供される<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。 一般に、セカンダリ レプリカを送信する必要があります<see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />です。 Service Fabric では、これを行うサービスは必要ありません、一般にサービスがすべて転送<see cref="T:System.Fabric.OperationData" />コピーからオブジェクトが最初に、ストリームし、レプリケーション ストリームからの操作を転送します。 同時に両方のコピーからの転送がサポートされていますが、増加状態を適用する際の複雑さは正しく更新し、高度なサービスにのみ推奨されます。 ストリームが空ときに、返された<see cref="T:System.Fabric.IOperation" />メソッドは null です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。 次のいずれかが原因</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ReplicateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ReplicateAsync (System.Fabric.OperationData operationData, System.Threading.CancellationToken cancellationToken, out long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ReplicateAsync(class System.Fabric.OperationData operationData, valuetype System.Threading.CancellationToken cancellationToken, [out] int64&amp; sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />
      <MemberSignature Language="F#" Value="abstract member ReplicateAsync : System.Fabric.OperationData * System.Threading.CancellationToken *  -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iStateReplicator.ReplicateAsync (operationData, cancellationToken, sequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationData" Type="System.Fabric.OperationData" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="sequenceNumber" Type="System.Int64&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="operationData">
          <para><see cref="T:System.Fabric.OperationData" />プライマリ レプリカは、レプリケートする必要がある状態の変更を表すです。</para>
        </param>
        <param name="cancellationToken">
          <para> 失われているレプリカの書き込みクォーラムです。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <param name="sequenceNumber">
          <para>Long、操作の LSN です。 これは、タスクによって返される同じ値であることに注意してください。 Out パラメーターとして指定することは、ローカル記録するには、タスクが終了する場合はコミットの準備をするサービスに便利です。</para>
        </param>
        <summary>
          <para>セカンダリ レプリカにプライマリ レプリカから状態の変更をレプリケートし、それらの状態の変更が適用されているクォーラムの受信確認を受信します。</para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />long 型で、操作の LSN。</para>
        </returns>
        <remarks>
          <para>プライマリ レプリカでレプリケーションを実装するオブジェクトを生成する<see cref="T:System.Fabric.IOperation" />経由でレプリケーション ストリームから、セカンダリ レプリカを取得する<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />が続きます<see cref="M:System.Fabric.IOperationStream.GetOperationAsync(System.Threading.CancellationToken)" />です。 </para>
          <para>プライマリ レプリカでは、状態の更新の処理に関連する多くの職務にします。 次の手順では、プライマリ レプリカがレプリケートされ、変更の確認に扱う必要があるイベントの全般的な順序を示します。 </para>
          <para>パート 1: 着信要求の処理: 要求を受け取る: Write(x) – サービスが書き込み要求を受信する x。 CheckArguments –、サービスは、要求の引数をチェックします。 このチェックは、サービスの状態の一貫性を確保に役立ちます。</para>
          <para>現在の状態チェック – サービスは、操作が有効ではし、できますか、またはを実行するかを現在の状態を調べます。 このチェックでは、データの一貫性を確保できます。 サービス コードによって実行されます。</para>
          <para>ロックの取得: サービスが同時に発生してから追加の操作を防ぐために必要なロックを取得する必要があります。 この操作により、分離と一貫性を確保します。</para>
          <para>試行操作 (省略可能) – サービスがローカルで操作を試みることができます。 この手順は、予約し領域の割り当てし、必要なすべての計算を実行します。 この手順では、結果の実際のコミットがすべて含まれています。 この操作は、操作の持続性が向上し、以降の障害は非常に珍しい、します。</para>
          <para>OperationData – を製造、<see cref="T:System.Fabric.OperationData" />オブジェクトは、サービスに提示された Write(x) の表現。 <see cref="T:System.Fabric.OperationData" />オブジェクトには、セカンダリ レプリカにプライマリ レプリカから受信確認で転送する状態の変更が含まれています。 OperationData にサービスを挿入するデータを分割不可能な定義を更新、<see cref="T:System.Fabric.FabricReplicator" />のセカンダリ レプリカに転送します。 作成することに注意してください、<see cref="T:System.Fabric.OperationData" />オブジェクトには、1 つまたは複数のバイト配列が必要です。 決定自体と、状態の変化をシリアル化を介して FabricReplicator にこのバイト数のセットを提供する必要がありますサービス<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。 サービスでは、FabricReplicator に、操作を送信し、戻り値論理のシーケンス番号 (LSN) を受け取ります。 LSN は、操作の id は、し、サービスと操作がすべての場所で同じ順序で常に適用されるように Service Fabric の両方を支援します。サービスは、インフライト操作の順序付きリストで、LSN と共に OperationData を記録する必要があります。 これにより、操作が完了したら、一貫して適用できますが正しい順序で。</para>
          <para>ロックを解除 - 処理または以降の要求の待機を続行します。</para>
          <para>パート 2: 要求を完了して、応答: プライマリ レプリカは、操作が適用されたことを示すコールバックを受信します。 ReplicateAsync は完了です。 このコールバックは、レプリカ セット内のレプリカのクォーラムによる操作が確認されていることを示します。 プライマリ レプリカがこのコールバックを受信すると、次の操作を実行にする必要があります。 </para>
          <para>サービスのインフライトの一覧で ReplicateAsync から返される長い LSN で示されている、対応する操作を見つけて「QuorumAck は」としてマークします。 </para>
          <para>ここで、インフライトの一覧の最初の操作から開始して、移動、リストをローカル コミット操作で、[完了] に指定された受信者、QuorumAck のすべてのローカル状態と、対応する LSN の状態が変更された最初の不完全な操作になるまでマークに変更発生しました。 これにより、順序が保持されている (一貫性) とする操作が実際に適用されています。 これは、以前の持続性と分離の準備の活用します。 注: ほとんどのサービスは、そのためこの最後のコミット LSN 値をキャッシュするのには、その応答、<see cref="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />最大 LSN のため、実際のストアのクエリは不要です。 </para>
          <para>操作は、プライマリ レプリカに正常にコミットされたときに、プライマリ レプリカことができますようになりました呼び出しを開始したクライアントに返信して、インフライトの一覧から、操作を削除します。 [次へ] の受信確認のクォーラム コールバックの待機を続行します。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="T:System.Fabric.FabricTransientException" />再試行可能な例外です。 次のいずれかが原因</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NoWriteQuorum" />レプリケーターが書き込みクォーラムを現在持っていない場合が返されます.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReconfigurationPending" />レプリケーターが保留中の再構成が返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />レプリケーター キューがいっぱいになったときに返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>
            <see cref="T:System.Fabric.FabricNotPrimaryException" />次のいずれかが原因は、</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NotPrimary" />レプリケーターが保留中の再構成が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
            <see cref="T:System.Fabric.FabricObjectClosedException" />次のいずれかが原因は、</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ObjectClosed" />レプリケーターが終了した場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>
            <see cref="T:System.OperationCanceledException" />次のいずれかが原因は、</para>
          <para>E_ABORT レプリケーターが転送レプリケーション操作をキャンセルするとします。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateReplicator.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="abstract member UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="iStateReplicator.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>新しい<see cref="T:System.Fabric.ReplicatorSettings" />更新された資格情報を使用します。</para>
        </param>
        <summary>
          <para>実行時に複製物作成会社設定の変更を有効にします。 変更できる唯一の設定は、セキュリティ資格情報です。 </para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>