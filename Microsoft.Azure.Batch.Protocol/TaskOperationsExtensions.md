<Type Name="TaskOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TaskOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TaskOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TaskOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TaskOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TaskOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Add (operations, jobId, task, taskAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを追加するジョブの ID。
            </param>
        <param name="task">
            追加するタスク。
            </param>
        <param name="taskAddOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたジョブにタスクを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            追加からタスクを完了するまでの最長有効期間は、7 日間です。 バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddAsync (operations, jobId, task, taskAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを追加するジョブの ID。
            </param>
        <param name="task">
            追加するタスク。
            </param>
        <param name="taskAddOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブにタスクを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            追加からタスクを完了するまでの最長有効期間は、7 日間です。 バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult AddCollection(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions)" />
      <MemberSignature Language="F#" Value="static member AddCollection : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollection (operations, jobId, value, taskAddCollectionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクのコレクションを追加するジョブの ID。
            </param>
        <param name="value">
            追加するタスクのコレクション。 このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。 (たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。
            </param>
        <param name="taskAddCollectionOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたジョブにタスクのコレクションを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            各タスクが必要となる一意の ID に注意してください。 バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。 場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。 このような場合、ユーザーは再要求を発行する必要があります。 再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。
            たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。 応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。 再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。 追加からタスクを完了するまでの最長有効期間は、7 日間です。 バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddCollectionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt; AddCollectionAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddCollectionAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.AddCollectionAsync (operations, jobId, value, taskAddCollectionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;AddCollectionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクのコレクションを追加するジョブの ID。
            </param>
        <param name="value">
            追加するタスクのコレクション。 このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。 (たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。
            </param>
        <param name="taskAddCollectionOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブにタスクのコレクションを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            各タスクが必要となる一意の ID に注意してください。 バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。 場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。 このような場合、ユーザーは再要求を発行する必要があります。 再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。
            たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。 応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。 再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。 追加からタスクを完了するまでの最長有効期間は、7 日間です。 バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Delete (operations, jobId, taskId, taskDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを削除するジョブの ID。
            </param>
        <param name="taskId">
            削除するタスクの ID。
            </param>
        <param name="taskDeleteOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたジョブからタスクを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクを削除すると、すべての行く先コンピューティング ノード上のディレクトリにファイルの (時刻に関係なく、保有期間) も削除されます。 マルチ インスタンスのタスクの削除タスクの操作に適用されます同期的に主要なタスクです。サブタスクとそのファイルに非同期的に、バック グラウンドでは削除し、されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.DeleteAsync (operations, jobId, taskId, taskDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを削除するジョブの ID。
            </param>
        <param name="taskId">
            削除するタスクの ID。
            </param>
        <param name="taskDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブからタスクを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクを削除すると、すべての行く先コンピューティング ノード上のディレクトリにファイルの (時刻に関係なく、保有期間) も削除されます。 マルチ インスタンスのタスクの削除タスクの操作に適用されます同期的に主要なタスクです。サブタスクとそのファイルに非同期的に、バック グラウンドでは削除し、されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTask Get (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTask Get(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTask" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Get (operations, jobId, taskId, taskGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTask</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクが含まれているジョブの ID。
            </param>
        <param name="taskId">
            情報を取得するタスクの ID。
            </param>
        <param name="taskGetOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたタスクに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.GetAsync (operations, jobId, taskId, taskGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクが含まれているジョブの ID。
            </param>
        <param name="taskId">
            情報を取得するタスクの ID。
            </param>
        <param name="taskGetOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたタスクに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; List(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.List (operations, jobId, taskListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskListOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定されたジョブに関連付けられているタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListAsync (operations, jobId, taskListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskListOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定されたジョブに関連付けられているタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNext (operations, nextPageLink, taskListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="taskListNextOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定されたジョブに関連付けられているタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListNextAsync (operations, nextPageLink, taskListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="taskListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定されたジョブに関連付けられているタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            複数インスタンスのタスク、affinityId などの情報の executionInfo と nodeInfo は、主要なタスクを参照してください。 一覧のサブタスク API を使用して、サブタスクについての情報を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult ListSubtasks(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions)" />
      <MemberSignature Language="F#" Value="static member ListSubtasks : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasks (operations, jobId, taskId, taskListSubtasksOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskId">
            タスクの ID。
            </param>
        <param name="taskListSubtasksOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての複数インスタンスの指定したタスクに関連付けられているサブタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクがタスクを複数のインスタンスではない場合この空のコレクションを返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt; ListSubtasksAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSubtasksAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ListSubtasksAsync (operations, jobId, taskId, taskListSubtasksOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ListSubtasksAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskId">
            タスクの ID。
            </param>
        <param name="taskListSubtasksOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての複数インスタンスの指定したタスクに関連付けられているサブタスクの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクがタスクを複数のインスタンスではない場合この空のコレクションを返します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reactivate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders Reactivate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions)" />
      <MemberSignature Language="F#" Value="static member Reactivate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Reactivate (operations, jobId, taskId, taskReactivateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            再アクティブ化するタスクの ID。
            </param>
        <param name="taskReactivateOptions">
            操作の追加パラメーター
            </param>
        <summary>
            許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。 タスクの状態はアクティブに変更します。 タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。 タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。 完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。 さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReactivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt; ReactivateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReactivateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.ReactivateAsync (operations, jobId, taskId, taskReactivateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;ReactivateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            再アクティブ化するタスクの ID。
            </param>
        <param name="taskReactivateOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。 タスクの状態はアクティブに変更します。 タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。 タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。 完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。 さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Terminate (operations, jobId, taskId, taskTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            タスクが終了するの ID。
            </param>
        <param name="taskTerminateOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したタスクを終了します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクが終了したとき、完了状態に移動します。 マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.TerminateAsync (operations, jobId, taskId, taskTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            タスクが終了するの ID。
            </param>
        <param name="taskTerminateOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したタスクを終了します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクが終了したとき、完了状態に移動します。 マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.Update (operations, jobId, taskId, constraints, taskUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            更新するタスクの ID。
            </param>
        <param name="constraints">
            このタスクに適用される制約します。 省略した場合、タスクは、既定の制約を付与します。 複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。
            </param>
        <param name="taskUpdateOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したタスクのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.ITaskOperations operations, string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.ITaskOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.ITaskOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions.UpdateAsync (operations, jobId, taskId, constraints, taskUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.TaskOperationsExtensions/&lt;UpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ITaskOperations" RefType="this" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            更新するタスクの ID。
            </param>
        <param name="constraints">
            このタスクに適用される制約します。 省略した場合、タスクは、既定の制約を付与します。 複数インスタンスの作業、リテンション期間を更新、主要なタスクにのみ適用されますおよびサブタスクがありません。
            </param>
        <param name="taskUpdateOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したタスクのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>