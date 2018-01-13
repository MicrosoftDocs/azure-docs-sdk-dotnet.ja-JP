<Type Name="CloudJob" FullName="Microsoft.Azure.Batch.CloudJob">
  <TypeSignature Language="C#" Value="public class CloudJob : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJob extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CloudJob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJob&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type CloudJob = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;JobAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Batch のジョブの場合は。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="cloudJob.AddTask (taskToAdd, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskToAdd">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            これを 1 つのタスクを追加<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。  複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。
            </summary>
        <returns>ステージング処理ファイルに関する情報のコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</returns>
        <remarks>
          <para>
            このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。 したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。
            並列でこれらの操作の多くを実行して、クライアント側のタイムアウトが表示される場合 (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTask(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.AddTask (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</param>
        <param name="parallelOptions">
            バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。  各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。
            また、操作のキャンセル トークンを制御します。
            既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。
            </param>
        <param name="fileStagingArtifacts">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。
            単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。
            各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</param>
        <param name="timeout">操作がタイムアウトするまでの時間。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            ジョブにタスクを追加します。
            </summary>
        <remarks>
          <para>これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</para>
          <para>このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。 追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。  に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</para>
          <para>Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。
            これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合、クライアント側のタイムアウトが表示される (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</para>
          <para>エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。
            通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。
            この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskToAdd">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</param>
        <param name="allFileStagingArtifacts">オプションのコレクションをカスタマイズし、ステージング処理ファイルに関する情報を受け取ります (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            これを 1 つのタスクを追加<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。  複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。 したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。
            並列でこれらの操作の多くを実行して、クライアント側のタイムアウトが表示される場合 (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.
            </para>
          <para>タスクの追加操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudJob.AddTaskAsync (tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;AddTaskAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToAdd"><see cref="T:Microsoft.Azure.Batch.CloudTask" />S を追加します。</param>
        <param name="parallelOptions">
            バッチ サービスに発行された同時の並列 AddTaskCollection 要求の数を制御します。  各 AddTaskCollection 要求が最大で含まれている<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />その中のタスクです。
            また、操作のキャンセル トークンを制御します。
            既定値が使用される省略すると、(を参照してください<see cref="T:Microsoft.Azure.Batch.BatchClientParallelOptions" />)。
            </param>
        <param name="fileStagingArtifacts">ステージング処理ファイルに関する情報を受信する、省略可能なコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            エントリを追加、 <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" /> Batch service に送信するグループ化されたタスクのセットごとにします。
            単一タスクとは異なりを追加、ファイルのステージング処理をカスタマイズする、このパラメーターを使用することはできません。
            各エントリの形式に関する詳細については、次を参照してください。<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />です。</param>
        <param name="timeout">操作がタイムアウトするまでの時間。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            ジョブにタスクを追加します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>タスクの追加操作は非同期的に実行されます。</para>
          <para>このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。 追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。  に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</para>
          <para>Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。
            これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合、クライアント側のタイムアウトが表示される (、 <see cref="T:System.Threading.Tasks.TaskCanceledException" />)、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</para>
          <para>エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。
            通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。
            この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Commit additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            このコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。
            </summary>
        <remarks>
          <para>場合、<see cref="T:Microsoft.Azure.Batch.CloudJob" />既に存在する、バッチ サービスでは、そのプロパティがこのプロパティで置き換えられます<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            このコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>場合、<see cref="T:Microsoft.Azure.Batch.CloudJob" />既に存在する、バッチ サービスでは、そのプロパティがこのプロパティで置き換えられます<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。</para>
          <para>コミット操作が非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChanges">
      <MemberSignature Language="C#" Value="public void CommitChanges (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CommitChanges(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChanges(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CommitChanges (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CommitChanges : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.CommitChanges additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。
            </summary>
        <remarks>
          <para>
            既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJob" />が変更されました。
            変更されていないプロパティは無視されます。
            このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。
            Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。
            プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。
            </para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitChangesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitChangesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitChangesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.CommitChangesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitChangesAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.CommitChangesAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;CommitChangesAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            これをすべて保留中の変更をコミット<see cref="T:Microsoft.Azure.Batch.CloudJob" />Azure Batch のサービスにします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            既存の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />のこのプロパティをそのプロパティを置き換えることで、バッチ サービスで<see cref="T:Microsoft.Azure.Batch.CloudJob" />が変更されました。
            変更されていないプロパティは無視されます。
            このエンティティの前回のすべての変更は、バッチ サービスから取得されました (のいずれかによって<see cref="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、 <see cref="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />、または<see cref="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />) 適用されます。
            Null が明示的に設定されているプロパティでは、バッチ サービスは、プロパティを null に設定する部分的な更新をサポートしていないため、例外が発生します。
            プロパティを null に設定する必要がある場合を使用して<see cref="M:Microsoft.Azure.Batch.CloudJob.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。
            </para>
          <para>この操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または一般的な環境変数設定の一覧を設定します。 これらの環境変数がすべてのタスクの設定は<see cref="T:Microsoft.Azure.Batch.CloudJob" />(ジョブ マネージャー、ジョブの準備およびジョブのリリース タスクを含む)。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの実行の制約を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの作成時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Delete additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            この <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を削除します。
            </summary>
        <remarks>
          <para>削除操作は、ジョブを削除することを要求します。  要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            この <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>削除操作は、ジョブを削除することを要求します。  要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public void Disable (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Disable(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Disable(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.Disable : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Disable (disableJobOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="disableJobOption">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。  無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableAsync (Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableAsync(valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.DisableAsync(Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableAsync : Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.DisableAsync (disableJobOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="disableJobOption">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            これを無効に<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。  無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>無効化操作が非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public void Enable (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Enable(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Enable(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Enable (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Enable : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Enable additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJob" />、新しいタスクの実行を許可します。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.EnableAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.EnableAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            これにより、 <see cref="T:Microsoft.Azure.Batch.CloudJob" />、新しいタスクの実行を許可します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>有効にする操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Batch.CloudJob.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの ETag を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobExecutionInformation ExecutionInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionInformation As JobExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInformation : Microsoft.Azure.Batch.JobExecutionInformation" Usage="Microsoft.Azure.Batch.CloudJob.ExecutionInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの実行情報を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTask(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="cloudJob.GetTask (taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="taskId">取得するためのタスクの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.GetTaskAsync (taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskId">取得するためのタスクの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</returns>
        <remarks>タスクの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetTaskCounts (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetTaskCounts(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCounts(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTaskCounts (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetTaskCounts : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="cloudJob.GetTaskCounts additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskCounts</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            ジョブのタスクの数を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />オブジェクトのタスクを含むジョブのカウント</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetTaskCountsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.GetTaskCountsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskCountsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="cloudJob.GetTaskCountsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;GetTaskCountsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ジョブのタスクの数を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</returns>
        <remarks>ジョブのタスクの取得は、非同期的に操作の実行をカウントします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ジョブ マネージャー タスクを設定します。 ジョブ マネージャー タスクが起動されるときに、<see cref="T:Microsoft.Azure.Batch.CloudJob" />が開始します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの準備タスクを設定します。 バッチ サービスは、そのコンピューティング ノードでそのジョブのすべてのタスクを開始する前に、コンピューティング ノードでジョブの準備タスクが実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブのリリース タスクを設定します。 バッチ サービスは、ジョブのいずれかのタスクが実行される各コンピューティング ノードで、ジョブの終了時に、ジョブのリリース タスクを実行します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの最終更新時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.ListTasks(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="cloudJob.ListTasks (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.CloudTask">タスク</see>この<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を使用して非同期的または同期的にタスクの列挙をことができます。</returns>
        <remarks>このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアクション、ジョブ内のすべてのタスクがあるときにサービスが実行するバッチの設定、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />状態です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ジョブ内の任意のタスクが失敗したときに、バッチ サービスが実行するアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            タスクは、ゼロ以外の終了コードが完了し、再試行カウントが不足する場合は、またはスケジュール設定エラーが発生した場合に失敗したと見なされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolInformation PoolInformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolInformation PoolInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PoolInformation" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInformation As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInformation : Microsoft.Azure.Batch.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.CloudJob.PoolInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの以前の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ジョブが場合は、初期の<see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" />状態、PreviousState プロパティが定義されていません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブを直前の状態が入力された時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ジョブが場合は、初期の<see cref="F:Microsoft.Azure.Batch.Common.JobState.Active" />状態、PreviousStateTransitionTime プロパティが定義されていません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの優先順位を設定します。 優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は 0 です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。  詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJob.Id" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CloudJob/&lt;RefreshAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel">最新の更新の詳細レベルです。  詳細レベルを省略する場合、<see cref="P:Microsoft.Azure.Batch.CloudJob.Id" />プロパティを指定すると、更新は失敗します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            現在の更新<see cref="T:Microsoft.Azure.Batch.CloudJob" />です。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />非同期更新操作を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;" Usage="Microsoft.Azure.Batch.CloudJob.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの現在の状態を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.CloudJob.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブが現在の状態を入力する時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobStatistics Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Batch.JobStatistics" Usage="Microsoft.Azure.Batch.CloudJob.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの有効期間全体のリソース使用状況の統計を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            場合にのみ、このプロパティが設定されます、<see cref="T:Microsoft.Azure.Batch.CloudJob" />で取得した、 <see cref="P:Microsoft.Azure.Batch.ODATADetailLevel.ExpandClause" /> 'stats' 属性を含むそれ以外の場合は null を返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public void Terminate (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Terminate(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.Terminate(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Terminate (Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Terminate : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="cloudJob.Terminate (terminateReason, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="terminateReason">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <summary>
            これが終了<see cref="T:Microsoft.Azure.Batch.CloudJob" />、完了済みとしてマークすることです。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateAsync (string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateAsync(string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CloudJob.TerminateAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudJob.TerminateAsync (terminateReason, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="terminateReason">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CloudJob.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            これが終了<see cref="T:Microsoft.Azure.Batch.CloudJob" />、完了済みとしてマークすることです。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>終了操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.CloudJob.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ジョブの URL を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ジョブ内のタスクは相互に依存関係を定義することができるかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は false です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>