<Type Name="IReliableDictionary2&lt;TKey,TValue&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;TKey,TValue&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableDictionary2&lt;TKey,TValue&gt; : Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;System.Collections.Generic.KeyValuePair&lt;TKey,TValue&gt;&gt;, Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt; where TKey : IComparable&lt;TKey&gt;, IEquatable&lt;TKey&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableDictionary2`2&lt;(class System.IComparable`1&lt;!TKey&gt;, class System.IEquatable`1&lt;!TKey&gt;) TKey, TValue&gt; implements class Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1&lt;valuetype System.Collections.Generic.KeyValuePair`2&lt;!TKey, !TValue&gt;&gt;, class Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2&lt;!TKey, !TValue&gt;, class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableDictionary2(Of TKey, TValue)&#xA;Implements IReliableCollection(Of KeyValuePair(Of TKey, TValue)), IReliableDictionary(Of TKey, TValue)" />
  <TypeSignature Language="F#" Value="type IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt; = interface&#xA;    interface IReliableDictionary&lt;'Key, 'Value (requires 'Key :&gt; IComparable&lt;'Key&gt; and 'Key :&gt; IEquatable&lt;'Key&gt;)&gt;&#xA;    interface IReliableCollection&lt;KeyValuePair&lt;'Key, 'Value&gt;&gt;&#xA;    interface IReliableState" />
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
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.Collections.IReliableDictionary&lt;TKey,TValue&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TKey">信頼性の高いディクショナリ内のキーの型。</typeparam>
    <typeparam name="TValue">
            信頼性の高いディクショナリ内の値の型。</typeparam>
    <summary>
            信頼性の高い永続化されレプリケートされているキー/値ペアのコレクションを表します。
            </summary>
    <remarks>ディクショナリでの操作のコンテキストの外部キーまたは MUST NOT このディクショナリに格納されている値は変換。  両方をお勧め<typeparamref name="TKey" />と<typeparamref name="TValue" />偶発的なデータの破損を回避するために変更できません。
            
            <para>トランザクションは、同時実行の単位です。ユーザーが特定の時点の時間、インフライトの複数のトランザクションを持つことができますが、特定のトランザクションの各 API 呼び出す必要があります、一度に 1 つ。非同期信頼性の高いコレクション メソッドの呼び出しがいつ、 <see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />、同じトランザクションを使用して別のメソッドを呼び出す前に、返されるタスクの完了を待つ必要があります。</para></remarks>
  </Docs>
  <Members>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public long Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Long" />
      <MemberSignature Language="F#" Value="member this.Count : int64" Usage="Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2&lt;'Key, 'Value (requires 'Key :&gt; System.IComparable&lt;'Key&gt; and 'Key :&gt; System.IEquatable&lt;'Key&gt;)&gt;.Count" />
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
            含まれているキー/値ペアの数を取得、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティには、トランザクションのセマンティクスがありません。 プロパティがアクセスした時点で最適な残存作業時間数、ディクショナリ内の項目を表します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateKeyEnumerableAsync (txn As ITransaction) As Task(Of IAsyncEnumerable(Of TKey))" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync txn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <summary>
            経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。
            </summary>
        <returns>信頼性の高いディクショナリ キーの列挙可能です。</returns>
        <remarks>
            信頼性の高いディクショナリから返される enumerarable は安全に読み取りと同時に使用し、ディクショナリに書き込みます。 ディクショナリのスナップショットの一貫したビューを表します。
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。
            <see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。
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
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="enumerationMode">使用する列挙モード。 既定値は順序なしです。</param>
        <summary>
            経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。
            </summary>
        <returns>列挙可能な<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キー。</returns>
        <remarks>
            返された enumerarable、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />を安全に読み取りと同時に使用してディクショナリを書き込みます。 ディクショナリのスナップショットの一貫したビューを表します。
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。
            <see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。
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
    <Member MemberName="CreateKeyEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt; CreateKeyEnumerableAsync (Microsoft.ServiceFabric.Data.ITransaction txn, Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;!TKey&gt;&gt; CreateKeyEnumerableAsync(class Microsoft.ServiceFabric.Data.ITransaction txn, valuetype Microsoft.ServiceFabric.Data.Collections.EnumerationMode enumerationMode, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2.CreateKeyEnumerableAsync(Microsoft.ServiceFabric.Data.ITransaction,Microsoft.ServiceFabric.Data.Collections.EnumerationMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyEnumerableAsync : Microsoft.ServiceFabric.Data.ITransaction * Microsoft.ServiceFabric.Data.Collections.EnumerationMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;'Key&gt;&gt;" Usage="iReliableDictionary2.CreateKeyEnumerableAsync (txn, enumerationMode, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;TKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="txn" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="enumerationMode" Type="Microsoft.ServiceFabric.Data.Collections.EnumerationMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="txn">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="enumerationMode">使用する列挙モード。 既定値は順序なしです。</param>
        <param name="timeout">
            操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。
            </param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。 既定値は None です。</param>
        <summary>
            経由で非同期列挙子を作成、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キーを列挙します。
            </summary>
        <returns>列挙可能な<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />キー。</returns>
        <remarks>
            返された enumerarable、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary2`2" />を安全に読み取りと同時に使用してディクショナリを書き込みます。 ディクショナリのスナップショットの一貫したビューを表します。
            </remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外は、信頼性の高いディクショナリが現時点での読み取りを使用できないことを示します。
            <see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.Primary" />が失われること<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの例でスローされたため、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />は、信頼性の高いコレクションの状態があるまだ一貫性のあります。
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
  </Members>
</Type>