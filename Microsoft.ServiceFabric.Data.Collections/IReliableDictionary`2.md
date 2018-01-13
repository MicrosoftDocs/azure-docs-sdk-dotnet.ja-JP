<Type Name="IReliableDictionary&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue))" />
  <TypeSignature Language="F#" Value="type IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TKey">
      <Constraints>
        <InterfaceName>System.IComparable&lt;TKey&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;TKey&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TValue" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey">信頼性の高いディクショナリ内のキーの型。</typeparam>
    <typeparam name="TValue">信頼性の高いディクショナリ内の値の型。</typeparam>
    <summary>
      <para>信頼性の高い永続化されレプリケートされているキー/値ペアのコレクションを表します。</para>
    </summary>
    <remarks>
      <para>ディクショナリでの操作のコンテキストの外部キーまたは MUST NOT このディクショナリに格納されている値は変換。 両方をお勧め<typeparamref name="TKey" />と<typeparamref name="TValue" />偶発的なデータの破損を回避するために変更できません。
            参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>よくある落とし穴をします。</para>
      <para>トランザクションは、同時実行の単位です。 ユーザーが特定の時点の時間、インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つ。
            非同期信頼性の高いコレクション メソッドの呼び出しがいつ、 <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />、同じトランザクションを使用して別のメソッドを呼び出す前に、返されるタスクの完了を待つ必要があります。 トランザクションの例を参照して<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加されるキー。</param>
        <param name="value">追加する値。 参照型の場合は、値を null にできます。</param>
        <summary>
            信頼性の高いディクショナリに、指定したキー/値ペアを追加します。
            </summary>
        <returns>表す非同期のタスクは、操作を追加します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">同じキーを持つ値は、信頼性の高いディクショナリに既に存在します。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.AddAsync (tx, key, value, timeout, cancellationToken)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加されるキー。</param>
        <param name="value">追加する値。 参照型の場合は、値を null にできます。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリに、指定したキー/値ペアを追加します。
            </summary>
        <returns>表す非同期のタスクは、操作を追加します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">同じキーを持つ値は、信頼性の高いディクショナリに既に存在または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValueFactory As Func(Of TKey, TValue), updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加するキーまたは値を更新するキー。</param>
        <param name="addValueFactory">キーが存在しない場合に、値を生成するために使用される関数。</param>
        <param name="updateValueFactory">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</param>
        <summary>
            キーが既に存在しない場合に、信頼性の高い辞書にキー/値ペアを追加するか、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新する、指定された関数を使用します。
            </summary>
        <returns>
            非同期の追加または更新操作を表すタスク。 タスクの結果は、キーの新しい値です。 これは、なります、addValueFactory の結果 (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="addValueFactory" />が null、または<paramref name="updateValueFactory" />が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddOrUpdateAsync (tx As ITransaction, key As TKey, addValue As TValue, updateValueFactory As Func(Of TKey, TValue, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加するキーまたは値を更新するキー。</param>
        <param name="addValue">キーが存在しない場合に追加する値。 参照型の場合は、値を null にできます。</param>
        <param name="updateValueFactory">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</param>
        <summary>
            キーが既に存在しない場合、キーが既に存在する場合、指定された関数を使用して、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>
            非同期の追加または更新操作を表すタスク。 タスクの結果は、キーの新しい値です。 これは、されますか、addValue (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="updateValueFactory" />が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; addValueFactory, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; addValueFactory, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValueFactory, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加するキーまたは値を更新するキー。</param>
        <param name="addValueFactory">キーが存在しない場合に、値を生成するために使用される関数。</param>
        <param name="updateValueFactory">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            キーが既に存在しない場合に、信頼性の高い辞書にキー/値ペアを追加するか、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新する、指定された関数を使用します。
            </summary>
        <returns>
            非同期の追加または更新操作を表すタスク。 タスクの結果は、キーの新しい値です。 これは、なります、addValueFactory の結果 (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="addValueFactory" />が null、または<paramref name="updateValueFactory" />が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; AddOrUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue addValue, Func&lt;TKey,TValue,TValue&gt; updateValueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; AddOrUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue addValue, class System.Func`3&lt;!TKey, !TValue, !TValue&gt; updateValueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.AddOrUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.Func{`0,`1,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * Func&lt;'Key, 'Value, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.AddOrUpdateAsync (tx, key, addValue, updateValueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="addValue" Type="TValue" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;TKey,TValue,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加するキーまたは値を更新するキー。</param>
        <param name="addValue">キーが存在しない場合に追加する値。 参照型の場合は、値を null にできます。</param>
        <param name="updateValueFactory">キーの既存の値に基づいて、既存のキーの新しい値を生成するために使用される関数。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            キーが既に存在しない場合、キーが既に存在する場合、指定された関数を使用して、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>
            非同期の追加または更新操作を表すタスク。 タスクの結果は、キーの新しい値です。 これは、されますか、addValue (キーが存在しない場合) か updateValueFactory の結果 (キーが存在) 場合。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="updateValueFactory" />が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ClearAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.ClearAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリからすべてのキーと値を削除します。
            </summary>
        <returns>非同期のクリア操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function ContainsKeyAsync (tx As ITransaction, key As TKey) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">信頼性の高いディクショナリ内で検索するキー。</param>
        <summary>
            信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、キーが存在するかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">信頼性の高いディクショナリ内で検索するキー。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <summary>
            信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、キーが存在するかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">信頼性の高いディクショナリ内で検索するキー。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、キーが存在するかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsKeyAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsKeyAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.ContainsKeyAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsKeyAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.ContainsKeyAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">信頼性の高いディクショナリ内で検索するキー。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリに指定したキーが含まれているかどうかを判断します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、キーが存在するかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of KeyValuePair(Of TKey, TValue)))" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <summary>
            非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。
            </summary>
        <returns>
          <para>表す非同期のタスクは、列挙可能な操作を作成します。 タスクの結果は、信頼性の高い辞書の列挙子です。</para>
        </returns>
        <remarks>
          <para>返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。
            スナップショットの一貫したビューを表します。 なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。 使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="enumerationMode">使用する列挙モード。 既定値は順序なしです。 列挙体の順序付けは昇順のみです。 </param>
        <summary>
            非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。
            </summary>
        <returns>
          <para>表す非同期のタスクは、列挙可能な操作を作成します。 タスクの結果は、信頼性の高い辞書の列挙子です。</para>
        </returns>
        <remarks>
          <para>返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。
            スナップショットの一貫したビューを表します。 なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。 使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt; CreateEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Func&lt;TKey,bool&gt; filter, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;&gt; CreateEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, class System.Func`2&lt;!TKey, bool&gt; filter, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.CreateEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Func{`0,System.Boolean},Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Func&lt;'Key, bool (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;'Key, 'Value&gt;&gt;&gt;" Usage="iReliableDictionary.CreateEnumerableAsync (txn, filter, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="filter" Type="System.Func&lt;TKey,System.Boolean&gt;" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="filter">キーに基づく列挙型に含めるキーと値のペアをフィルター処理する述語。</param>
        <param name="enumerationMode">使用する列挙モード。 既定値は順序なしです。 列挙体の順序付けは昇順のみです。</param>
        <summary>
            非同期の列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />です。
            </summary>
        <returns>
          <para>表す非同期のタスクは、列挙可能な操作を作成します。 タスクの結果は、信頼性の高い辞書の列挙子です。</para>
        </returns>
        <remarks>
          <para>返された列挙子は、安全に読み取りと同時に使用し、信頼性の高いディクショナリに書き込みます。
            スナップショットの一貫したビューを表します。 なお、<see cref="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />を列挙するために、返された IAsyncEnumerable に呼び出される必要があります。 使用例がわかるように<see href="https://github.com/Azure-Samples/service-fabric-dotnet-web-reference-app/blob/master/ReferenceApp/Inventory.Service/InventoryService.cs">ここ</see>です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DictionaryChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt; DictionaryChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2&lt;!TKey, !TValue&gt;&gt; DictionaryChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.DictionaryChanged" />
      <MemberSignature Language="VB.NET" Value="Event DictionaryChanged As EventHandler(Of NotifyDictionaryChangedEventArgs(Of TKey, TValue)) " />
      <MemberSignature Language="F#" Value="member this.DictionaryChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " Usage="member this.DictionaryChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;'Key, 'Value&gt;&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs&lt;TKey,TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            信頼性の高いディクショナリが変更されたときに発生します。
            たとえば、更新プログラムの追加または削除の項目。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, valueFactory As Func(Of TKey, TValue)) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="valueFactory">キーの値を生成するために使用される関数。</param>
        <summary>
            キーが既に存在しない場合に指定された関数を使用して、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>
            表す非同期のタスクは、操作を追加します。 タスクの結果は、キーの値です。 これは、キーが、信頼性の高いディクショナリに既に場合は、キーの既存の値またはキーが信頼性の高いディクショナリ内でない場合は valueFactory から返されたキーの新しい値のいずれかになります。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="valueFactory" />が null です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of TValue)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="value">キーがまだ存在しない場合に追加する値。</param>
        <summary>
            キーが既に存在しない場合は、信頼性の高い辞書にキー/値ペアを追加します。
            キーが存在する場合は、値に更新プログラムは作成されません。
            </summary>
        <returns>
            表す非同期のタスクは、操作を追加します。 タスクの結果は、キーの値です。 これは、場合は、キーが、信頼性の高いディクショナリに既にキーの既存の値または新しい値のいずれか場合なりますキーは、信頼性の高いディクショナリではありませんでした。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Func&lt;TKey,TValue&gt; valueFactory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, class System.Func`2&lt;!TKey, !TValue&gt; valueFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Func{`0,`1},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Func&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, valueFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="valueFactory" Type="System.Func&lt;TKey,TValue&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="valueFactory">キーの値を生成するために使用される関数。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            キーが既に存在しない場合に指定された関数を使用して、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>
            表す非同期のタスクは、操作を追加します。 タスクの結果は、キーの値です。 これは、キーが、信頼性の高いディクショナリに既に場合は、キーの既存の値またはキーが信頼性の高いディクショナリ内でない場合は valueFactory から返されたキーの新しい値のいずれかになります。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化できませんまたは<paramref name="valueFactory" />が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TValue&gt; GetOrAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TValue&gt; GetOrAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.GetOrAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'Value&gt;" Usage="iReliableDictionary.GetOrAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TValue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="value">キーがまだ存在しない場合に追加する値。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            キーが既に存在しない場合は、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>
            表す非同期のタスクは、操作を追加します。 タスクの結果は、キーの値です。 これは、場合は、キーが、信頼性の高いディクショナリに既にキーの既存の値または新しい値のいずれか場合なりますキーは、信頼性の高いディクショナリではありませんでした。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="RebuildNotificationAsyncCallback">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`3&lt;class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2&lt;!TKey, !TValue&gt;, class System.Threading.Tasks.Task&gt; RebuildNotificationAsyncCallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.RebuildNotificationAsyncCallback" />
      <MemberSignature Language="VB.NET" Value="Public Property RebuildNotificationAsyncCallback As Func(Of IReliableDictionary(Of TKey, TValue), NotifyDictionaryRebuildEventArgs(Of TKey, TValue), Task)" />
      <MemberSignature Language="F#" Value="member this.RebuildNotificationAsyncCallback : Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value&gt;, Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;'Key, 'Value&gt;, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.RebuildNotificationAsyncCallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;,Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs&lt;TKey,TValue&gt;,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            信頼性の高いディクショナリがコピー、復元または復旧中に再構築されるときに呼び出される関数。
            </summary>
        <value>
            非同期の再構築の通知関数。 関数は、IReliableDictionary and NotifyDictionaryRebuildEventArgs トークン内の取得しを再構築の通知の非同期処理を表すタスクを返します。
            </value>
        <remarks>
          <see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryChangedEventArgs`2" />このコールバック内でのみ使用できます。
            非同期のコールバックが完了すると、<see cref="T:Microsoft.ServiceFabric.Data.Notifications.NotifyDictionaryRebuildEventArgs`2" />は無効になります。 詳細については、<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-notifications">ここを</see>を参照してください。 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetAsync (tx As ITransaction, key As TKey, value As TValue) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">キー値を更新する必要があります。</param>
        <param name="value">指定した要素の値を置き換える値<paramref name="key" />です。</param>
        <summary>
            キーが既に存在しない場合、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>非同期更新操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="key" />信頼性の高いディクショナリではありません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="SetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.SetAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iReliableDictionary.SetAsync (tx, key, value, timeout, cancellationToken)" />
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
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">キー値を更新する必要があります。</param>
        <param name="value">指定した要素の値を置き換える値<paramref name="key" />です。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            キーが既に存在しない場合、キーが既に存在する場合は、信頼性の高いディクショナリのキー/値ペアを更新、信頼性の高い辞書にキー/値ペアを追加します。
            </summary>
        <returns>非同期更新操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="key" />ディクショナリに存在しない、信頼性の高い、または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddAsync (tx As ITransaction, key As TKey, value As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="value">追加する要素の値。 参照型の場合は、値を null にできます。</param>
        <summary>
            信頼性の高いディクショナリに、指定したキーと値を追加しようとしています。
            </summary>
        <returns>表す非同期のタスクは、操作を追加します。 タスクの結果は、キー/値ペアが追加されたかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryAddAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryAddAsync (tx, key, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="value" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">追加する要素のキー。</param>
        <param name="value">追加する要素の値。 参照型の場合は、値を null にできます。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリに、指定したキーと値を追加しようとしています。
            </summary>
        <returns>表す非同期のタスクは、操作を追加します。 タスクの結果は、キー/値ペアが追加されたかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetValueAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">取得する値のキー。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。
            </summary>
        <returns>
            非同期の読み取り操作を表すタスク。 タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">取得する値のキー。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。
            </summary>
        <returns>
            非同期の読み取り操作を表すタスク。 タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">取得する値のキー。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。
            </summary>
        <returns>
            非同期の読み取り操作を表すタスク。 タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetValueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryGetValueAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryGetValueAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype Microsoft.ServiceFabric.Data.Collections.LockMode lockMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryGetValueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,Microsoft.ServiceFabric.Data.Collections.LockMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetValueAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * Microsoft.ServiceFabric.Data.Collections.LockMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryGetValueAsync (tx, key, lockMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="lockMode" Type="Microsoft.ServiceFabric.Data.Collections.LockMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">取得する値のキー。</param>
        <param name="lockMode">この読み取り操作に使用するロックの種類です。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに関連付けられている値を取得しようとしています。
            </summary>
        <returns>
            非同期の読み取り操作を表すタスク。 タスクの結果の組は、その場合は、信頼性の高いディクショナリのキーが見つかったかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            IReliableDictionary が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。
            </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryRemoveAsync (tx As ITransaction, key As TKey) As Task(Of ConditionalValue(Of TValue))" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">削除する要素のキー。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに値を削除しようとしています。
            </summary>
        <returns>
            非同期の削除操作を表すタスク。 タスクの結果の組は、その場合、信頼性の高いディクショナリからキーが削除されたかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt; TryRemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!TValue&gt;&gt; TryRemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryRemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'Value&gt;&gt;" Usage="iReliableDictionary.TryRemoveAsync (tx, key, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;TValue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">削除する要素のキー。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            信頼性の高いディクショナリから指定されたキーに値を削除しようとしています。
            </summary>
        <returns>
            非同期の削除操作を表すタスク。 タスクの結果の組は、その場合、信頼性の高いディクショナリからキーが削除されたかどうかを示す、値。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryUpdateAsync (tx As ITransaction, key As TKey, newValue As TValue, comparisonValue As TValue) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">値を <paramref name="comparisonValue" /> と比較し、場合によっては置き換えるキー。</param>
        <param name="newValue">比較した結果が等しい場合に、指定した <paramref name="key" /> を持つ要素の値を置き換える値。</param>
        <param name="comparisonValue">指定した <paramref name="key" /> を持つ要素の値と比較する値。</param>
        <summary>
            指定したキーの既存の値と指定した値を比較し、等しい場合は別の値でキーを更新します。
            </summary>
        <returns>非同期更新操作を表すタスク。 タスクの結果は、オブジェクトが更新されたかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryUpdateAsync (Microsoft.ServiceFabric.Data.ITransaction tx, TKey key, TValue newValue, TValue comparisonValue, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryUpdateAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, !TKey key, !TValue newValue, !TValue comparisonValue, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2.TryUpdateAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,`1,`1,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryUpdateAsync : Microsoft.ServiceFabric.Data.ITransaction * 'Key * 'Value * 'Value * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iReliableDictionary.TryUpdateAsync (tx, key, newValue, comparisonValue, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="key" Type="TKey" />
        <Parameter Name="newValue" Type="TValue" />
        <Parameter Name="comparisonValue" Type="TValue" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="key">値を <paramref name="comparisonValue" /> と比較し、場合によっては置き換えるキー。</param>
        <param name="newValue">比較した結果が等しい場合に、指定した <paramref name="key" /> を持つ要素の値を置き換える値。</param>
        <param name="comparisonValue">指定した <paramref name="key" /> を持つ要素の値と比較する値。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            指定したキーの既存の値と指定した値を比較し、等しい場合は別の値でキーを更新します。
            </summary>
        <returns>非同期更新操作を表すタスク。 タスクの結果は、オブジェクトが更新されたかどうかを示します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="key" />が null またはシリアル化することはできません。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="timeout" /> が負の値です。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">ときにスローされる例外、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高いディクショナリが閉じられたか、削除されたことを示します。</exception>
      </Docs>
    </Member>
  </Members>
</Type>