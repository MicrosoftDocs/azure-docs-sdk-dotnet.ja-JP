<Type Name="IReliableCollection&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.Collections.IReliableCollection&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IReliableCollection&lt;T&gt; : Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableCollection`1&lt;T&gt; implements class Microsoft.ServiceFabric.Data.IReliableState" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableCollection(Of T)&#xA;Implements IReliableState" />
  <TypeSignature Language="F#" Value="type IReliableCollection&lt;'T&gt; = interface&#xA;    interface IReliableState" />
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
    <typeparam name="T">コレクション内の要素の型。</typeparam>
    <summary>
      <para>信頼性の高いコレクションを操作するメソッドを定義します。</para>
    </summary>
    <remarks>
      <para>詳細については、信頼性の高いコレクションがわかるように<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">ここ</see>です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.ClearAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ClearAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iReliableCollection.ClearAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>すべての状態を削除、 <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />、レプリケートされ、保持された状態を含むです。</para>
        </summary>
        <returns>
          <para>非同期のクリア操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>この操作を実行しようとするときにスローされます、<cref name="IReliableCollection{T}" />に含まれていない、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロール。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>この操作を指定したタイムアウト時間内に完了できなかったことを示します。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCountAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; GetCountAsync (Microsoft.ServiceFabric.Data.ITransaction tx);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; GetCountAsync(class Microsoft.ServiceFabric.Data.ITransaction tx) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1.GetCountAsync(Microsoft.ServiceFabric.Data.ITransaction)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCountAsync (tx As ITransaction) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="abstract member GetCountAsync : Microsoft.ServiceFabric.Data.ITransaction -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="iReliableCollection.GetCountAsync tx" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
      </Parameters>
      <Docs>
        <param name="tx">
            使用してこの操作を関連付けるトランザクションです。 トランザクションの例を参照して<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-work-with-reliable-collections">ここ</see>です。
            </param>
        <summary>
          <para><see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" /> に格納されている要素の数を取得します。</para>
        </summary>
        <returns>
          <para>要素の数を示す、非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricNotReadableException">
          <para>IReliableCollection が現時点での読み取りを使用できないことを示します。
            すべてのページでこの例外はスローされる<see cref="T:System.Fabric.ReplicaRole" />s。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロールが失われる<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。
            1 つの理由でスローされる可能性が、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />ロールは、信頼性の高いコレクションの状態があるまだ一貫性のあります。</para>
        </exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">
          <para>この操作を実行しようとするときにスローされます、<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />に含まれていない、<see cref="F:System.Fabric.ReplicaRole.Primary" />ロール。
            使用 IReliableCollection の実装によってセカンダリ レプリカから、場合によっては、読み取りなどの操作を実行できます。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>