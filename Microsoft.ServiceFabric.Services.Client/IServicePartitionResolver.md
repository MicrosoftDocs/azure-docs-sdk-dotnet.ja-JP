<Type Name="IServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver">
  <TypeSignature Language="C#" Value="public interface IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type IServicePartitionResolver = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>
            サービス パーティション競合回避モジュールのインターフェイスを定義します。
            サービスの解決は、一連のパーティション内のレプリカのエンドポイントを検索するプロセスです。 サービス パーティションの競合回避モジュールでは、サービスの解決のロジックを実装します。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</param>
        <param name="resolveTimeoutPerTry">解決ごとのタイムアウトを再試行してください。</param>
        <param name="maxRetryBackoffInterval">
            再試行できない例外により、障害発生後、解像度を再試行する前にバックオフする間隔。
            </param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
          <para>
            再試行可能エラー時に指定したバックアップ/再試行設定で指定されたサービスの既に解決されたパーティションが再解決します。 このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。
            </para>
        </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理のサービスの解決操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="iServicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri">解決するのには、サービス インスタンスの名前です。</param>
        <param name="partitionKey">
          <para>
            <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。 <see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。
            </para>
        </param>
        <param name="resolveTimeoutPerTry">解決ごとのタイムアウトを再試行してください。</param>
        <param name="maxRetryBackoffInterval">
            再試行できない例外により、障害発生後、解像度を再試行する前にバックオフする間隔。
            </param>
        <param name="cancellationToken">
          <para>
            この CancellationToken は、この操作を確認します。 取り消す必要がある操作の通知に使用されます。
            </para>
        </param>
        <summary>
            再試行可能エラー時に指定したバックアップ/再試行設定で指定されたサービスのパーティションを解決します。
            </summary>
        <returns>
            A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理のサービスの解決操作を表すです。 タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>