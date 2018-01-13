<Type Name="IReliableConcurrentQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableConcurrentQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableConcurrentQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableConcurrentQueue(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableConcurrentQueue&lt;'T&gt; = interface&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">
            スリム信頼性の高いキューに格納されている値の型。
            </typeparam>
    <summary>
      <para>
            信頼性の高いベスト エフォート先入れ先出しの順序を永続化された、レプリケートされた値のコレクションを表します。
            </para>
    </summary>
    <remarks>
      <para>
            代わりとして用意されています<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />ワークロードの厳密な順序付けが行われていない必要な場合として、順序付けの制約を緩和すること同時実行が大幅に向上できます。  <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />1 つずつ、最大同時コンシューマーとプロデューサーを制限するときに<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />このような制限はありません。
            </para>
      <para>
        <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />その他の信頼できるデータ構造体として同じトランザクション分離のセマンティクスを提供していません。  個々 の操作とプロパティを参照してください (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />と<see cref="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />) どのような分離の詳細については、存在する場合、それらを提供します。
            </para>
      <para>
            値をキューで比較的短時間になることが必要つまりの送信 (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) 率は、受信以上になると (<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />) 率。  この期待値を違反すると、システムのパフォーマンスが悪化する可能性があります。  容量に達した後に受信キューに入れますを調整する計画的なキュー容量に制約は、このプロパティを維持するために役立ちます。
            プロパティを使用する方法を示します。
            </para>
      <para>
            ように、要素の順序が厳密に限りませんが、キュー内の 2 つの値の順序について想定する必要がありますは行われません。  ベスト エフォート先入れ先出しの順序付けは、提供公平性です。値が、キューに費やす時間は、障害発生率を関連付ける必要があります (エラー変わることがあります、キューの順序) およびデキュー レートがエンキュー率ではありません。
            </para>
      <para>
        <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ただし、ピーク操作を提供しません結合して<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />と<see cref="M:Microsoft.ServiceFabric.Data.ITransaction.Abort" />同じセマンティクスを実現できます。  参照してください<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />追加の詳細と例です。
            </para>
      <para>
            このキューに格納されている値は、キューでの操作のコンテキスト外変換します。 強くお勧めする<typeparamref name="T" />偶発的なデータの破損を回避するために変更できません。
            </para>
      <para>
            トランザクションは、同時実行の単位: ユーザーは、時間の特定の時点インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つです。
            すべての信頼性の高いコレクション Api をトランザクションでは、タスクを返すには、待機中の 1 つずつをする必要があります。
            <seealso cref="T:Microsoft.ServiceFabric.Data.ITransaction" /></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue&lt;'T&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
             値の数を取得、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />です。
             </para>
        </summary>
        <value>値の数、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />です。</value>
        <remarks>
          <para>
             この数に現在表示されている値の数を表します<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />です。  コミットされていないキューに登録でが、コミットされていない Dequeues はカウントを減らし、カウントは向上しません。
             </para>
          <para>
             この API は、トランザクション パラメーターを受け取らないに注意してください。  以降の効果<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />は他のトランザクションから分離されません、カウントすることもできません他のトランザクションから分離します。  
             </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">レプリカを現在読み取れません。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</exception>
        <example>
             この例では、キャンセル トークンが取り消されるまで、無限、キューの数を監視する方法を示します。
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                 // Assumption: values are being enqueued/dequeued in another place (e.g. the communication listener).
                 var observer = Task.Run(
                     async () =>
                         {
                             while (true)
                             {
                                 cancellationToken.ThrowIfCancellationRequested();
            
                                 try
                                 {
                                     Console.WriteLine("Count: " + concurrentQueue.Count);
                                 }
                                 catch (FabricNotReadableException e)
                                 {
                                     // Retry until the queue is readable or a different exception is thrown.
                                     Console.WriteLine("Queue is not readable, retrying the observation: " + e);
                                 }
                                 catch (FabricObjectClosedException e)
                                 {
                                     // Gracefully exit as this is happening due to replica close.
                                     Console.WriteLine("Replica is closing, stopping observer: " + e);
                                     return;
                                 }
                                 
                                 await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                             }
                         },
                     cancellationToken);
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T value, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T value, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task" Usage="iReliableConcurrentQueue.EnqueueAsync (tx, value, cancellationToken, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="value">キューの末尾に追加する値。 参照型の場合は、値を null にできます。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定では、 <see cref="P:System.Threading.CancellationToken.None" />です。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 既定値は null です。  Null が渡された場合は、既定のタイムアウトが使用されます。</param>
        <summary>
          <para>
             ステージの値がキューにエンキューします。
             </para>
        </summary>
        <returns>非同期のエンキュー操作を表すタスク。</returns>
        <remarks>
             A<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作は、対象の任意の値を返すことはできません、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />まだコミットされていません。
             これで、値がエンキュー; トランザクションが含まれますその結果、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />読み取り、書き込みをサポートしていません。
             </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">レプリカは不要になった<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">レプリカを現在読み取れません。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</exception>
        <exception cref="T:System.Fabric.FabricTransientException">レプリカは、一時的なエラーを説明しました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.Fabric.FabricException">レプリカは、上記で定義された型以外の非再試行可能エラーを説明しました。 クリーンアップと rethrow 例外</exception>
        <exception cref="T:System.TimeoutException">
             操作は、指定したタイムアウト時間内に完了できませんでした。  トランザクションを中止するかし、再試行する、新しいトランザクションを作成する必要があります。
             </exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.OperationCanceledException">使用して、操作が取り消されました<paramref name="cancellationToken" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
             メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
             例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
             この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
             </exception>
        <example>
             この例を使用する方法を示しています。<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />エンキュー再試行の値にします。
             <code><![CDATA[
             protected override async Task RunAsync(CancellationToken cancellationToken)
             {
                 var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                 while (true)
                 {
                     cancellationToken.ThrowIfCancellationRequested();
             
                     try
                     {
                         using (var tx = this.StateManager.CreateTransaction())
                         {
                             await concurrentQueue.EnqueueAsync(tx, 12L, cancellationToken);
                             await tx.CommitAsync();
            
                             return;
                         }
                     }
                     catch (TransactionFaultedException e)
                     {
                         // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
                         // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
                         Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
                     }
                     catch (FabricNotPrimaryException e)
                     {
                         // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
                         // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                         return;
                     }
                     catch (FabricNotReadableException e)
                     {
                         // Retry until the queue is readable or a different exception is thrown.
                         Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                     }
                     catch (FabricObjectClosedException e)
                     {
                         // Gracefully exit RunAsync as this is happening due to replica close.
                         // If instead enqueue was being executed as part of a client request, the client would be signaled to re-resolve.
                         Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                         return;
                     }
                     catch (TimeoutException e)
                     {
                         Console.WriteLine("Encountered TimeoutException during EnqueueAsync, retrying the transaction: " + e);
                     }
                     catch (FabricTransientException e)
                     {
                         // Retry until the queue is writable or a different exception is thrown.
                         Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                     }
            
                     // Delay and retry.
                     await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                 }
             }
             ]]></code></example>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, System.Threading.CancellationToken cancellationToken = null, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.Threading.CancellationToken cancellationToken, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * System.Threading.CancellationToken * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableConcurrentQueue.TryDequeueAsync (tx, cancellationToken, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定では、 <see cref="P:System.Threading.CancellationToken.None" />です。</param>
        <param name="timeout">操作が完了するまで待機する時間の量。 既定値は null です。  Null が渡された場合は、既定のタイムアウトが使用されます。</param>
        <summary>
          <para>
            仮キューからの値をデキューします。 キューが空の場合は、使用可能になるアイテム dequeue 操作は待機します。
            </para>
        </summary>
        <returns>
            表す非同期のタスクには、操作がキューから削除します。 タスクの結果は T 型の ConditionalValue場合は、値は、許容時間内デキューされました、返す、ConditionalValue false として HasValue、それ以外の場合、返さ true として HasValue と型 T のキューから取り出されたアイテムとして値を持つ ConditionalValue
            </returns>
        <remarks>
          <para>
            中に<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />対象の値を返すことができますのみ、対応する<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />コミットされ、<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作が互いから分離されていません。  トランザクションには、値がデキュー、他のトランザクション、キューから削除できませんがその他の値をキューからブロックされていません。
            </para>
          <para>
            ときに、トランザクション、または 1 つまたは複数を含むトランザクション<see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" />操作が中止されて、デキューされる値を任意の順序でキューの先頭に追加されます。  これにより、これらの値がデキューのため、すぐに再度厳密順序を適用することがなく、データ構造の公平性を向上させるよう (で許可される同時実行を減らすことが必要<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />)。
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">レプリカは不要になった<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">レプリカを現在読み取れません。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException"><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1" />ランタイムによって終了されました。</exception>
        <exception cref="T:System.Fabric.FabricTransientException">レプリカは、一時的なエラーを説明しました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.Fabric.FabricException">レプリカは、上記で定義された型以外の非再試行可能エラーを説明しました。 クリーンアップと rethrow 例外</exception>
        <exception cref="T:System.TimeoutException">
            操作は、指定したタイムアウト時間内に完了できませんでした。  トランザクションを中止するかし、再試行する、新しいトランザクションを作成する必要があります。
            </exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。 この例外を処理しません。</exception>
        <exception cref="T:System.OperationCanceledException">使用して、操作が取り消されました<paramref name="cancellationToken" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <example>
            この例では、デキューし、キャンセル トークンが取り消されるまで、再試行で無限にログインする方法を示します。  
            <code><![CDATA[
            protected override async Task RunAsync(CancellationToken cancellationToken)
            {
                var concurrentQueue = await this.StateManager.GetOrAddAsync<IReliableConcurrentQueue<long>>(new Uri("fabric:/concurrentQueue"));
            
                // Assumption: values are being enqueued by another source (e.g. the communication listener).
                while (true)
                {
                    cancellationToken.ThrowIfCancellationRequested();
            
                    try
                    {
                        using (var tx = this.StateManager.CreateTransaction())
                        {
                            var dequeueOutput = await concurrentQueue.TryDequeueAsync(tx, cancellationToken, TimeSpan.FromMilliseconds(100));
                            await tx.CommitAsync();
            
                            if (dequeueOutput.HasValue)
                            {
                                Console.WriteLine("Dequeue # " + dequeueOutput);
                            }
                            else
                            {
                                Console.WriteLine("Could not dequeue in the given time");
                            }
                        }
                    }
                    catch (TransactionFaultedException e)
                    {
                        // This indicates that the transaction was internally faulted by the system. One possible cause for this is that the transaction was long running
                        // and blocked a checkpoint. Increasing the "ReliableStateManagerReplicatorSettings.CheckpointThresholdInMB" will help reduce the chances of running into this exception
                        Console.WriteLine("Transaction was internally faulted, retrying the transaction: " + e);
                    }
                    catch (FabricNotPrimaryException e)
                    {
                        // Gracefully exit RunAsync as the new primary should have RunAsync invoked on it and continue work.
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
                        Console.WriteLine("Replica is not primary, exiting RunAsync: " + e);
                        return;
                    }
                    catch (FabricNotReadableException e)
                    {
                        // Retry until the queue is readable or a different exception is thrown.
                        Console.WriteLine("Queue is not readable, retrying the transaction: " + e);
                    }
                    catch (FabricObjectClosedException e)
                    {
                        // Gracefully exit RunAsync as this is happening due to replica close.
                        // If instead dequeue was being executed as part of a client request, the client would be signaled to re-resolve.
                        Console.WriteLine("Replica is closing, exiting RunAsync: " + e);
                        return;
                    }
                    catch (TimeoutException e)
                    {
                        Console.WriteLine("Encountered TimeoutException during DequeueAsync, retrying the transaction: " + e);
                    }
                    catch (FabricTransientException e)
                    {
                        // Retry until the queue is writable or a different exception is thrown.
                        Console.WriteLine("Queue is currently not writable, retrying the transaction: " + e);
                    }
            
                    // Delay and retry.
                    await Task.Delay(TimeSpan.FromMilliseconds(100), cancellationToken);
                }
            }
            ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>