<Type Name="ReliableStateManager" FullName="Microsoft.ServiceFabric.Data.ReliableStateManager">
  <TypeSignature Language="C#" Value="public class ReliableStateManager : Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;, Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi ReliableStateManager extends System.Object implements class Microsoft.ServiceFabric.Data.IAsyncEnumerable`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt;, class Microsoft.ServiceFabric.Data.IReliableStateManager, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica, class Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Class ReliableStateManager&#xA;Implements IAsyncEnumerable(Of IReliableState), IReliableStateManagerReplica2" />
  <TypeSignature Language="F#" Value="type ReliableStateManager = class&#xA;    interface IReliableStateManagerReplica2&#xA;    interface IReliableStateManagerReplica&#xA;    interface IStateProviderReplica&#xA;    interface IReliableStateManager&#xA;    interface IAsyncEnumerable&lt;IReliableState&gt;&#xA;    interface IStateProviderReplica2" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IReliableStateManagerReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            ReliableStateManager クラスが管理を担当<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />サービス レプリカにします。
            サービス内の各レプリカで独自<see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />と<see cref="T:Microsoft.ServiceFabric.Data.ReliableStateManager" />です。 
            <see cref="T:Microsoft.ServiceFabric.Data.IReliableState" />含めることができます<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableDictionary`2" />、 <see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableQueue`1" />、または any<see cref="T:Microsoft.ServiceFabric.Data.Collections.IReliableCollection`1" />型です。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReliableStateManager (System.Fabric.StatefulServiceContext serviceContext, Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext serviceContext, class Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceContext As StatefulServiceContext, Optional configuration As ReliableStateManagerConfiguration = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.ReliableStateManager : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration -&gt; Microsoft.ServiceFabric.Data.ReliableStateManager" Usage="new Microsoft.ServiceFabric.Data.ReliableStateManager (serviceContext, configuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="configuration" Type="Microsoft.ServiceFabric.Data.ReliableStateManagerConfiguration" />
      </Parameters>
      <Docs>
        <param name="serviceContext">A<see cref="T:System.Fabric.StatefulServiceContext" />サービス コンテキストをについて説明します。</param>
        <param name="configuration">構成パラメーター。</param>
        <summary>
            新しい ReliableStateManager を作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</param>
        <summary>
            これによって管理されるすべての信頼性の高い状態の完全バックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            完全バックアップは、1 時間のタイムアウトを設定して実行されます。
            BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。
            False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。
            また、バックアップはマークされます失敗とします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">実行するバックアップの種類。</param>
        <param name="timeout">この操作のタイムアウト。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <param name="backupCallback">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</param>
        <summary>
            これによって管理されるすべての信頼性の高い状態のバックアップを実行<see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />です。
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            BackupCallback によって返されるブール値では、サービスが正常に外部の場所に、バックアップ フォルダーを移動するかどうかを示します。
            False が返される場合は BackupAsync backupCallback false が返されたことを示す関連するメッセージに InvalidOperationException がスローされます。
            また、バックアップはマークされます失敗とします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsyncEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.IAsyncEnumerator`1&lt;class Microsoft.ServiceFabric.Data.IReliableState&gt; GetAsyncEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.GetAsyncEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAsyncEnumerator () As IAsyncEnumerator(Of IReliableState)" />
      <MemberSignature Language="F#" Value="abstract member GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;&#xA;override this.GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;" Usage="reliableStateManager.GetAsyncEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;Microsoft.ServiceFabric.Data.IReliableState&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            コレクションを反復処理する列挙子を返します。
            </summary>
        <returns>
            コレクションを反復処理するために使用できる <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> オブジェクト。
            </returns>
        <remarks>To be added.</remarks>
        <filterpriority>1</filterpriority>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction">
      <MemberSignature Language="C#" Value="Microsoft.ServiceFabric.Data.ITransaction IReliableStateManager.CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.ITransaction Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Function CreateTransaction () As ITransaction Implements IReliableStateManager.CreateTransaction" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.CreateTransaction</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As String, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IReliableStateManager.GetOrAddAsync&lt;T&gt; (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function GetOrAddAsync(Of T As IReliableState) (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task(Of T) Implements IReliableStateManager.GetOrAddAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.GetOrAddAsync``1(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, string name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, string name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As String, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IReliableStateManager.RemoveAsync (Microsoft.ServiceFabric.Data.ITransaction tx, Uri name, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(class Microsoft.ServiceFabric.Data.ITransaction tx, class System.Uri name, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Function RemoveAsync (tx As ITransaction, name As Uri, timeout As TimeSpan) As Task Implements IReliableStateManager.RemoveAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.RemoveAsync(Microsoft.ServiceFabric.Data.ITransaction,System.Uri,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
        <exception cref="T:System.InvalidOperationException">
            メソッドの呼び出しが、オブジェクトの現在の状態に対して無効である場合にスローされます。
            たとえば、使用されるトランザクションは終了既に: コミットまたは中止されました。
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;">
      <MemberSignature Language="C#" Value="bool IReliableStateManager.TryAddStateSerializer&lt;T&gt; (Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt; stateSerializer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer&lt;T&gt;(class Microsoft.ServiceFabric.Data.IStateSerializer`1&lt;!!T&gt; stateSerializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" />
      <MemberSignature Language="VB.NET" Value="Function TryAddStateSerializer(Of T) (stateSerializer As IStateSerializer(Of T)) As Boolean Implements IReliableStateManager.TryAddStateSerializer" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
            状態のシリアライザーを追加します。
            すべての信頼性の高いコレクション インスタンスに対して追加されます。
            </summary>
        <returns>
            True の場合、シリアライザーが追加されました。
            Serailizer は既に登録されている場合は false。
            </returns>
        <remarks>
            このメソッドは、InitializeStateSerializers でのみ呼び出すことができます。
            インスタンスの特定の状態のシリアライザー常に優先されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (string name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As String) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; IReliableStateManager.TryGetAsync&lt;T&gt; (Uri name) where T : Microsoft.ServiceFabric.Data.IReliableState;" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync&lt;(class Microsoft.ServiceFabric.Data.IReliableState) T&gt;(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IReliableStateManager#TryGetAsync``1(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Function TryGetAsync(Of T As IReliableState) (name As Uri) As Task(Of ConditionalValue(Of T)) Implements IReliableStateManager.TryGetAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryGetAsync``1(System.Uri)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            状態プロバイダーのレプリカを強制的に中止します。
            </summary>
        <remarks>
            これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">プライマリまたはセカンダリなど、新しいレプリカ ロール。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。
            </summary>
        <returns>非同期の変更の役割の操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            状態プロバイダーの複製が正常にクローズします。
            </summary>
        <returns>非同期の close 操作を表すタスク。</returns>
        <remarks>
            これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</param>
        <summary>
            サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。
            </summary>
        <remarks>
            複雑な処理を初期化中に行う必要はありません。 OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">これが新規または既存のレプリカであるかどうかを示します。</param>
        <param name="partition">このレプリカが属しているパーティション。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            使用するため、状態プロバイダーのレプリカを開きます。
            </summary>
        <returns>
            非同期の open 操作を表すタスク。 結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。
            </returns>
        <remarks>
            この時点でのタスクを開始状態プロバイダーの初期化を拡張します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            通知を受信するには、このプロパティを設定するときにこの<see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />データが失われると予想できます。
            </summary>
        <value>
            疑いのあるデータ損失の処理の一部として呼び出される関数。
            </value>
        <remarks>
          <para>
            OnDataLossAsync 関数は、CancellationToken はし、イベントの非同期処理を表すタスクを返す必要があります。
            True を返すには、信頼性の高い状態マネージャーの状態が復元されていることを示します。
            False を返すことは、信頼性の高い状態マネージャーの状態が変更されていないことを示します。
            </para>
          <para>
            渡されたデリゲートは、キャンセル要求に指定されたキャンセル トークンを監視する必要があります。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Data.ReliableStateManager.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ServiceFabric.Data.IStateProviderReplica2.OnRestoreCompletedAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Post 復元が呼び出される関数はレプリカで実行されています。
            </summary>
        <value>
            フレームワークによって、レプリカの状態が正常に復元された場合に呼び出される関数
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできませんを空または空白のみが含まれています。 UNC パスも指定することがあります。
            </param>
        <summary>
            によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。
            </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
            つまり、復元するデータが、現在のレプリカの状態より進んでいる場合、復元は完了のみ、安全なバックアップが実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.ReliableStateManager.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="reliableStateManager.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            このパラメーターを null にすることはできませんを空または空白のみが含まれています。 UNC パスも指定することがあります。
            </param>
        <param name="restorePolicy">復元のポリシー。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。
            </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManagerChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; StateManagerChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.StateManagerChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event StateManagerChanged As EventHandler(Of NotifyStateManagerChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.StateManagerChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " Usage="member this.StateManagerChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.StateManagerChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyStateManagerChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態マネージャーが変更されたときに発生します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
    <Member MemberName="TransactionChanged">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; TransactionChanged" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceFabric.Data.ReliableStateManager.TransactionChanged" />
      <MemberSignature Language="VB.NET" Value="Public Custom Event TransactionChanged As EventHandler(Of NotifyTransactionChangedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.TransactionChanged : EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " Usage="member this.TransactionChanged : System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <Implements>
        <InterfaceMember>E:Microsoft.ServiceFabric.Data.IReliableStateManager.TransactionChanged</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceFabric.Data.Notifications.NotifyTransactionChangedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トランザクションが変更されたときに発生します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">信頼性の高い状態マネージャーが閉じていることを示します。</exception>
      </Docs>
    </Member>
  </Members>
</Type>