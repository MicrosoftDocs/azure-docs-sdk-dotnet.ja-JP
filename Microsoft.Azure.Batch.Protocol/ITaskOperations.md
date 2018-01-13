<Type Name="ITaskOperations" FullName="Microsoft.Azure.Batch.Protocol.ITaskOperations">
  <TypeSignature Language="C#" Value="public interface ITaskOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITaskOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ITaskOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITaskOperations" />
  <TypeSignature Language="F#" Value="type ITaskOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            TaskOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddCollectionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync (string jobId, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt; AddCollectionWithHttpMessagesAsync(string jobId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; value, class Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions taskAddCollectionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddCollectionWithHttpMessagesAsync(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter},Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddCollectionWithHttpMessagesAsync : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult, Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;" Usage="iTaskOperations.AddCollectionWithHttpMessagesAsync (jobId, value, taskAddCollectionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionResult,Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter&gt;" />
        <Parameter Name="taskAddCollectionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddCollectionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクのコレクションを追加するジョブの ID。
            </param>
        <param name="value">
            追加するタスクのコレクション。 このコレクションのシリアル化された合計サイズは 4 MB 未満である必要があります。 (たとえば、各タスクは 100 のリソース ファイルや環境変数の場合など)、4 MB を超える場合は、要求はコード 'RequestBodyTooLarge' で失敗し、タスクが削減再試行する必要があります。
            </param>
        <param name="taskAddCollectionOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブにタスクのコレクションを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            各タスクが必要となる一意の ID に注意してください。 バッチ サービスは、タスクがこの要求で送信された順序と同じ順序で各タスクの結果を返さない場合があります。 場合は、サーバーがタイムアウトするか、要求時に、接続が閉じられる、要求あった可能性があります部分的または完全に処理された、またはまったくです。 このような場合、ユーザーは再要求を発行する必要があります。 再要求を発行する際に、エラーを正しく処理するには、ユーザーの責任であることに注意してください。 たとえば、前の操作が成功した場合、再試行は作成されません余分なタスクが予期せずように再試行中に同じタスク Id を使用する必要があります。 応答の追加に失敗したすべてのタスクが含まれている場合、クライアントは要求を再試行できます。 再試行を追加し、最初の試行で正常に追加されたタスクを省略する場合に失敗したタスクのみを再送信する最も効率的です。 追加からタスクを完了するまでの最長有効期間は、7 日間です。
            バッチ サービスと左で終了されている追加の 7 日間、タスクが完了していない場合どのような状態での時点でします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt; AddWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter task, class Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions taskAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.AddWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter,Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter * Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;" Usage="iTaskOperations.AddWithHttpMessagesAsync (jobId, task, taskAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="task" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
        <Parameter Name="taskAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクを追加するジョブの ID。
            </param>
        <param name="task">
            追加するタスク。
            </param>
        <param name="taskAddOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions taskDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;" Usage="iTaskOperations.DeleteWithHttpMessagesAsync (jobId, taskId, taskDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクを削除するジョブの ID。
            </param>
        <param name="taskId">
            削除するタスクの ID。
            </param>
        <param name="taskDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask, class Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions taskGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask, Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;" Usage="iTaskOperations.GetWithHttpMessagesAsync (jobId, taskId, taskGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask,Microsoft.Azure.Batch.Protocol.Models.TaskGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクが含まれているジョブの ID。
            </param>
        <param name="taskId">
            情報を取得するタスクの ID。
            </param>
        <param name="taskGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions taskListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListNextWithHttpMessagesAsync (nextPageLink, taskListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="taskListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="taskListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSubtasksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt; ListSubtasksWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions taskListSubtasksOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListSubtasksWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSubtasksWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" Usage="iTaskOperations.ListSubtasksWithHttpMessagesAsync (jobId, taskId, taskListSubtasksOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskListSubtasksOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskId">
            タスクの ID。
            </param>
        <param name="taskListSubtasksOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, class Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt; ListWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.TaskListOptions taskListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ListWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.TaskListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.TaskListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;, Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;" Usage="iTaskOperations.ListWithHttpMessagesAsync (jobId, taskListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTask&gt;,Microsoft.Azure.Batch.Protocol.Models.TaskListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="taskListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
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
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReactivateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt; ReactivateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions taskReactivateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.ReactivateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReactivateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;" Usage="iTaskOperations.ReactivateWithHttpMessagesAsync (jobId, taskId, taskReactivateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskReactivateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskReactivateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskReactivateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            再アクティブ化するタスクの ID。
            </param>
        <param name="taskReactivateOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            許可することで、再試行カウントが使い果たされた場合でも、もう一度実行するタスクを再アクティブ化します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            再アクティブ化では、タスクがその最大再試行回数まで再試行の対象となります。 タスクの状態はアクティブに変更します。 タスクが完了した状態である不要になった、以前の終了コードまたはエラー情報は再アクティブ化の後に使用できなくします。 タスクの再アクティブ化するたびに、再試行カウントが 0 にリセットします。
            完了していない、または正常に (終了コード 0) の以前に完了したタスクを再アクティブ化は失敗します。
            さらに、ジョブが完了しました (が終了または削除する) 場合は失敗します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TerminateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions taskTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;" Usage="iTaskOperations.TerminateWithHttpMessagesAsync (jobId, taskId, taskTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="taskTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            タスクを含むジョブの ID。
            </param>
        <param name="taskId">
            タスクが終了するの ID。
            </param>
        <param name="taskTerminateOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したタスクを終了します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクが終了したとき、完了状態に移動します。
            マルチ インスタンスのタスクの終了タスク操作に適用されます同期的に主要なタスクです。サブタスクは、バック グラウンドで非同期的に終了します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, string taskId, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, string taskId, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions taskUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ITaskOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;" Usage="iTaskOperations.UpdateWithHttpMessagesAsync (jobId, taskId, constraints, taskUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="taskUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
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
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したタスクのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>