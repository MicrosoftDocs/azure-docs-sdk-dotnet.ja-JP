<Type Name="JobOperations" FullName="Microsoft.Azure.Batch.JobOperations">
  <TypeSignature Language="C#" Value="public class JobOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type JobOperations = class&#xA;    interface IInheritedBehaviors" />
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
  </Interfaces>
  <Docs>
    <summary>
            Azure Batch のジョブで操作を実行します。
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Batch.CloudJob" />
  </Docs>
  <Members>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; AddTask(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTask (jobId As String, taskToAdd As CloudTask, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As ConcurrentDictionary(Of Type, IFileStagingArtifact)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * Microsoft.Azure.Batch.CloudTask * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;" Usage="jobOperations.AddTask (jobId, taskToAdd, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを追加するジョブの id。</param>
        <param name="taskToAdd">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            ジョブを 1 つのタスクを追加します。  複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。
            </summary>
        <returns>ステージング処理ファイルに関する情報のコレクション (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</returns>
        <remarks>
          <para>このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。 したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。
            場合は、これらの操作の多くの並列で実行し、クライアント側のタイムアウトが表示される、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください、複数のタスクAddTask のオーバー ロードします。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTask">
      <MemberSignature Language="C#" Value="public void AddTask (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddTask(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTask(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddTask (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.AddTask : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.AddTask (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを追加するジョブの id。</param>
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
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            ジョブにタスクを追加します。
            </summary>
        <remarks>
          <para>これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />です。</para>
          <para>このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。 追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。  に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</para>
          <para>Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。
            これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合とは、クライアント側のタイムアウト、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</para>
          <para>エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。
            通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。
            この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, Microsoft.Azure.Batch.CloudTask taskToAdd, System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class Microsoft.Azure.Batch.CloudTask taskToAdd, class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt; allFileStagingArtifacts, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * Microsoft.Azure.Batch.CloudTask * System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, taskToAdd, allFileStagingArtifacts, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskToAdd" Type="Microsoft.Azure.Batch.CloudTask" />
        <Parameter Name="allFileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを追加するジョブの id。</param>
        <param name="taskToAdd">追加する <see cref="T:Microsoft.Azure.Batch.CloudTask" />。</param>
        <param name="allFileStagingArtifacts">オプションのコレクションをカスタマイズし、ステージング処理ファイルに関する情報を受け取ります (を参照してください<see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />)。
            詳細については、「<see cref="T:Microsoft.Azure.Batch.IFileStagingArtifact" />」を参照してください。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ジョブを 1 つのタスクを追加します。  複数のタスクを追加する<see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see>です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>このメソッドを呼び出すたびには、バッチ サービスへの要求が発生します。 したがって、このメソッドを使用して、複数のタスクが一括を使用するよりも効率の低いを追加するメソッドを追加し、HTTP 接続の制限が発生することができます。
            場合は、これらの操作の多くの並列で実行し、クライアント側のタイムアウトが表示される、http://msdn.microsoft.com/en-us/library/system.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx を参照してくださいか使用してください、複数のタスクAddTaskAsync のオーバー ロードします。</para>
          <para>タスクの追加操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddTaskAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions = null, System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts = null, Nullable&lt;TimeSpan&gt; timeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AddTaskAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToAdd, class Microsoft.Azure.Batch.BatchClientParallelOptions parallelOptions, class System.Collections.Concurrent.ConcurrentBag`1&lt;class System.Collections.Concurrent.ConcurrentDictionary`2&lt;class System.Type, class Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; fileStagingArtifacts, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function AddTaskAsync (jobId As String, tasksToAdd As IEnumerable(Of CloudTask), Optional parallelOptions As BatchClientParallelOptions = null, Optional fileStagingArtifacts As ConcurrentBag(Of ConcurrentDictionary(Of Type, IFileStagingArtifact)) = null, Optional timeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.AddTaskAsync : string * seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.BatchClientParallelOptions * System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;Type, Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="jobOperations.AddTaskAsync (jobId, tasksToAdd, parallelOptions, fileStagingArtifacts, timeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;AddTaskAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="tasksToAdd" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="parallelOptions" Type="Microsoft.Azure.Batch.BatchClientParallelOptions" />
        <Parameter Name="fileStagingArtifacts" Type="System.Collections.Concurrent.ConcurrentBag&lt;System.Collections.Concurrent.ConcurrentDictionary&lt;System.Type,Microsoft.Azure.Batch.IFileStagingArtifact&gt;&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを追加するジョブの id。</param>
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
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            ジョブにタスクを追加します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>タスクの追加操作は非同期的に実行されます。</para>
          <para>このメソッドは、アトミックです。つまり、メソッドがタスクの追加を開始し、失敗する可能性です。 追加するタスクのコレクションに分割されるサイズのチャンク多くて<see cref="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />、各チャンクに対して AddTaskCollection 要求が実行されたとします。  に従って並列で要求を発行することがあります、<paramref name="parallelOptions" />です。</para>
          <para>Batch service への多数の同時要求の発行と、HTTP 接続の制限が発生することができます。
            これらの操作の多くを並列で実行中 (または、parallelOptions で大きな MaxDegreeOfParallelism を指定した) 場合とは、クライアント側のタイムアウト、http://msdn.microsoft.com/en-us/library/ を参照してくださいsystem.net.servicepointmanager.defaultconnectionlimit%28v=vs.110%29.aspx です。</para>
          <para>エラーが発生した場合、操作の進行状況は、によって決まります<see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" />動作します。
            通常、クライアントは、通常の状況で動作する、既定値を使用してバッチとして、この動作を指定する必要はありません。
            この動作をカスタマイズする場合、AddTaskCollectionResultHandler 内の指定、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />または<paramref name="additionalBehaviors" />コレクション。</para>
        </remarks>
        <exception cref="T:Microsoft.Azure.Batch.ParallelOperationsException">Batch service への 1 つまたは複数の要求が失敗した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateJob () As CloudJob" />
      <MemberSignature Language="F#" Value="member this.CreateJob : unit -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            バインドが、バッチ サービスで任意のジョブを整合性のリレーションシップを持たない CloudJob のインスタンスを作成します。
            </summary>
        <returns>A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> Batch service への送信されていないかの新しいジョブを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob CreateJob (string jobId, Microsoft.Azure.Batch.PoolInformation poolInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob CreateJob(string jobId, class Microsoft.Azure.Batch.PoolInformation poolInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.CreateJob(System.String,Microsoft.Azure.Batch.PoolInformation)" />
      <MemberSignature Language="F#" Value="member this.CreateJob : string * Microsoft.Azure.Batch.PoolInformation -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.CreateJob (jobId, poolInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="poolInformation" Type="Microsoft.Azure.Batch.PoolInformation" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの Id。</param>
        <param name="poolInformation">プールの情報、ジョブが実行されます。</param>
        <summary>
            バインドが、バッチ サービスで任意のジョブを整合性のリレーションシップを持たない CloudJob のインスタンスを作成します。
            </summary>
        <returns>A <see cref="T:Microsoft.Azure.Batch.CloudJob" /> Batch service への送信されていないかの新しいジョブを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />
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
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.JobOperations" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJob">
      <MemberSignature Language="C#" Value="public void DeleteJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteJob (jobId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したジョブを削除します。
            </summary>
        <remarks>
          <para>削除操作は、ジョブを削除することを要求します。  要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteJobAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したジョブを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>削除操作は、ジョブを削除することを要求します。  要求、ジョブを格納する、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            バッチ サービスは、実行中のタスクを停止し、さらにクライアント操作をしなくても、実際のジョブの削除を実行します。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFile">
      <MemberSignature Language="C#" Value="public void DeleteNodeFile (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNodeFile(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFile(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNodeFile (jobId As String, taskId As String, filePath As String, Optional recursive As Nullable(Of Boolean) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFile : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteNodeFile (jobId, taskId, filePath, recursive, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="filePath">削除するファイルのパス。</param>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            コンピューティング ノードでこのタスクのディレクトリから指定されたファイルを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>これは、ブロッキング操作です。  非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNodeFileAsync (string jobId, string taskId, string filePath, Nullable&lt;bool&gt; recursive = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNodeFileAsync(string jobId, string taskId, string filePath, valuetype System.Nullable`1&lt;bool&gt; recursive, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteNodeFileAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNodeFileAsync : string * string * string * Nullable&lt;bool&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteNodeFileAsync (jobId, taskId, filePath, recursive, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DeleteNodeFileAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="filePath">削除するファイルのパス。</param>
        <param name="recursive">
            ファイル パスのパラメーターは、ファイルの代わりにディレクトリを表している場合にディレクトリを削除するには、省略可能な再帰的なパラメーターをすべてのファイルとサブディレクトリを設定できます。 再帰が false の場合、ディレクトリを空にする必要がありますか、削除は失敗します。
            </param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードでこのタスクのディレクトリから指定されたファイルを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>削除操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTask">
      <MemberSignature Language="C#" Value="public void DeleteTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DeleteTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したタスクを削除します。
            </summary>
        <remarks>これは、ブロッキング操作です。  非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DeleteTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DeleteTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したタスクを削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>削除操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJob">
      <MemberSignature Language="C#" Value="public void DisableJob (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableJob(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJob(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.DisableJob : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.DisableJob (jobId, disableJobOption, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="disableJobOption">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したジョブを無効にします。  無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableJobAsync (string jobId, Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableJobAsync(string jobId, valuetype Microsoft.Azure.Batch.Common.DisableJobOption disableJobOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.DisableJobAsync(System.String,Microsoft.Azure.Batch.Common.DisableJobOption,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableJobAsync : string * Microsoft.Azure.Batch.Common.DisableJobOption * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.DisableJobAsync (jobId, disableJobOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;DisableJobAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableJobOption" Type="Microsoft.Azure.Batch.Common.DisableJobOption" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="disableJobOption">ジョブに関連付けられているアクティブなタスクを行うには新機能を指定します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したジョブを無効にします。  無効なジョブは、新しいタスクを実行しないでくださいが、後で再度有効ことがあります。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>無効化操作が非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJob">
      <MemberSignature Language="C#" Value="public void EnableJob (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableJob(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJob(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableJob (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableJob : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.EnableJob (jobId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            新しいタスクの実行を許可する、指定されたジョブを有効にします。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableJobAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableJobAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.EnableJobAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableJobAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.EnableJobAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;EnableJobAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            新しいタスクの実行を許可する、指定されたジョブを有効にします。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>有効にする操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.JobStatistics GetAllLifetimeStatistics(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatistics(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAllLifetimeStatistics (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatistics : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.JobStatistics" Usage="jobOperations.GetAllLifetimeStatistics additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            ジョブの現在のアカウント内のすべての有効期間の概要統計情報を取得します。  
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。 
            </summary>
        <returns>集計されたジョブの統計。</returns>
        <remarks>これは、ブロッキング操作です。非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.JobStatistics&gt; GetAllLifetimeStatisticsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetAllLifetimeStatisticsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetAllLifetimeStatisticsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;" Usage="jobOperations.GetAllLifetimeStatisticsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetAllLifetimeStatisticsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.JobStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            ジョブの現在のアカウント内のすべての有効期間の概要統計情報を取得します。  
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。 
            </summary>
        <returns>集計されたジョブの統計。</returns>
        <remarks>統計情報の取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJob GetJob (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJob GetJob(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJob(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetJob : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudJob" Usage="jobOperations.GetJob (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">取得するジョブの id です。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudJob" />指定した Azure Batch のジョブに関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; GetJobAsync(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.GetJobAsync (jobId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">取得するジョブの id です。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudJob" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudJob" />指定した Azure Batch のジョブに関する情報を格納します。</returns>
        <remarks>Get job 操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskCounts GetJobTaskCounts(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCounts(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetJobTaskCounts (jobId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As TaskCounts" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCounts : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.TaskCounts" Usage="jobOperations.GetJobTaskCounts (jobId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定されたジョブのタスクの数を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobTaskCountsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync (string jobId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.TaskCounts&gt; GetJobTaskCountsAsync(string jobId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetJobTaskCountsAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobTaskCountsAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;" Usage="jobOperations.GetJobTaskCountsAsync (jobId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;GetJobTaskCountsAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.TaskCounts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定されたジョブのタスクの数を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.TaskCounts" />ジョブのカウントをタスクを含むオブジェクトします。</returns>
        <remarks>ジョブのタスクの取得は、非同期的に操作の実行をカウントします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFile(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (jobId As String, taskId As String, filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="jobOperations.GetNodeFile (jobId, taskId, filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />コンピューティング ノードで、指定したタスクのディレクトリからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</returns>
        <remarks>これは、ブロッキング操作です。  非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string jobId, string taskId, string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string jobId, string taskId, string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetNodeFileAsync(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.GetNodeFileAsync (jobId, taskId, filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="filePath">取得するファイルのパス。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された取得<see cref="T:Microsoft.Azure.Batch.NodeFile" />コンピューティング ノードで、指定したタスクのディレクトリからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.NodeFile" />を表す、指定したファイルです。</returns>
        <remarks>ファイルの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudTask GetTask (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudTask GetTask(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTask(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetTask : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudTask" Usage="jobOperations.GetTask (jobId, taskId, detailLevel, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを取得するジョブの id。</param>
        <param name="taskId">取得するためのタスクの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; GetTaskAsync(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.GetTaskAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTaskAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.GetTaskAsync (jobId, taskId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを取得するジョブの id。</param>
        <param name="taskId">取得するためのタスクの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.CloudTask" /> を取得します。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.CloudTask" />指定した Azure Batch のタスクに関する情報を格納します。</returns>
        <remarks>タスクの取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobPreparationAndReleaseTaskStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt; ListJobPreparationAndReleaseTaskStatus(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobPreparationAndReleaseTaskStatus(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobPreparationAndReleaseTaskStatus : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;" Usage="jobOperations.ListJobPreparationAndReleaseTaskStatus (jobId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.JobPreparationAndReleaseTaskExecutionInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            状態を列挙します<see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask" />と<see cref="P:Microsoft.Azure.Batch.CloudJob.JobReleaseTask" />指定されたジョブのタスクです。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的にステータスの列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るこれらの状態は、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。状態は、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListJobs(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobOperations.ListJobs (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.CloudJob">ジョブ</see>Batch アカウントにします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、ジョブを列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るジョブは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。ジョブは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (string jobId, string taskId, Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(string jobId, string taskId, valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListNodeFiles(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="jobOperations.ListNodeFiles (jobId, taskId, recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="recursive">True の場合は、タスクのすべてのファイルの再帰的な一覧を実行します。 False の場合は、タスクのルート ディレクトリにファイルのみを返します。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、 <see cref="T:Microsoft.Azure.Batch.NodeFile">NodeFiles</see>コンピューティング ノードで、指定したタスクのディレクトリにします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />ファイルを列挙する非同期的または同期的に使用できます。</returns>
        <remarks>このメソッドがすぐに戻るファイル データは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。ファイル データは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks (string jobId, string taskId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.SubtaskInformation&gt; ListSubtasks(string jobId, string taskId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListSubtasks(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListSubtasks : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;" Usage="jobOperations.ListSubtasks (jobId, taskId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.SubtaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="taskId">取得するためのタスクの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.SubtaskInformation">サブタスクについて</see>指定したタスク。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />サブタスクを非同期的または同期的に列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTasks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; ListTasks (string jobId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; ListTasks(string jobId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ListTasks(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListTasks : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" Usage="jobOperations.ListTasks (jobId, detailLevel, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.CloudTask">タスク</see>の指定されたジョブです。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を使用して非同期的または同期的にタスクの列挙をことができます。</returns>
        <remarks>このメソッドがすぐに戻るタスクは、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。タスクは、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTask">
      <MemberSignature Language="C#" Value="public void ReactivateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ReactivateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub ReactivateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.ReactivateTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。
            </summary>
        <remarks>
          <para>
            再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。
            </para>
          <para>
            この操作は完了していない、または正常に (終了コード 0) の以前に完了したタスクを失敗します。
            </para>
          <para>
            さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReactivateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReactivateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReactivateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.ReactivateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>
            再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。
            </para>
          <para>
            さらは失敗しますが、ジョブの場合、<see cref="F:Microsoft.Azure.Batch.Common.JobState.Completed" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />または<see cref="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />状態です。
            これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.ReactivateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。
            </para>
          <para>
            再アクティブ化操作が非同期的に実行されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJob">
      <MemberSignature Language="C#" Value="public void TerminateJob (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateJob(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJob(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateJob (jobId As String, Optional terminateReason As String = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateJob : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateJob (jobId, terminateReason, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="terminateReason">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            完了としてマークして、指定されたジョブを終了します。
            </summary>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateJobAsync (string jobId, string terminateReason = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateJobAsync(string jobId, string terminateReason, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateJobAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateJobAsync (jobId, terminateReason, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobOperations/&lt;TerminateJobAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの id。</param>
        <param name="terminateReason">ジョブのとして表示するテキスト<see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" />です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            完了としてマークして、指定されたジョブを終了します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>終了操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTask">
      <MemberSignature Language="C#" Value="public void TerminateTask (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateTask(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTask(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateTask (jobId As String, taskId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateTask : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobOperations.TerminateTask (jobId, taskId, additionalBehaviors)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <summary>
            指定したタスクを終了します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>これは、ブロッキング操作です。  非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateTaskAsync (string jobId, string taskId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateTaskAsync(string jobId, string taskId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobOperations.TerminateTaskAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateTaskAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOperations.TerminateTaskAsync (jobId, taskId, additionalBehaviors, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">タスクを含むジョブの ID です。</param>
        <param name="taskId">タスクの ID です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.JobOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定したタスクを終了します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>終了操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>