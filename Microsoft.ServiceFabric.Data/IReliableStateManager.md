<Type Name="IReliableStateManager" FullName="Microsoft.ServiceFabric.Data.IReliableStateManager">
  <TypeSignature Language="C#" Value="public interface IReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReliableStateManager implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState)" />
  <TypeSignature Language="F#" Value="type IReliableStateManager = interface&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            すべて管理<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />サービス レプリカにします。
            サービス内の各レプリカは、独自の状態マネージャーであるため、独自のセット<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.ITransaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As ITransaction" />
      <MemberSignature Language="F#" Value="abstract member CreateTransaction : unit -&gt; Microsoft.ServiceFabric.Data.ITransaction" Usage="iReliableStateManager.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.ITransaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            作成し、原子的に実行する操作をグループ化に使用できる新しいトランザクションを開始します。
            </summary>
        <returns>新しいトランザクションです。</returns>
        <remarks>
            操作は、トランザクションに渡すことによって追加されます、<see cref="T:Microsoft.ServiceFabric.Data.ITransaction" />信頼性の高い状態メソッド内のオブジェクトします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できないか、既存の<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.GetOrAddAsync (tx, name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="tx" Type="Microsoft.ServiceFabric.Data.ITransaction" />
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            指定する場合、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />型、クラス型またはインターフェイス型のいずれかを要求することがあります。
            <para>クラスの種類を指定する場合、システムはその型のインスタンスを返すしようとします。その型のインスタンスをインスタンス化できない場合 (抽象クラス、適切なコンス トラクターがないなど)、ArgumentException をスローします。</para><para>インターフェイス型を指定すると、マネージャーは具象型にインターフェイスを解決しようとします。型のマッピングが、ユーザーが指定されている場合、このメソッドは、(サポートされていない) 型を解決するのには、ユーザー指定のマッピングが使用されます。型のマッピングが、ユーザーが指定されていない場合、このメソッドは指定されたインターフェイスの既定の実装を選択します。指定されたインターフェイス型には、既定の実装はありません。 または型のユーザー指定のマッピングが指定されていない、種類が無効、このメソッドは ArgumentException をスローします。</para></typeparam>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            取得、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と、指定した名前が存在する場合、または 1 つ作成が既に存在しない場合は、それを取得します。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態のインスタンスです。</returns>
        <remarks>
            これは、分割不可能な操作です。 ときに、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />を作成する必要がありますまたはいずれかを完了し、正常に戻り、作成できません。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException">型のインスタンス<typeparamref name="T" />を作成できない既存または<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスの型ではありません<typeparamref name="T" />、または<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 状態が永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 状態が永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
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
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name)" />
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
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前がありません。</exception>
        <exception cref="T:System.TimeoutException">既定のタイムアウト以内に完了する操作が失敗しました。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 状態が永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (name, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 状態が永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * string * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
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
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveAsync : Microsoft.ServiceFabric.Data.ITransaction * Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="iReliableStateManager.RemoveAsync (tx, name, timeout)" />
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
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="tx">使用してこの操作を関連付けるトランザクションです。</param>
        <param name="name">削除する <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。</param>
        <param name="timeout">操作が、TimeoutException がスローする前に完了するまで待機する時間の量。 主にデッドロックを防ぐために使用します。 既定では 4 秒です。</param>
        <summary>
            削除、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />この状態マネージャーから指定した名前です。 トランザクションがコミットされるとき、状態は永続的な記憶域およびすべてのレプリカから削除されます。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>
            これは、分割不可能な操作です。 <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と共にすべての状態が正常に削除される予定または整合性のままにします。 このメソッドは、例外をスローする場合は、トランザクションが中止する必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="tx" />null、または<paramref name="name" />が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定した名前が存在しないか、<paramref name="timeout" />が負の値。</exception>
        <exception cref="T:System.TimeoutException">操作は、指定したタイムアウト時間内に完了できませんでした。</exception>
        <exception cref="T:System.Fabric.FabricNotPrimaryException">場合にスローされる、<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />に含まれていない<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">トランザクションは、システムによって内部で途中終了されました。 新しいトランザクションで操作を再試行してください。</exception>
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            例では、使用されるトランザクションは既に終了: コミット済みまたはユーザーによって中止されました。
            この例外がスローされた場合は、トランザクションの使用のサービス コードにバグがある可能性があります。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態マネージャーの状態が変更されたときに発生します。
            たとえば、作成または信頼性の高い状態の削除または信頼性の高い状態マネージャーを再構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トランザクションの状態が変更されたときに発生します。
            たとえば、トランザクションのコミットされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="public bool TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateSerializer : Microsoft.ServiceFabric.Data.IStateSerializer&lt;'T&gt; -&gt; bool" Usage="iReliableStateManager.TryAddStateSerializer stateSerializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateSerializer" Type="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">シリアル化および逆シリアル化される型。</typeparam>
        <param name="stateSerializer">
            追加する状態シリアライザー。
            </param>
        <summary>
            すべての信頼性の高いコレクションのカスタム シリアライザーを登録します。
            </summary>
        <returns>
            カスタムのシリアライザーが追加された場合は true。
            指定した型のカスタムのシリアライザーが既に存在する場合は false です。
            </returns>
        <remarks>
          <para>
            信頼性の高いコレクションは、オブジェクトをシリアル化する必要があるとき、に、指定した型のシリアライザーを状態マネージャーを要求します。
            状態マネージャーは、入力の型に対して登録されているカスタムのシリアライザーが最初に確認します。 ない場合は、ある型をシリアル化できるかどうかは組み込みのシリアライザーのいずれかを確認します。 状態マネージャーは、次の種類の組み込みのシリアライザー: guid、bool、byte、sbyte、char、decimal、float、int、uint、double、long、ulong、short、ushort、文字列です。 使用していない場合、<see cref="T:System.Runtime.Serialization.DataContractSerializer" />です。
            </para>
          <para>
            シリアライザーの forwards と backwards の互換性が無限にあります。 組み込みのシリアライザーを使用しているタイプの場合、Service Fabric が上位互換性と下位互換性を保証します。 ただし、組み込みのシリアライザーと型のカスタムのシリアライザーが追加されると、カスタムのシリアライザーは、そのタイプの組み込みのシリアル化形式と互換性のあるする必要があります。
            </para>
          <para>
            このメソッドは、ステートフル サービスのコンス トラクターから呼び出す必要があります。 これにより、信頼性の高いコレクションいるために必要なシリアライザー、保存した状態の回復が開始される前にします。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。 取得したオブジェクトは、指定された型にキャストされます。
            </typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。
            <see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。
            たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T))" />
      <MemberSignature Language="F#" Value="abstract member TryGetAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt; (requires 'T :&gt; Microsoft.ServiceFabric.Data.IReliableState)" Usage="iReliableStateManager.TryGetAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceFabric.Data.IReliableState</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            型を指定する場合は、具象型またはインターフェイス型のいずれかを要求することがあります。 取得したオブジェクトは、指定された型にキャストされます。
            </typeparam>
        <param name="name">
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" /> の名前。 この名前は、この内で一意である必要があります<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />間<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />関係のない型を含む型。
            </param>
        <summary>
            取得を試みます、<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />指定された型の<typeparamref name="T" />と指定した名前です。
            </summary>
        <returns>非同期操作を表すタスク。 タスクの結果は、信頼性の高い状態が見つかったかどうかを示す組とそのインスタンス。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="name" /> が null です。</exception>
        <exception cref="T:System.ArgumentException"><see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />インスタンスは型に変換できません<typeparamref name="T" />です。</exception>
        <exception cref="T:System.Fabric.FabricNotReadableException">
            例外は、状態マネージャーに信頼性の高いコレクションを取得できないことを示します。
            <see cref="T:System.Fabric.FabricNotReadableException" />すべてのページでスローされる可能性<see cref="T:System.Fabric.ReplicaRole" />s。
            たとえば、ときに、<see cref="F:System.Fabric.ReplicaRole.Primary" />または<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />を失った<see cref="P:System.Fabric.IStatefulServicePartition.ReadStatus" />です。</exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
        <exception cref="T:System.Fabric.TransactionFaultedException">操作は、システムによって内部で途中終了されました。 操作をやり直してください。</exception>
      </Docs>
    </Member>
  </Members>
</Type>