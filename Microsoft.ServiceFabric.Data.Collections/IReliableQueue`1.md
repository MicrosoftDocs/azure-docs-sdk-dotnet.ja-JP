<Type Name="IReliableQueue&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableQueue&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableQueue&lt;T&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableQueue`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;!T&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableQueue(Of T)&#xA;Implements IReliableCollection(Of T)" />
  <TypeSignature Language="F#" Value="type IReliableQueue&lt;'T&gt; = interface&#xA;    interface IReliableCollection&lt;'T&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">信頼性の高いキューに格納されている要素の型。</typeparam>
    <summary>
            信頼性の高い、先入れ先出しのコレクションを表します永続化され、レプリケートされるオブジェクト。
            </summary>
    <remarks>
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
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!T&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (tx As ITransaction) As Task(Of IAsyncEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'T&gt;&gt;" Usage="iReliableQueue.CreateEnumerableAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <summary>
            経由で列挙可能な非同期を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />です。
            </summary>
        <returns>すべての値を表す IEnumerable です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。
            <cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。
            1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnqueueAsync (tx As ITransaction, item As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item)" />
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
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="item">キューの末尾に追加するオブジェクト。 参照型の場合は、値を null にできます。</param>
        <summary>
            信頼性の高いキューの末尾にオブジェクトを追加します。
            </summary>
        <returns>非同期のエンキュー操作を表すタスク。</returns>
        <remarks>再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnqueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnqueueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, T item, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task EnqueueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !T item, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnqueueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'T * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableQueue.EnqueueAsync (tx, item, timeout, cancellationToken)" />
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
        <Parameter Name="item" Type="T" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="item">キューの末尾に追加するオブジェクト。 参照型の場合は、値を null にできます。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いキューの末尾にオブジェクトを追加します。
            </summary>
        <returns>非同期のエンキュー操作を表すタスク。</returns>
        <remarks>再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryDequeueAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync tx" />
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
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <summary>
            削除して、信頼性の高いキューの先頭にオブジェクトを取得しようとします。
            </summary>
        <returns>
            表す非同期のタスクには、操作がキューから削除します。 タスクの結果の組は、その場合、オブジェクトが削除されたかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryDequeueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryDequeueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryDequeueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryDequeueAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryDequeueAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryDequeueAsync (tx, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            削除して、信頼性の高いキューの先頭にオブジェクトを取得しようとします。
            </summary>
        <returns>
            表す非同期のタスクには、操作がキューから削除します。 タスクの結果の組は、その場合、オブジェクトが削除されたかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>再試行可能な例外は、このメソッドによってスローされた場合は、トランザクションを破棄する勧め<paramref name="tx" />し、新しいトランザクションでもう一度やり直してください。</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<cref name="IReliableQueue{T}" />に含まれていない<cref name="ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryPeekAsync (tx As ITransaction) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync tx" />
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
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <summary>
            削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。
            </summary>
        <returns>
            非同期操作を表すタスク。 タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。
            <cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。
            1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode)" />
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
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <summary>
            削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。
            </summary>
        <returns>
            非同期操作を表すタスク。 タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。
            <cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。
            1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, timeout, cancellationToken)" />
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
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。
            </summary>
        <returns>
            非同期操作を表すタスク。 タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。
            <cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。
            1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TryPeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryPeekAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!T&gt;&gt; TryPeekAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1.TryPeekAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryPeekAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iReliableQueue.TryPeekAsync (tx, lockMode, timeout, cancellationToken)" />
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
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            削除することがなく、信頼性の高いキューの先頭からオブジェクトを返すしようとしています。
            </summary>
        <returns>
            非同期操作を表すタスク。 タスクの結果の組は、その場合、キューの先頭にオブジェクトが見つかったかどうかを示すオブジェクトを使用して、します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外には、ことを示します、<cref name="IReliableQueue{T}" />時点で読み取りを処理できません。
            <cref name="FabricNotReadableException" />すべてのページでスローされる可能性<cref name="ReplicaRole" />s。
            1 つの例でスローされたため、<cref name="ReplicaRole.Primary" />が失われること<cref name="IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<cref name="ReplicaRole.ActiveSecondary" />は、信頼性の高いキューの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>