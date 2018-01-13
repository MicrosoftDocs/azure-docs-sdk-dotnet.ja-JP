<Type Name="FabricClient+FaultManagementClient" FullName="System.Fabric.FabricClient+FaultManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.FaultManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/FaultManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.FaultManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.FaultManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.FaultManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Service Fabric クラスター内の障害を導入する機能を提供します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。 </param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。 </param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <summary>
             新しいノードにプライマリ レプリカを選択したクラスターに移動します。
             </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
             API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
             この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
             </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
             - アクションは、ステートレス サービスに対して呼び出されるとします。
             - 十分な数のノードは処理で使用しない場合
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。 </param>
        <param name="token">キャンセル トークン</param>
        <summary>
             新しいノードにプライマリ レプリカを選択したクラスターに移動します。
             </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
             API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
             この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
             </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
             - アクションは、ステートレス サービスに対して呼び出されるとします。
             - 十分な数のノードは処理で使用しない場合
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。 </param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            このオーバー ロードは、現在のノードの一覧から選択したランダム ノードを使用し、プライマリ レプリカがプライマリ レプリカを移動するための API の呼び出し時に存在しません。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。</remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。 </param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
             新しいノードにプライマリ レプリカを選択したクラスターに移動します。
             </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
             API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
             この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
             </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
             - アクションは、ステートレス サービスに対して呼び出されるとします。
             - 十分な数のノードは処理で使用しない場合
             </exception>
        <exception cref="T:System.Fabric.FabricException">
             FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
             </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            </param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MovePrimaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync (string nodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MovePrimaryResult&gt; MovePrimaryAsync(string nodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MovePrimaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MovePrimaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;" Usage="faultManagementClient.MovePrimaryAsync (nodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MovePrimaryAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MovePrimaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">ノードの名前、プライマリ レプリカを移動します。</param>
        <param name="partitionSelector">この選択されたパーティションで呼び出されるプライマリを移動します。
            API では、選択したパーティションのプライマリ レプリカを使用して、新しいノードの場所に移動します。
            </param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            新しいノードにプライマリ レプリカを選択したクラスターに移動します。
            </summary>
        <returns>移動プライマリ結果のタスク</returns>
        <remarks>
            API では、選択したパーティションのプライマリ レプリカを使用して、ノード名で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.NotReady - プライマリ レプリカが移動 FabricErrorCode.AlreadyPrimaryReplica - に対する準備されていない場合選択したパーティションの場合、プライマリ レプリカに既に存在新しいノード FabricErrorCode.ConstraintNotSatisfied の場合、新しい制約レプリカの場所は、移動を禁止します。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync partitionSelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。
            </param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、現在のセカンダリ ノードで指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。 </param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、現在のセカンダリ ノードで指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            この API のオーバー ロードは、選択したパーティションのランダムなセカンダリ レプリカの現在のセカンダリ ノードと選択したこのレプリカは、現在のノードの場所から新しいノードの場所に移動されますレプリカ移動のための新しいセカンダリ ノードにランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、指定されたパーティションのセレクターをランダムに選択したセカンダリ レプリカを使用します。
            この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノード位置をランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - レプリカが移動される場合はセカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。
            </param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。
            </param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、指定されたパーティションのセレクターをランダムに選択したセカンダリ レプリカを使用します。
            この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノード位置をランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この API のオーバー ロードは、この選択したレプリカは現在のノードの場所から新しいノードの場所に移動するレプリカの移動のための新しいセカンダリ ノードをランダムに選択します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用します。
            この選択したレプリカは、ランダムに選択されたノードの新しい場所に移動されます。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用します。
            この選択したレプリカは、ランダムに選択されたノードの新しい場所に移動されます。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName で指定された、選択したセカンダリ レプリカを使用および newNodeName で指定されたノードの新しい場所に移動します。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - 選択したパーティションのレプリカをプライマリ存在しない場合に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのアクティブなセカンダリ レプリカが新しいノードに存在しない場合FabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがない場合、セカンダリ FabricErrorCode.ConstraintNotSatisfied - レプリカの新しい場所の制約には、移動が禁止されている場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName 場所で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この選択したレプリカは、現在のノードの場所から newNodeName 場所に移動されます。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveSecondaryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync (string currentNodeName, string newNodeName, System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.MoveSecondaryResult&gt; MoveSecondaryAsync(string currentNodeName, string newNodeName, class System.Fabric.PartitionSelector partitionSelector, bool ignoreConstraints, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.MoveSecondaryAsync(System.String,System.String,System.Fabric.PartitionSelector,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveSecondaryAsync : string * string * System.Fabric.PartitionSelector * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;" Usage="faultManagementClient.MoveSecondaryAsync (currentNodeName, newNodeName, partitionSelector, ignoreConstraints, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;MoveSecondaryAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.MoveSecondaryResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentNodeName" Type="System.String" />
        <Parameter Name="newNodeName" Type="System.String" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="ignoreConstraints" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentNodeName">移動する場合に選択したレプリカが現在存在するノード名</param>
        <param name="newNodeName">ノード名の選択されたレプリカを移動します。</param>
        <param name="partitionSelector">移動セカンダリは、この選択したパーティションに呼び出されます。</param>
        <param name="ignoreConstraints">移動を実行しようとするときに制約を無視するかどうかを指定します。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            移動するには、クラスター内の新しいノードに現在のノードからのセカンダリ レプリカが選択されています。
            </summary>
        <returns>移動セカンダリ結果のタスク</returns>
        <remarks>
            API は、currentNodeName 場所で指定されたパーティション セレクター構造内の選択したセカンダリ レプリカを使用します。 この選択したレプリカは、現在のノードの場所から newNodeName 場所に移動されます。
            この API は、なることはありませんクォーラムやデータの損失を単独で追加のエラーや障害が同時に発生する場合を除き、つまりも安全です。
            </remarks>
        <exception cref="T:System.TimeoutException">再試行は行われません。</exception>
        <exception cref="T:System.InvalidOperationException">操作が無効です。
            - アクションは、ステートレス サービスに対して呼び出されるとします。
            - アクティブなセカンダリ レプリカが存在しない場合
            - 十分な数のノードは処理で使用しない場合
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            FabricErrorCode.AlreadyPrimaryReplica - に新しいノード FabricErrorCode.AlreadySecondaryReplica - 選択したパーティションのプライマリ レプリカが存在する場合の選択したパーティションのアクティブなセカンダリ レプリカに既に存在新しいノードFabricErrorCode.InvalidReplicaStateForReplicaOperation - 対象のレプリカがセカンダリではない場合
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM vie.w 外 DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</param>
        <param name="forceRemove">レプリカは強制的に削除されます。</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</param>
        <param name="forceRemove">レプリカは強制的に削除されます。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, bool forceRemove, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (replicaSelector, completionMode, forceRemove, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを削除することを示します。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</param>
        <param name="forceRemove">レプリカが強制的に削除されます。</param>
        <param name="operationTimeout">レプリカを削除するを待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカを削除する必要がある Id </param>
        <param name="replicaId">削除する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="forceRemove">レプリカは強制的に削除されます。</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカを削除する必要がある Id </param>
        <param name="replicaId">削除する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />レプリカの削除が完了するか、FM ビューから外れて DoNotVerify できません - レプリカを確認してください - 戻り値が終わったら、削除など、レプリカの削除をトリガーして返されるはまで待機するかどうかを指定します。</param>
        <param name="forceRemove">レプリカは強制的に削除されます。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, bool forceRemove, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RemoveReplicaResult&gt; RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, bool forceRemove, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Boolean,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * bool * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;" Usage="faultManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaId, completionMode, forceRemove, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RemoveReplicaAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RemoveReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカを移動するノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカを削除する必要がある Id </param>
        <param name="replicaId">削除する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="forceRemove">レプリカが強制的に削除されます。</param>
        <param name="operationTimeoutSec">レプリカを削除するを待機するタイムアウトを含む操作は、秒単位で全体的タイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡されたで指定されたレプリカ (ReportFault - 永続的であるのと同等) を削除で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RemoveReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前</param>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <summary>
            この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。
            </summary>
        <returns>RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">コードが belong.s をパッケージ化するアプリケーションの名前</param>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。
            </summary>
        <returns>RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (Uri applicationName, System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(class System.Uri applicationName, class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.Uri,System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : Uri * System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (applicationName, replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前</param>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />識別、レプリカがホスト コード パッケージが再起動する必要があります。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" /> Not.n またはコード パッケージの再起動が完了するまで待機するかどうかを指定します</param>
        <param name="operationTimeout">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</param>
        <param name="token">キャンセル トークン。</param>
        <summary>
            この API 呼び出しで指定されたレプリカをホストしているコード パッケージが再起動、<see cref="T:System.Fabric.ReplicaSelector" />指定されたアプリケーション名に属しているとします。
            </summary>
        <returns>RestartDeployedCodePackageResult が実際のコード パッケージが再起動し、選択されているレプリカに関する情報を得られます。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、指定されたパーティションが選択されている FabricErrorCode.CodePackageNotFound が存在しません - 選択したレプリカが FabricErrorCode.PartitionNotFound が見つからない場合、選択したコードパッケージが見つかりませんでした。</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノードです。</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前。</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前。</param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノード</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前</param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノードです。</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前。</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前。</param>
        <param name="servicePackageActivationId">
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。 使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノードです。</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前。</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前。</param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <param name="operationTimeout">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノード</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前</param>
        <param name="servicePackageActivationId">
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。 使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartDeployedCodePackageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync (string nodeName, Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, long codePackageInstanceId, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartDeployedCodePackageResult&gt; RestartDeployedCodePackageAsync(string nodeName, class System.Uri applicationName, string serviceManifestName, string servicePackageActivationId, string codePackageName, int64 codePackageInstanceId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartDeployedCodePackageAsync(System.String,System.Uri,System.String,System.String,System.String,System.Int64,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartDeployedCodePackageAsync : string * Uri * string * string * string * int64 * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;" Usage="faultManagementClient.RestartDeployedCodePackageAsync (nodeName, applicationName, serviceManifestName, servicePackageActivationId, codePackageName, codePackageInstanceId, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartDeployedCodePackageAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartDeployedCodePackageResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
        <Parameter Name="codePackageName" Type="System.String" />
        <Parameter Name="codePackageInstanceId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">コード パッケージがホストされているノードです。</param>
        <param name="applicationName">コード パッケージが所属するアプリケーションの名前。</param>
        <param name="serviceManifestName">コード パッケージが定義されているサービス マニフェストの名前。</param>
        <param name="servicePackageActivationId">
          <para>
            <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />コード パッケージが含まれている展開済みサービス パッケージのです。 使用して、展開済みサービス パッケージの ServicePackageActivationId を取得できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />クエリ。 
            </para>
          <para>
            場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />の作成時に指定された、サービスは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </param>
        <param name="codePackageName">再起動するコード パッケージの名前</param>
        <param name="codePackageInstanceId">指定されていてと一致しませんし、再起動場合は処理されません、値は 0、比較を実行中のコード パッケージのコード パッケージ インスタンス id はスキップされます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />か、コード パッケージの再起動が完了するまで待機するかどうかを指定します。</param>
        <param name="operationTimeout">コード パッケージを再起動するまで待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API 呼び出しでは、入力パラメーターで指定されたコード パッケージが再起動します。
            </summary>
        <returns>実際のコード パッケージについての情報」に進んで RestartDeployedCodePackageResult が再起動されます。 SelectedReplica はこのオーバー ロードでは None です。</returns>
        <remarks>
            <see cref="T:System.Fabric.CompletionMode" />オプションは DoNotVerify - コード パッケージを確認してください - 完了再起動つまりコード パッケージの戻り値の再起動をトリガーした後の戻り値が返されるもう一度です。
            </remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.CodePackageNotFound - 選択したコード パッケージが見つかりませんでした FabricErrorCode.InstanceIdMismatch - 指定したインスタンス id が一致しない場合</exception>
        <exception cref="T:System.InvalidOperationException">コード パッケージが有効な実行中状態ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">このパラメーターは使用を特定のレプリカを選択します。  このレプリカの対応するノードが再起動されます。</param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードと選択したレプリカを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。
              ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。
              ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">このパラメーターは使用を特定のレプリカを選択します。  このレプリカの対応するノードが再起動されます。</param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードと選択したレプリカを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。
              ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。
              ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">再起動するノードのノード名。</param>
        <param name="nodeInstance">
          <para>再起動するノードのノード インスタンス ID。
            いない、または、指定されて 0 に設定されている場合、値は無視されます。
            インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。
            インスタンスには正の値がある場合は、アクティブなノード id と比較されます。
            Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。
            古いメッセージは、このエラーを発生できます。
            </para>
        </param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。
              ErrorCode が NodeNotFound の場合は、nodeName またはノード インスタンスが無効です。
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">このパラメーターは使用を特定のレプリカを選択します。
            レプリカが配置されているノードが再起動されます。</param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードと選択したレプリカを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。
              ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。
              ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">再起動するノードのノード名。</param>
        <param name="nodeInstance">
          <para>再起動するノードのノード インスタンス ID。
            いない、または、指定されて 0 に設定されている場合、値は無視されます。
            インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。
            インスタンスには正の値がある場合は、アクティブなインスタンス ID を持つ比較します。
            インスタンスが一致しない場合、プロセスは再開されませんし、エラーが発生します。
            古いメッセージは、このエラーを発生できます。
            </para>
        </param>
        <param name="completionMode">場合設定<see cref="F:System.Fabric.CompletionMode.Verify" />、システムことを確認、ノードを再起動し、API があり、NodeStatus が稼働するまでは返されません。
            場合設定<see cref="F:System.Fabric.CompletionMode.DoNotVerify" />ノードの再起動が開始された後に、API が返されます。</param>
        <param name="token">この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。
            ErrorCode が InstanceIdMismatch の場合、<paramref name="nodeInstance" />提供される、現在実行中のインスタンスと一致しません。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartNodeAsync (nodeName As String, nodeInstance As BigInteger, operationTimeout As TimeSpan, token As CancellationToken) As Task(Of RestartNodeResult)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">再起動するノードのノード名。</param>
        <param name="nodeInstance">
          <para>再起動するノードのノード インスタンス ID。
            いない、または、指定されて 0 に設定されている場合、値は無視されます。
            インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。
            インスタンスには正の値がある場合は、アクティブなノード id と比較されます。
            Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。
            古いメッセージは、このエラーを発生できます。
            </para>
        </param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。  
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(class System.Fabric.ReplicaSelector replicaSelector, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.Fabric.ReplicaSelector,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : System.Fabric.ReplicaSelector * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (replicaSelector, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector">このパラメーターは使用を特定のレプリカを選択します。  このレプリカの対応するノードが再起動されます。</param>
        <param name="createFabricDump"> 場合は true、システムに設定は、このノードの Fabric.exe のプロセスのダンプを作成します。</param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードと選択したレプリカを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。
            CreateFabricDump パラメーターが設定されている場合は、再起動時に、プロセスがクラッシュしましたおよびクラッシュ ダンプ フォルダーに配置されて、クラッシュ ダンプ DCA は、アップロードするように構成できます。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。
              ErrorCode が ReplicaDoesNotExist の場合は、選択したレプリカは見つかりませんでした。
              ErrorCode が PartitionNotFound の場合は、指定されたパーティションは存在しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, bool createFabricDump, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartNodeResult&gt; RestartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, bool createFabricDump, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartNodeAsync(System.String,System.Numerics.BigInteger,System.Boolean,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartNodeAsync : string * System.Numerics.BigInteger * bool * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;" Usage="faultManagementClient.RestartNodeAsync (nodeName, nodeInstance, createFabricDump, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartNodeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="createFabricDump" Type="System.Boolean" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">再起動するノードのノード名。</param>
        <param name="nodeInstance">
          <para>再起動するノードのノード インスタンス ID。
            いない、または、指定されて 0 に設定されている場合、値は無視されます。
            インスタンスは、-1 に設定されている場合、システムはこの値を内部的に決定します。
            インスタンスには正の値がある場合は、アクティブなノード id と比較されます。
            Id が一致しない場合、プロセスは再開されませんし、エラーが発生します。
            古いメッセージは、このエラーを発生できます。
            </para>
        </param>
        <param name="createFabricDump"> 場合は true、システムに設定は、このノードの Fabric.exe のプロセスのダンプを作成します。</param>
        <param name="completionMode">設定を確認してください、システムは確認をノードを再起動して、API があり、NodeStatus が稼働するまでは返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの再起動が開始されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            ノードをホストする Fabric.exe プロセスを再起動することによって、クラスター ノードを再起動します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>
            この API は、Service Fabric サービスのフェールオーバーの復旧パスをテストすると、クラスター内のノードの障害をシミュレートします。
            </remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が NodeNotFound の場合は、ノード名が正しくありません。  
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。 この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <summary>
            この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。 この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡された ReplicaSelector で指定されたレプリカ (ReportFault - 一時のと同等) を再起動します。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (System.Fabric.ReplicaSelector replicaSelector, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(class System.Fabric.ReplicaSelector replicaSelector, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.Fabric.ReplicaSelector,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : System.Fabric.ReplicaSelector * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (replicaSelector, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="replicaSelector" Type="System.Fabric.ReplicaSelector" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="replicaSelector"><see cref="T:System.Fabric.ReplicaSelector" />レプリカを再起動することを示します。 この API は、永続化されたサービス レプリカでのみ呼び出すことができます。</param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="operationTimeout">レプリカを場合に再起動するを待機するタイムアウトを含む、操作の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist - 選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカが再起動する必要がある Id </param>
        <param name="replicaId">再起動する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <summary>
            この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカが再起動する必要がある Id </param>
        <param name="replicaId">再起動する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API は、渡された ReplicaSelector で指定されたレプリカ (ReportFault - 一時のと同等) を再起動します。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist の場合は、選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync (string nodeName, Guid partitionId, long replicaId, System.Fabric.CompletionMode completionMode, double operationTimeoutSec, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartReplicaResult&gt; RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.Fabric.CompletionMode completionMode, float64 operationTimeoutSec, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.Fabric.CompletionMode,System.Double,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * System.Fabric.CompletionMode * double * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;" Usage="faultManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaId, completionMode, operationTimeoutSec, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;RestartReplicaAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartReplicaResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeoutSec" Type="System.Double" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">レプリカが再起動する必要があるノード名<see cref="T:System.Fabric.ReplicaSelector" /></param>
        <param name="partitionId">パーティション、レプリカが再起動する必要がある Id </param>
        <param name="replicaId">再起動する必要があるレプリカ Id </param>
        <param name="completionMode"><see cref="T:System.Fabric.CompletionMode" />いない DoNotVerify またはレプリカの再起動が完了するまで待機するかどうかを指定する - トリガーを確認してください - 戻り値の削除が完了した後、レプリカの再起動後に返されます</param>
        <param name="operationTimeoutSec">場合は再起動するレプリカを待機するタイムアウトを含む操作は、秒単位の全体的なタイムアウト<see cref="T:System.Fabric.CompletionMode" />を確認してください。</param>
        <param name="token">キャンセル トークン</param>
        <summary>
            この API に渡された指定されたレプリカ (ReportFault - 一時のと同等) が再起動で<see cref="T:System.Fabric.ReplicaSelector" />です。
            </summary>
        <returns>RestartReplicaResult が実際に選択したレプリカに関する情報を得られます。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">アクションにかかった、割り当てられた時間を超える。</exception>
        <exception cref="T:System.ArgumentNullException">必須の引数のいずれかが null です。</exception>
        <exception cref="T:System.Fabric.FabricException">これらは、ファブリック エラー FabricErrorCode.ReplicaDoesNotExist - 選択したレプリカが見つかりませんでした FabricErrorCode.PartitionNotFound - 選択されている、指定されたパーティションが存在しない場合</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">開始するノードのノード名。</param>
        <param name="nodeInstance">停止する前に、ノードのノード インスタンス ID。 これが指定されていない、または 0 に設定されている、これは無視されます。 これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。  かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</param>
        <summary>
            クラスター ノードを開始します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。  
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。  
              ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">開始するノードのノード名。</param>
        <param name="nodeInstance">停止する前に、ノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。  かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            クラスター ノードを開始します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。  
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。  
              ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">開始するノードのノード名。</param>
        <param name="nodeInstance">停止する前に、ノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="ipAddressOrFQDN">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。  このパラメーターを指定すると場合、' ClusterConnectionPort"も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="clusterConnectionPort">ターゲット ノードのクラスター接続ポートです。  このパラメーターを指定すると場合、'ipAddressOrFQDN' も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。  かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</param>
        <summary>
            クラスター ノードを開始します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。  
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。  
              ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">開始するノードのノード名。</param>
        <param name="nodeInstance">停止する前に、ノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="ipAddressOrFQDN">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。  このパラメーターを指定すると場合、<paramref name="clusterConnectionPort" />も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="clusterConnectionPort">ターゲット ノードのクラスター接続ポートです。  このパラメーターを指定すると場合、<paramref name="ipAddressOrFQDN" />も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。  かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            クラスター ノードを開始します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。  
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。  
              ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt; StartNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int clusterConnectionPort, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StartNodeResult&gt; StartNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, string ipAddressOrFQDN, int32 clusterConnectionPort, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StartNodeAsync(System.String,System.Numerics.BigInteger,System.String,System.Int32,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartNodeAsync : string * System.Numerics.BigInteger * string * int * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;" Usage="faultManagementClient.StartNodeAsync (nodeName, nodeInstance, ipAddressOrFQDN, clusterConnectionPort, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StartNodeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StartNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
        <Parameter Name="clusterConnectionPort" Type="System.Int32" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">開始するノードのノード名。</param>
        <param name="nodeInstance">停止する前に、ノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="ipAddressOrFQDN">IP アドレスまたはターゲット ノードの完全修飾ドメイン名 (FQDN) です。  このパラメーターを指定すると場合、<paramref name="clusterConnectionPort" />も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="clusterConnectionPort">ターゲット ノードのクラスター接続ポートです。  このパラメーターを指定すると場合、<paramref name="ipAddressOrFQDN" />も指定する必要があります。  どちらも指定しないと場合、システムはこれらを内部的に決定します。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが開始されると、および状態になるまで、この API は返されません。  かどうか DoNotVerify に設定すると、API を返しますノードの開始が開始されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">CancellationToken</param>
        <summary>
            クラスター ノードを開始します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、nodeName またはノード インスタンスが無効です。  
              ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。  
              ErrorCode が NodeHasNotStoppedYet の場合は、このノードで現在保留中の停止操作があります。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
      </Parameters>
      <Docs>
        <param name="nodeName">停止するノードのノード名。</param>
        <param name="nodeInstance">停止するノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</param>
        <summary>
            クラスター ノードを停止します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。  
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">停止するノードのノード名。</param>
        <param name="nodeInstance">停止するノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            クラスター ノードを停止します。
            </summary>
        <returns>については、ターゲット ノードを表すタスク。</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。  
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="StopNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt; StopNodeAsync (string nodeName, System.Numerics.BigInteger nodeInstance, System.Fabric.CompletionMode completionMode, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.StopNodeResult&gt; StopNodeAsync(string nodeName, valuetype System.Numerics.BigInteger nodeInstance, valuetype System.Fabric.CompletionMode completionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.FaultManagementClient.StopNodeAsync(System.String,System.Numerics.BigInteger,System.Fabric.CompletionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopNodeAsync : string * System.Numerics.BigInteger * System.Fabric.CompletionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;" Usage="faultManagementClient.StopNodeAsync (nodeName, nodeInstance, completionMode, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartNodeTransitionAsync instead.")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.FabricClient/FaultManagementClient/&lt;StopNodeAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.StopNodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstance" Type="System.Numerics.BigInteger" />
        <Parameter Name="completionMode" Type="System.Fabric.CompletionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">停止するノードのノード名。</param>
        <param name="nodeInstance">停止するノードのノード インスタンス ID。  これが指定されていない、または 0 に設定されている、これは無視されます。  これは、-1 に設定されている場合、システムはこの値を決定内部的にします。</param>
        <param name="completionMode">設定を確認してください、システムがチェックするノードが停止し、API は、状態になるまで返されません。  かどうか DoNotVerify に設定すると、API を返します、ノードの停止が開始されます。</param>
        <param name="operationTimeout">この API 呼び出しのタイムアウト。</param>
        <param name="token">操作をキャンセルするすべての要求の監視は、キャンセル トークン。</param>
        <summary>
            クラスター ノードを停止します。
            </summary>
        <returns>ターゲット ノードを表す情報とタスク</returns>
        <remarks>クラスター ノードとは、仮想または物理マシンではなく、プロセスです。</remarks>
        <exception cref="T:System.Fabric.FabricException"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。  
              ErrorCode が無効な引数の場合は、ノード名が正しくありません。  
              ErrorCode が InstanceIdMismatch の場合は、提供されるノード インスタンスが、現在実行中のインスタンスと一致しません。
            </exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたとき。</exception>
        <exception cref="T:System.ArgumentNullException">値は null の引数が渡されました。</exception>
      </Docs>
    </Member>
  </Members>
</Type>