<Type Name="IJobOperations" FullName="Microsoft.Azure.Batch.Protocol.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            JobOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobAddParameter job, class Microsoft.Azure.Batch.Protocol.Models.JobAddOptions jobAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;" Usage="iJobOperations.AddWithHttpMessagesAsync (job, jobAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
        <Parameter Name="jobAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job">
            追加するジョブです。
            </param>
        <param name="jobAddOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントに、ジョブを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            バッチ サービスでは、ジョブの一部として行われる処理を制御する 2 つの方法をサポートします。 最初の方法では、ユーザーは、ジョブ マネージャー タスクを指定します。 バッチ サービスは、ジョブを開始する準備ができたときに、このタスクを起動します。 ジョブ マネージャー タスクは、タスクの Api を使用して、このジョブで実行される他のすべてのタスクを制御します。 2 番目の方法で、ユーザーは直接タスク Api を使用してアクティブなジョブのタスクの実行を制御します。 注意してください。 ジョブの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。 この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions jobDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;" Usage="iJobOperations.DeleteWithHttpMessagesAsync (jobId, jobDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            削除するジョブの ID。
            </param>
        <param name="jobDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ジョブを削除すると、そのジョブの一部であるすべてのタスクとすべてのジョブの統計も削除されます。 タスクのデータの保有期間も上書きされます。つまり、ジョブにコンピューティング ノードで保持されているタスクが含まれている場合、バッチ サービスをそれらのタスクの作業ディレクトリとそのすべてのコンテンツを削除します。  ジョブの削除要求を受信すると、バッチ サービスは、削除の状態にジョブを設定します。 ジョブの状態を削除するのには上のすべての更新操作は、追加情報をジョブが削除されていることを示すステータス コード 409 (Conflict) で失敗します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt; DisableWithHttpMessagesAsync(string jobId, valuetype Microsoft.Azure.Batch.Protocol.Models.DisableJobOption disableTasks, class Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions jobDisableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.DisableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.DisableJobOption,Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.DisableJobOption * Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;" Usage="iJobOperations.DisableWithHttpMessagesAsync (jobId, disableTasks, jobDisableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobDisableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="disableTasks" Type="Microsoft.Azure.Batch.Protocol.Models.DisableJobOption" />
        <Parameter Name="jobDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobDisableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            無効にするジョブの ID。
            </param>
        <param name="disableTasks">
            ジョブに関連付けられているアクティブなタスクを行うには何か。 使用可能な値が含まれます: 'キューに再登録'、'終了'、'待機'
            </param>
        <param name="jobDisableOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいタスクの実行を妨げて、指定されたジョブを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            すぐに、Batch Service はジョブを無効化の状態に移動します。
            バッチは、この disableTasks パラメーターを使用して、ジョブの現在実行中のタスクを行うには何かを判断します。 ジョブ状態のまま残す無効にすると無効化操作が完了し、すべてのタスクが処理済み disableTasks オプション; に基づいてまでジョブは、無効の状態に移動します。 コンソール アプリケーションは、アクティブな状態に戻るまで、ジョブの下で、新しいタスクは開始されません。 Active 以外の任意の状態になっているジョブを無効にしようとすると、無効化または無効にされた、要求が失敗したステータス コード 409 でします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EnableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt; EnableWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions jobEnableOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.EnableWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;" Usage="iJobOperations.EnableWithHttpMessagesAsync (jobId, jobEnableOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobEnableHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobEnableOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            有効にするジョブの ID。
            </param>
        <param name="jobEnableOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            新しいタスクの実行を許可する、指定されたジョブを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API を呼び出すときに、バッチ サービスは、有効にすると、状態を無効になっているジョブを設定します。 この後、ジョブはアクティブ状態、およびジョブの再開での新しいタスクのスケジュール に移動操作を完了すると、します。 バッチ サービスでは、7 日間を超えてアクティブ状態のままにして、タスクは許可されません。 そのため、7 日以上前に追加されたアクティブなタスクを含むジョブを有効にすると、それらのタスクは実行されません。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.JobStatistics, class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions jobGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics, Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iJobOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (jobGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobStatistics,Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobGetAllLifetimeStatisticsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のジョブのすべての有効期間の概要統計情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのジョブで集計されます。
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
    <Member MemberName="GetTaskCountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskCounts, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt; GetTaskCountsWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions jobGetTaskCountsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetTaskCountsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTaskCountsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts, Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;" Usage="iJobOperations.GetTaskCountsWithHttpMessagesAsync (jobId, jobGetTaskCountsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.TaskCounts,Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetTaskCountsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetTaskCountsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="jobGetTaskCountsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたジョブのタスクの数を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            タスクの数は、アクティブな実行中または完了したタスクの状態によって、タスクの数と、成功または失敗したタスクの数を提供します。 準備状態のタスクが実行中としてカウントされます。 ValidationStatus が検証済みでない場合、Batch サービスがされていませんリスト タスク API で報告されるタスクの状態に対して状態の数を確認できません。 ジョブには、200,000 以上のタスクが含まれている場合に、validationStatus を検証できない可能性があります。
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob, class Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobGetOptions jobGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob, Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;" Usage="iJobOperations.GetWithHttpMessagesAsync (jobId, jobGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob,Microsoft.Azure.Batch.Protocol.Models.JobGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="jobGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="ListFromJobScheduleNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions jobListFromJobScheduleNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleNextWithHttpMessagesAsync (nextPageLink, jobListFromJobScheduleNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="jobListFromJobScheduleNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="ListFromJobScheduleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync (string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt; ListFromJobScheduleWithHttpMessagesAsync(string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions jobListFromJobScheduleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListFromJobScheduleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFromJobScheduleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;" Usage="iJobOperations.ListFromJobScheduleWithHttpMessagesAsync (jobScheduleId, jobListFromJobScheduleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobListFromJobScheduleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListFromJobScheduleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId">
            ジョブの一覧を取得するジョブのスケジュールの ID。
            </param>
        <param name="jobListFromJobScheduleOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブ スケジュール の下に作成されたジョブを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions jobListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListNextWithHttpMessagesAsync (nextPageLink, jobListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="jobListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions jobListPreparationAndReleaseTaskStatusNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusNextWithHttpMessagesAsync (nextPageLink, jobListPreparationAndReleaseTaskStatusNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。 これには、プールからからは削除されているノードが含まれます。 この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。
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
    <Member MemberName="ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt; ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions jobListPreparationAndReleaseTaskStatusOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;" Usage="iJobOperations.ListPreparationAndReleaseTaskStatusWithHttpMessagesAsync (jobId, jobListPreparationAndReleaseTaskStatusOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobListPreparationAndReleaseTaskStatusOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListPreparationAndReleaseTaskStatusOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            ジョブの ID。
            </param>
        <param name="jobListPreparationAndReleaseTaskStatusOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            ジョブの実行のコンピューティング ノードで指定されたジョブのジョブの準備とジョブのリリース タスクの実行状態を一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API は、ジョブの準備またはジョブのリリース タスクを実行したすべてのコンピューティング ノードでジョブの準備とジョブのリリース タスクの状態を返します。 これには、プールからからは削除されているノードが含まれます。 この API は、ジョブの準備またはジョブのリリース タスクがないジョブで呼び出される、Batch service は JobPreparationTaskNotSpecified のエラー コードの HTTP ステータス コード 409 (Conflict) を返します。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, class Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.JobListOptions jobListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.JobListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.JobListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;, Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;" Usage="iJobOperations.ListWithHttpMessagesAsync (jobListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJob&gt;,Microsoft.Azure.Batch.Protocol.Models.JobListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のジョブのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
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
    <Member MemberName="PatchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter jobPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions jobPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;" Usage="iJobOperations.PatchWithHttpMessagesAsync (jobId, jobPatchParameter, jobPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
        <Parameter Name="jobPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            プロパティを更新するジョブの ID。
            </param>
        <param name="jobPatchParameter">
            要求のパラメーターです。
            </param>
        <param name="jobPatchOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これには、要求で指定されたジョブのプロパティのみが置き換えられます。 たとえば、ジョブの制約には、要求が制約要素を指定しない場合は、既存の制約維持ジョブにします。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync (string jobId, string terminateReason = null, Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt; TerminateWithHttpMessagesAsync(string jobId, string terminateReason, class Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions jobTerminateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.TerminateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TerminateWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;" Usage="iJobOperations.TerminateWithHttpMessagesAsync (jobId, terminateReason, jobTerminateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobTerminateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="terminateReason" Type="System.String" />
        <Parameter Name="jobTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobTerminateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            終了するジョブの ID。
            </param>
        <param name="terminateReason">
            ジョブの TerminateReason として表示するテキストです。 既定値は、'UserTerminate' です。
            </param>
        <param name="jobTerminateOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            完了としてマークして、指定されたジョブを終了します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ジョブの終了要求を受信すると、Batch service はジョブを最終状態に設定します。 バッチ サービスは、ジョブに関連付けられているアクティブなまたは実行中のタスクを終了し、必要なジョブのリリース タスクを実行します。 ジョブは、完了した状態に移動します。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (string jobId, Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(string jobId, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter jobUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions jobUpdateOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IJobOperations.UpdateWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;" Usage="iJobOperations.UpdateWithHttpMessagesAsync (jobId, jobUpdateParameter, jobUpdateOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.JobUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="jobUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateParameter" />
        <Parameter Name="jobUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobUpdateOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">
            プロパティを更新するジョブの ID。
            </param>
        <param name="jobUpdateParameter">
            要求のパラメーターです。
            </param>
        <param name="jobUpdateOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したジョブのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これにより、ジョブのすべての更新可能なプロパティが完全に置き換えられます。 たとえば、ジョブに関連付けられている制約が設定されている場合、この要求に制約が指定されていない場合、Batch service、既存の制約は削除します。
            </remarks>
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