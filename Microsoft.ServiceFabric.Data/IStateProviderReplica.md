<Type Name="IStateProviderReplica" FullName="Microsoft.ServiceFabric.Data.IStateProviderReplica">
  <TypeSignature Language="C#" Value="public interface IStateProviderReplica" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProviderReplica" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProviderReplica" />
  <TypeSignature Language="F#" Value="type IStateProviderReplica = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Service Fabric サービスと対話するの信頼性の高い状態プロバイダーの複製を実装する必要がありますメソッドを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStateProviderReplica.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.BackupAsync backupCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="F#" Value="abstract member BackupAsync : Microsoft.ServiceFabric.Data.BackupOption * TimeSpan * System.Threading.CancellationToken * Func&lt;Microsoft.ServiceFabric.Data.BackupInfo, System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.BackupAsync (option, timeout, cancellationToken, backupCallback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="iStateProviderReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Data.IStateProviderReplica.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            関数は、疑いのあるデータ損失の可能性の中に呼び出されます。
            </summary>
        <value>
            疑いのあるデータ損失の処理の一部として呼び出される関数。
            関数は、CancellationToken はし、イベントの非同期処理を表すタスクを返す必要があります。
            True を返すには、レプリカの状態が復元されていることを示します。
            False は、レプリカの状態が変更されていないことを示します。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="iStateProviderReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupFolderPath As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.RestoreAsync backupFolderPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
            つまり、復元するデータが、現在のレプリカの状態より進んでいる場合、復元は完了のみ、安全な復元が実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.ServiceFabric.Data.RestorePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProviderReplica.RestoreAsync (backupFolderPath, restorePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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
  </Members>
</Type>