<Type Name="IStateProvider" FullName="System.Fabric.IStateProvider">
  <TypeSignature Language="C#" Value="public interface IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProvider" />
  <TypeSignature Language="F#" Value="type IStateProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>サービスが対話するために実装する必要がありますの動作を定義、<see cref="T:System.Fabric.FabricReplicator" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyContext">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyContext () As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyContext : unit -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>作成され、プライマリ レプリカにコンテキストを送信する開かれた後は、セカンダリ レプリカ上のコンテキストを取得します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</para>
        </returns>
        <remarks>
          <para>プライマリ レプリカがコンテキストを分析しを使用して状態を返送<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。</para>
          <para>
            <see cref="M:System.Fabric.IStateProvider.GetCopyContext" />新しく作成された、アイドルなセカンダリ レプリカで呼び出され、非同期的に、プライマリ レプリカとの双方向メッセージ交換を確立するためのメカニズムを提供します。 セカンダリ レプリカは、送信<see cref="T:System.Fabric.OperationData" />オブジェクトをプライマリ レプリカがセカンダリ レプリカでコンテキストを収集する場合の進行状況を判断できます。 プライマリ レプリカは、必要な状態に戻すを送信して応答します。
                参照してください<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />交換の一方のプライマリ レプリカにします。 </para>
          <para>メモリ内のサービスでは、<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは呼び出されません、セカンダリ レプリカの状態は認識されている (空され、状態のすべてが必要)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCopyState">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyState : int64 * System.Fabric.IOperationDataStream -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyState (upToSequenceNumber, copyContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.NamingRules", "SA1305:FieldNamesMustNotUseHungarianNotation", Justification="Not Hungarian notation.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para>経由でコピー ストリーム内に配置する最大最後のシーケンス番号、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />メソッドです。
            この数より大きい Lsn が経由でレプリケーション ストリームの一部として、セカンダリ レプリカに配信される、<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />メソッドです。</para>
        </param>
        <param name="copyContext">
          <para><see cref="T:System.Fabric.IOperationDataStream" />を格納している、<see cref="T:System.Fabric.OperationData" />セカンダリ レプリカによって作成されるオブジェクト。 </para>
        </param>
        <summary>
          <para>プライマリ レプリカのセカンダリ レプリカを作成する必要がある状態を取得します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</para>
        </returns>
        <remarks>
          <para>同様に<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />により、セカンダリ レプリカを使用して、プライマリ レプリカにコンテキストを送信する、 <see cref="T:System.Fabric.IOperationDataStream" />、<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />により、プライマリ レプリカで応答する、<see cref="T:System.Fabric.IOperationDataStream" />です。 ストリームには使用して、セカンダリ レプリカに配信されるオブジェクトが含まれています、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />のメソッド、<see cref="T:System.Fabric.FabricReplicator" />クラスです。 オブジェクトを実装<see cref="T:System.Fabric.IOperation" />し、指定されたデータが含まれています。 </para>
          <para> プライマリ レプリカは、この呼び出しを受け取る、それを作成し、返す別<see cref="T:System.Fabric.IOperationDataStream" />を格納している<see cref="T:System.Fabric.OperationData" />です。 <see cref="T:System.Fabric.OperationData" />セカンダリ レプリカが次々 に提供されているために必要なデータ/状態を表す<paramref name="upToSequenceNumber" />最大 LSN。 どの程度およびセカンダリ レプリカを経由で提供されるコンテキスト情報を使用して送信されるどの状態を持つを特定できる<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドです。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastCommittedSequenceNumber () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetLastCommittedSequenceNumber : unit -&gt; int64" Usage="iStateProvider.GetLastCommittedSequenceNumber " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>取得する最後のシーケンス番号、サービスがコミットされるとも呼ばれる論理シーケンス番号 (LSN)。 </para>
        </summary>
        <returns>
          <para>最後のコミット シーケンス番号を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iStateProvider.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>このレプリカ セット内のレプリカのな書き込みクォーラムが失われていることと、そのためデータが失われる可能性がありますが発生したことを示します。 レプリカ セットは、プライマリ レプリカが含まれているレプリカの大部分で構成されます。 </para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Boolean" />、この通知の処理の一部として状態プロバイダーでの状態が変更されたかどうかを示す</para>
        </returns>
        <remarks>
          <para>Service Fabric ランタイムが、プライマリ レプリカが含まれており、レプリカのクォーラムの障害発生時に新しいプライマリ レプリカと、すぐに、新しいプライマリ レプリカでこのメソッドを呼び出します。 データ損失の可能性が通知をプライマリ レプリカは、外部データ ソースからの状態を復元することもできます。 またはが現在の状態で実行を続行できます。 サービスが、現在の状態で実行され続ける場合は、状態の変更が行われていないことを示す、このメソッドから false を返します。 復元または不完全な作業は、ロールバックなどの状態を変更した場合は true を返します。 True が返される場合はその他のレプリカの状態が不適切な想定されます。
            そのため、Service Fabric ランタイムでは、レプリカ セットから他のレプリカを削除し、それらを再作成します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProvider.UpdateEpochAsync (epoch, previousEpochLastSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>新しい <see cref="T:System.Fabric.Epoch" />。</para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> 以前のエポックの最大シーケンス番号 (LSN)。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>レプリカ セットの構成が変更の理由で変更または、プライマリ レプリカへの変更をしようとしましたが、レプリカを示します。 変更は、エラーまたは以前のプライマリ レプリカの負荷分散のために発生します。 エポックの変更は、特定のプライマリ レプリカによって送信された実際の構成の期間に操作を分割することによって、バリアとして機能します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
        </returns>
        <remarks>
          <para>内の情報、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドは、レプリカが受信した各エポックとそれらに含まれる最大の LSN の一覧、進行状況のベクトルを維持するためにサービスを有効にします。 </para>
          <para>
                現在適用されている最大の LSN と進行状況のベクター データは、レプリカの状態を説明するコピー操作中に送信するセカンダリ レプリカに役立ちます。</para>
          <para>
                コピー操作中に、セカンダリ レプリカから受信した進行状況のベクトルを比較することにより、プライマリ レプリカをセカンダリ レプリカにどのような状態を送信する必要があります、セカンダリ レプリカが最新では、どうかを決定するかどうかと、セカンダリ レプリカfalse の進行状況が行われます。 </para>
          <para>False の進行状況は、セカンダリ レプリカは、以前のエポックの LSN が、プライマリ レプリカは、その進行状況のベクター内にある LSN よりも大きかったレポートを意味します。 </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>