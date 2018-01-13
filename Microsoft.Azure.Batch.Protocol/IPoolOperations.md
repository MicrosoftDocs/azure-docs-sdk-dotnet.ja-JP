<Type Name="IPoolOperations" FullName="Microsoft.Azure.Batch.Protocol.IPoolOperations">
  <TypeSignature Language="C#" Value="public interface IPoolOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPoolOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IPoolOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPoolOperations" />
  <TypeSignature Language="F#" Value="type IPoolOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            PoolOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;" Usage="iPoolOperations.AddWithHttpMessagesAsync (pool, poolAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="pool">
            追加するプールです。
            </param>
        <param name="poolAddOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントにプールを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。 この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DeleteWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;" Usage="iPoolOperations.DeleteWithHttpMessagesAsync (poolId, poolDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            削除するプールの ID。
            </param>
        <param name="poolDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントからプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールが削除されることを要求すると、次の操作が行われますプールの状態が削除; に設定されている。プールで進行中のサイズ変更操作が停止しました。バッチ サービスの開始ノードをゼロにプールのサイズ変更既存のノードで実行されているすべてのタスクが終了し、(既定 requeue オプションを使用して要求された resize pool 操作) 場合、キューに再登録します。最後に、プールは、システムから削除されます。 実行中のタスクが再配置、ため、ユーザーは、別のプールを対象に、ジョブを更新することで、これらのタスクを再実行できます。 タスクは、新しいプールで実行できます。 キューの動作をオーバーライドする場合は、サイズがゼロにプールを削除する前に、プールを圧縮するには、明示的にサイズ変更のプールを呼び出す必要があります。 削除状態のプールの更新プログラム、修正または削除の API を呼び出す場合は、エラー コード PoolBeingDeleted HTTP ステータス コード 409 で失敗します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt; DisableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.DisableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.DisableAutoScaleWithHttpMessagesAsync (poolId, poolDisableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            自動スケーリングを無効にするプールの ID。
            </param>
        <param name="poolDisableAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの自動スケーリングを無効にします。
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
    <Member MemberName="EnableAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt; EnableAutoScaleWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EnableAutoScaleWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAutoScaleWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EnableAutoScaleWithHttpMessagesAsync (poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            自動スケーリングを有効にするプールの ID。
            </param>
        <param name="poolEnableAutoScaleParameter">
            要求のパラメーターです。
            </param>
        <param name="poolEnableAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの自動スケーリングを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。 プールの自動スケーリングが現在無効にした場合は、要求の一部として、有効な自動スケール式を指定する必要があります。 プールの自動スケーリングが既に有効になっている場合、新しい自動スケール式や新しい評価の間隔を指定する可能性があります。 30 秒ごとに 2 回以上で、同じプールのこの API を呼び出すことはできません。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync (string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt; EvaluateAutoScaleWithHttpMessagesAsync(string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EvaluateAutoScaleWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;" Usage="iPoolOperations.EvaluateAutoScaleWithHttpMessagesAsync (poolId, autoScaleFormula, poolEvaluateAutoScaleOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            自動スケーリング式を評価するプールの ID。
            </param>
        <param name="autoScaleFormula">
            プール内の計算ノードの必要な数の式。
            数式が検証されると、結果が計算されがプールには適用されません。 適用するには、数式をプールに 'を有効にするプールの自動スケーリングを' です。 この式の指定に関する詳細についてを参照して自動的に Azure Batch プール (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling) 内のノードをコンピューティング スケール。
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            自動の評価結果は、プール内の数式をスケーリングを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API は、自動スケール式を検証するため、主には、プールに、式を適用せず、結果が単純に返されるです。
            自動スケーリング式を評価するために有効になっている、プールが必要です。
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
    <Member MemberName="ExistsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;bool, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt; ExistsWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ExistsWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;bool, Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;" Usage="iPoolOperations.ExistsWithHttpMessagesAsync (poolId, poolExistsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Boolean,Microsoft.Azure.Batch.Protocol.Models.PoolExistsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolExistsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの基本プロパティを取得します。
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
    <Member MemberName="GetAllLifetimeStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt; GetAllLifetimeStatisticsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllLifetimeStatisticsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;" Usage="iPoolOperations.GetAllLifetimeStatisticsWithHttpMessagesAsync (poolGetAllLifetimeStatisticsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolGetAllLifetimeStatisticsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のプールのすべての有効期間の概要統計情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool, class Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool, Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;" Usage="iPoolOperations.GetWithHttpMessagesAsync (poolId, poolGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool,Microsoft.Azure.Batch.Protocol.Models.PoolGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールに関する情報を取得します。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListNextWithHttpMessagesAsync (nextPageLink, poolListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
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
    <Member MemberName="ListUsageMetricsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsNextWithHttpMessagesAsync (nextPageLink, poolListUsageMetricsNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListUsageMetricsNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。 指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。
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
    <Member MemberName="ListUsageMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt; ListUsageMetricsWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListUsageMetricsWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsageMetricsWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;" Usage="iPoolOperations.ListUsageMetricsWithHttpMessagesAsync (poolListUsageMetricsOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListUsageMetricsOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。 指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, class Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.PoolListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.PoolListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;, Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;" Usage="iPoolOperations.ListWithHttpMessagesAsync (poolListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;,Microsoft.Azure.Batch.Protocol.Models.PoolListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt; PatchWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.PatchWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;" Usage="iPoolOperations.PatchWithHttpMessagesAsync (poolId, poolPatchParameter, poolPatchOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolPatchParameter">
            要求のパラメーターです。
            </param>
        <param name="poolPatchOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これには、要求で指定されたプールのプロパティのみ置き換えられます。
            たとえば、プールに関連付けられている開始タスク、要求が開始タスク要素を指定しない場合は、既存の開始タスク保持プールにします。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt; RemoveNodesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.RemoveNodesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveNodesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;" Usage="iPoolOperations.RemoveNodesWithHttpMessagesAsync (poolId, nodeRemoveParameter, poolRemoveNodesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            ノードを削除するプールの ID。
            </param>
        <param name="nodeRemoveParameter">
            要求のパラメーターです。
            </param>
        <param name="poolRemoveNodesOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            削除は、指定したプールからノードを計算します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、プールの割り当ての状態が点灯している場合にのみ実行できます。 この操作を実行すると、割り当て状態の変更定常からサイズを変更します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt; ResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.ResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;" Usage="iPoolOperations.ResizeWithHttpMessagesAsync (poolId, poolResizeParameter, poolResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            サイズを変更するプールの ID です。
            </param>
        <param name="poolResizeParameter">
            要求のパラメーターです。
            </param>
        <param name="poolResizeOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールに割り当てられているコンピューティング ノードの数を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            割り当て状態が点灯しているときに、プールのサイズのみできます。 プールは既にサイズ変更、要求はステータス コードで失敗します。
            409. ときに、プールにある場合、プールの割り当ての状態の変更定常からサイズを変更するのには、サイズを変更します。 自動スケーリング用に構成されているプールのサイズを変更することはできません。 これを行うしようとすると、バッチ サービスはエラー 409 を返します。 起点、プールのサイズを変更する場合、バッチ サービスは削除するノードを選択します。 特定のノードを削除するには、代わりにプール削除ノード API を使用します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StopResizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt; StopResizeWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.StopResizeWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopResizeWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;" Usage="iPoolOperations.StopResizeWithHttpMessagesAsync (poolId, poolStopResizeOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            サイズを停止するプールの ID。
            </param>
        <param name="poolStopResizeOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            継続的な停止のサイズ変更、プールに操作します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。 停止後、プールが停止操作が完了するとではノードの数に安定します。 プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。 サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdatePropertiesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync (string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt; UpdatePropertiesWithHttpMessagesAsync(string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpdatePropertiesWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePropertiesWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;" Usage="iPoolOperations.UpdatePropertiesWithHttpMessagesAsync (poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolUpdatePropertiesParameter">
            要求のパラメーターです。
            </param>
        <param name="poolUpdatePropertiesOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これにより、プールのすべての更新可能なプロパティが完全に置き換えられます。 たとえば、開始タスクがこの要求に指定されていない場合、Batch service が解除され、プールに関連付けられている開始タスク、既存の開始タスク。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOSWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync (string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt; UpgradeOSWithHttpMessagesAsync(string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IPoolOperations.UpgradeOSWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpgradeOSWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;" Usage="iPoolOperations.UpgradeOSWithHttpMessagesAsync (poolId, targetOSVersion, poolUpgradeOSOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="poolId">
            アップグレードするプールの ID。
            </param>
        <param name="targetOSVersion">
            プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。
            </param>
        <param name="poolUpgradeOSOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールのオペレーティング システムをアップグレードします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アップグレード中は、バッチ サービス アップグレードは、プール内のノードを計算します。 アップグレードのコンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行キューに返されます。 アップグレードが完了するまで、ノードは使用できません。 ノードは、サービスのアップグレード対象として外すと、この演算の結果は一時的に削減プールの容量。 サービスが、すべてのアップグレードを回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行したがって、プールは一時的に実行できるようにタスクでない可能性があります。 この操作を実行するときにアップグレードする場合に、プールの状態を変更します。 すべてのコンピューティング ノードでは、アップグレードが完了したら、ときに、プールの状態をアクティブに返します。 アップグレードの進行状況では、プールの currentOSVersion は OS のバージョンから、ノードをアップグレードして、targetOSVersion ノードへのアップグレードは、OS のバージョンを反映することを反映します。 アップグレードが完了したら、currentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。 この操作は、cloudServiceConfiguration プロパティを使用して作成されたプールでのみ呼び出すことができます。
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