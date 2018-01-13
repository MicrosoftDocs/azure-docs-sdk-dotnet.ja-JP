<Type Name="PoolOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PoolOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PoolOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PoolOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PoolOperationsExtensions = class" />
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
            PoolOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Add (operations, pool, poolAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="pool">
            追加するプールです。
            </param>
        <param name="poolAddOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウントにプールを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールの名前を付けるときは、ユーザー名またはシークレット プロジェクト名などの機密情報が含まれないようにします。 この情報は、Microsoft サポート エンジニアにアクセスできる製品利用統計情報ログに表示可能性があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter pool, class Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions poolAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter,Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter * Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.AddAsync (operations, pool, poolAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;AddAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="pool" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddParameter" />
        <Parameter Name="poolAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="pool">
            追加するプールです。
            </param>
        <param name="poolAddOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Delete (operations, poolId, poolDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            削除するプールの ID。
            </param>
        <param name="poolDeleteOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウントからプールを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールが削除されることを要求すると、次の操作が行われますプールの状態が削除; に設定されている。プールで進行中のサイズ変更操作が停止しました。バッチ サービスの開始ノードをゼロにプールのサイズ変更既存のノードで実行されているすべてのタスクが終了し、(既定 requeue オプションを使用して要求された resize pool 操作) 場合、キューに再登録します。最後に、プールは、システムから削除されます。 実行中のタスクが再配置、ため、ユーザーは、別のプールを対象に、ジョブを更新することで、これらのタスクを再実行できます。 タスクは、新しいプールで実行できます。 キューの動作をオーバーライドする場合は、サイズがゼロにプールを削除する前に、プールを圧縮するには、明示的にサイズ変更のプールを呼び出す必要があります。 削除状態のプールの更新プログラム、修正または削除の API を呼び出す場合は、エラー コード PoolBeingDeleted HTTP ステータス コード 409 で失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions poolDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DeleteAsync (operations, poolId, poolDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            削除するプールの ID。
            </param>
        <param name="poolDeleteOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders DisableAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders DisableAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScale (operations, poolId, poolDisableAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリングを無効にするプールの ID。
            </param>
        <param name="poolDisableAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <summary>
            プールの自動スケーリングを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt; DisableAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt; DisableAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions poolDisableAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.DisableAutoScaleAsync (operations, poolId, poolDisableAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;DisableAutoScaleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolDisableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolDisableAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリングを無効にするプールの ID。
            </param>
        <param name="poolDisableAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの自動スケーリングを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders EnableAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders EnableAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member EnableAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScale (operations, poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリングを有効にするプールの ID。
            </param>
        <param name="poolEnableAutoScaleParameter">
            要求のパラメーターです。
            </param>
        <param name="poolEnableAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <summary>
            プールの自動スケーリングを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            サイズ変更操作が、プールで進行中の場合は、プールで自動スケーリングを有効にすることはできません。 プールの自動スケーリングが現在無効にした場合は、要求の一部として、有効な自動スケール式を指定する必要があります。 プールの自動スケーリングが既に有効になっている場合、新しい自動スケール式や新しい評価の間隔を指定する可能性があります。 30 秒ごとに 2 回以上で、同じプールのこの API を呼び出すことはできません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt; EnableAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt; EnableAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter poolEnableAutoScaleParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions poolEnableAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter,Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter * Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EnableAutoScaleAsync (operations, poolId, poolEnableAutoScaleParameter, poolEnableAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;EnableAutoScaleAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolEnableAutoScaleParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleParameter" />
        <Parameter Name="poolEnableAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEnableAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリングを有効にするプールの ID。
            </param>
        <param name="poolEnableAutoScaleParameter">
            要求のパラメーターです。
            </param>
        <param name="poolEnableAutoScaleOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScale">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun EvaluateAutoScale (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun EvaluateAutoScale(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScale(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions)" />
      <MemberSignature Language="F#" Value="static member EvaluateAutoScale : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScale (operations, poolId, autoScaleFormula, poolEvaluateAutoScaleOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリング式を評価するプールの ID。
            </param>
        <param name="autoScaleFormula">
            プール内の計算ノードの必要な数の式。 数式が検証されると、結果が計算されがプールには適用されません。 適用するには、数式をプールに 'を有効にするプールの自動スケーリングを' です。 この式の指定に関する詳細についてを参照して自動的に Azure Batch プール (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling) 内のノードをコンピューティング スケール。
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <summary>
            自動の評価結果は、プール内の数式をスケーリングを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API は、自動スケール式を検証するため、主には、プールに、式を適用せず、結果が単純に返されるです。 自動スケーリング式を評価するために有効になっている、プールが必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluateAutoScaleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt; EvaluateAutoScaleAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt; EvaluateAutoScaleAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string autoScaleFormula, class Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions poolEvaluateAutoScaleOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScaleAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EvaluateAutoScaleAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.EvaluateAutoScaleAsync (operations, poolId, autoScaleFormula, poolEvaluateAutoScaleOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;EvaluateAutoScaleAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.AutoScaleRun&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoScaleFormula" Type="System.String" />
        <Parameter Name="poolEvaluateAutoScaleOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolEvaluateAutoScaleOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            自動スケーリング式を評価するプールの ID。
            </param>
        <param name="autoScaleFormula">
            プール内の計算ノードの必要な数の式。 数式が検証されると、結果が計算されがプールには適用されません。 適用するには、数式をプールに 'を有効にするプールの自動スケーリングを' です。 この式の指定に関する詳細についてを参照して自動的に Azure Batch プール (https://azure.microsoft.com/en-us/documentation/articles/batch-automatic-scaling) 内のノードをコンピューティング スケール。
            </param>
        <param name="poolEvaluateAutoScaleOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            自動の評価結果は、プール内の数式をスケーリングを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この API は、自動スケール式を検証するため、主には、プールに、式を適用せず、結果が単純に返されるです。 自動スケーリング式を評価するために有効になっている、プールが必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Exists(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions -&gt; bool" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Exists (operations, poolId, poolExistsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolExistsOptions">
            操作の追加パラメーター
            </param>
        <summary>
            プールの基本プロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions poolExistsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ExistsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ExistsAsync (operations, poolId, poolExistsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ExistsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolExistsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolExistsOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールの基本プロパティを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudPool Get (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudPool Get(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudPool" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Get (operations, poolId, poolGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolGetOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したプールに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolStatistics GetAllLifetimeStatistics (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics GetAllLifetimeStatistics(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatistics(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatistics : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStatistics" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatistics (operations, poolGetAllLifetimeStatisticsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolGetAllLifetimeStatisticsOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウント内のプールのすべての有効期間の概要統計情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            統計情報は、存在していたアカウントを作成してから、アカウントの最後の更新時刻、統計のすべてのプール間で集計されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllLifetimeStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt; GetAllLifetimeStatisticsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt; GetAllLifetimeStatisticsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions poolGetAllLifetimeStatisticsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatisticsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAllLifetimeStatisticsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAllLifetimeStatisticsAsync (operations, poolGetAllLifetimeStatisticsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;GetAllLifetimeStatisticsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolGetAllLifetimeStatisticsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetAllLifetimeStatisticsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolGetAllLifetimeStatisticsOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions poolGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.GetAsync (operations, poolId, poolGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            取得するプールの ID。
            </param>
        <param name="poolGetOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; List (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; List(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.List (operations, poolListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolListOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListOptions poolListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListAsync (operations, poolListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolListOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNext (operations, nextPageLink, poolListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListNextOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions poolListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListNextAsync (operations, nextPageLink, poolListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内のプールのすべての一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetrics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetrics (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetrics(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetrics(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetrics : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetrics (operations, poolListUsageMetricsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolListUsageMetricsOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。 指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions poolListUsageMetricsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsAsync (operations, poolListUsageMetricsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListUsageMetricsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolListUsageMetricsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolListUsageMetricsOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetricsNext (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt; ListUsageMetricsNext(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNext(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsNext : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNext (operations, nextPageLink, poolListUsageMetricsNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListUsageMetricsNextOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウント用の個別の時間間隔の間でプールを使用して集計の使用状況メトリックを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            など、poolId $filter 句を指定しない場合、応答には、返される集計間隔の時間の範囲内のアカウント内に存在していたすべてのプールが含まれます。 指定しない場合、startTime、endTime など $filter 句を現在使用できません。 最後の集計間隔の開始と終了時刻に、これらの既定のフィルターつまり、最後の集計間隔のみが返されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsageMetricsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsNextAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt; ListUsageMetricsNextAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions poolListUsageMetricsNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNextAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsageMetricsNextAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ListUsageMetricsNextAsync (operations, nextPageLink, poolListUsageMetricsNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ListUsageMetricsNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUsageMetrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="poolListUsageMetricsNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolListUsageMetricsNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="poolListUsageMetricsNextOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Patch (operations, poolId, poolPatchParameter, poolPatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolPatchParameter">
            要求のパラメーターです。
            </param>
        <param name="poolPatchOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これには、要求で指定されたプールのプロパティのみ置き換えられます。 たとえば、プールに関連付けられている開始タスク、要求が開始タスク要素を指定しない場合は、既存の開始タスク保持プールにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter poolPatchParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions poolPatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter,Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter * Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.PatchAsync (operations, poolId, poolPatchParameter, poolPatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;PatchAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolPatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolPatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchParameter" />
        <Parameter Name="poolPatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolPatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolPatchParameter">
            要求のパラメーターです。
            </param>
        <param name="poolPatchOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これには、要求で指定されたプールのプロパティのみ置き換えられます。 たとえば、プールに関連付けられている開始タスク、要求が開始タスク要素を指定しない場合は、既存の開始タスク保持プールにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders RemoveNodes (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders RemoveNodes(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodes(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions)" />
      <MemberSignature Language="F#" Value="static member RemoveNodes : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodes (operations, poolId, nodeRemoveParameter, poolRemoveNodesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            ノードを削除するプールの ID。
            </param>
        <param name="nodeRemoveParameter">
            要求のパラメーターです。
            </param>
        <param name="poolRemoveNodesOptions">
            操作の追加パラメーター
            </param>
        <summary>
            削除は、指定したプールからノードを計算します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、プールの割り当ての状態が点灯している場合にのみ実行できます。 この操作を実行すると、割り当て状態の変更定常からサイズを変更します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt; RemoveNodesAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt; RemoveNodesAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter nodeRemoveParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions poolRemoveNodesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodesAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter,Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveNodesAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter * Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.RemoveNodesAsync (operations, poolId, nodeRemoveParameter, poolRemoveNodesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;RemoveNodesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeRemoveParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeRemoveParameter" />
        <Parameter Name="poolRemoveNodesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolRemoveNodesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            ノードを削除するプールの ID。
            </param>
        <param name="nodeRemoveParameter">
            要求のパラメーターです。
            </param>
        <param name="poolRemoveNodesOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="Resize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders Resize (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders Resize(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Resize(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions)" />
      <MemberSignature Language="F#" Value="static member Resize : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.Resize (operations, poolId, poolResizeParameter, poolResizeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            サイズを変更するプールの ID です。
            </param>
        <param name="poolResizeParameter">
            要求のパラメーターです。
            </param>
        <param name="poolResizeOptions">
            操作の追加パラメーター
            </param>
        <summary>
            プールに割り当てられているコンピューティング ノードの数を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            割り当て状態が点灯しているときに、プールのサイズのみできます。 プールは既にサイズ変更、要求はステータス コード 409 で失敗します。 ときに、プールにある場合、プールの割り当ての状態の変更定常からサイズを変更するのには、サイズを変更します。
            自動スケーリング用に構成されているプールのサイズを変更することはできません。 これを行うしようとすると、バッチ サービスはエラー 409 を返します。 起点、プールのサイズを変更する場合、バッチ サービスは削除するノードを選択します。 特定のノードを削除するには、代わりにプール削除ノード API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt; ResizeAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt; ResizeAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter poolResizeParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions poolResizeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ResizeAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter,Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResizeAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter * Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.ResizeAsync (operations, poolId, poolResizeParameter, poolResizeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;ResizeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolResizeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolResizeParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeParameter" />
        <Parameter Name="poolResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolResizeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            サイズを変更するプールの ID です。
            </param>
        <param name="poolResizeParameter">
            要求のパラメーターです。
            </param>
        <param name="poolResizeOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            プールに割り当てられているコンピューティング ノードの数を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            割り当て状態が点灯しているときに、プールのサイズのみできます。 プールは既にサイズ変更、要求はステータス コード 409 で失敗します。 ときに、プールにある場合、プールの割り当ての状態の変更定常からサイズを変更するのには、サイズを変更します。
            自動スケーリング用に構成されているプールのサイズを変更することはできません。 これを行うしようとすると、バッチ サービスはエラー 409 を返します。 起点、プールのサイズを変更する場合、バッチ サービスは削除するノードを選択します。 特定のノードを削除するには、代わりにプール削除ノード API を使用します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders StopResize (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders StopResize(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResize(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions)" />
      <MemberSignature Language="F#" Value="static member StopResize : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResize (operations, poolId, poolStopResizeOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            サイズを停止するプールの ID。
            </param>
        <param name="poolStopResizeOptions">
            操作の追加パラメーター
            </param>
        <summary>
            継続的な停止のサイズ変更、プールに操作します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プール サイズ変更操作の前に以前の状態は元に戻りません。 行われるさらなる変更だけが停止され、プールが、現在の状態を維持します。 停止後、プールが停止操作が完了するとではノードの数に安定します。 プール割り当て状態は、停止操作中は停止してから、安定したに最初に変更します。 サイズ変更操作で、明示的なサイズ変更プール要求である必要はありません。この API は、作成時に、プールの初期サイズ設定を停止するようにも使用できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopResizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt; StopResizeAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt; StopResizeAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions poolStopResizeOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResizeAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopResizeAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.StopResizeAsync (operations, poolId, poolStopResizeOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;StopResizeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolStopResizeOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolStopResizeOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            サイズを停止するプールの ID。
            </param>
        <param name="poolStopResizeOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="UpdateProperties">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders UpdateProperties (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders UpdateProperties(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdateProperties(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions)" />
      <MemberSignature Language="F#" Value="static member UpdateProperties : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdateProperties (operations, poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolUpdatePropertiesParameter">
            要求のパラメーターです。
            </param>
        <param name="poolUpdatePropertiesOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したプールのプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            これにより、プールのすべての更新可能なプロパティが完全に置き換えられます。 たとえば、開始タスクがこの要求に指定されていない場合、Batch service が解除され、プールに関連付けられている開始タスク、既存の開始タスク。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePropertiesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt; UpdatePropertiesAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt; UpdatePropertiesAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter poolUpdatePropertiesParameter, class Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions poolUpdatePropertiesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdatePropertiesAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter,Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePropertiesAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter * Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpdatePropertiesAsync (operations, poolId, poolUpdatePropertiesParameter, poolUpdatePropertiesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;UpdatePropertiesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="poolUpdatePropertiesParameter" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesParameter" />
        <Parameter Name="poolUpdatePropertiesOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpdatePropertiesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            更新するプールの ID。
            </param>
        <param name="poolUpdatePropertiesParameter">
            要求のパラメーターです。
            </param>
        <param name="poolUpdatePropertiesOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
    <Member MemberName="UpgradeOS">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders UpgradeOS (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders UpgradeOS(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOS(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions)" />
      <MemberSignature Language="F#" Value="static member UpgradeOS : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOS (operations, poolId, targetOSVersion, poolUpgradeOSOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            アップグレードするプールの ID。
            </param>
        <param name="targetOSVersion">
            プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。
            </param>
        <param name="poolUpgradeOSOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定したプールのオペレーティング システムをアップグレードします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            アップグレード中は、バッチ サービス アップグレードは、プール内のノードを計算します。 アップグレードのコンピューティング ノードを選択すると、そのノードで実行されているすべてのタスクがノードから削除され、後で (または、別の計算ノード) を再実行キューに返されます。 アップグレードが完了するまで、ノードは使用できません。 ノードは、サービスのアップグレード対象として外すと、この演算の結果は一時的に削減プールの容量。 サービスが、すべてのアップグレードを回避しようとしています。 バッチはコンピューティング ノードを同時とは限りません (特にでサイズの小さいプール); の実行したがって、プールは一時的に実行できるようにタスクでない可能性があります。 この操作を実行するときにアップグレードする場合に、プールの状態を変更します。 すべてのコンピューティング ノードでは、アップグレードが完了したら、ときに、プールの状態をアクティブに返します。 アップグレードの進行状況では、プールの currentOSVersion は OS のバージョンから、ノードをアップグレードして、targetOSVersion ノードへのアップグレードは、OS のバージョンを反映することを反映します。 アップグレードが完了したら、currentOSVersion はすべてのノードで実行されている OS バージョンを反映するように更新されます。 この操作は、cloudServiceConfiguration プロパティを使用して作成されたプールでのみ呼び出すことができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeOSAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt; UpgradeOSAsync (this Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt; UpgradeOSAsync(class Microsoft.Azure.Batch.Protocol.IPoolOperations operations, string poolId, string targetOSVersion, class Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions poolUpgradeOSOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOSAsync(Microsoft.Azure.Batch.Protocol.IPoolOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeOSAsync : Microsoft.Azure.Batch.Protocol.IPoolOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions.UpgradeOSAsync (operations, poolId, targetOSVersion, poolUpgradeOSOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.PoolOperationsExtensions/&lt;UpgradeOSAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IPoolOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="poolUpgradeOSOptions" Type="Microsoft.Azure.Batch.Protocol.Models.PoolUpgradeOSOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="poolId">
            アップグレードするプールの ID。
            </param>
        <param name="targetOSVersion">
            プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。
            </param>
        <param name="poolUpgradeOSOptions">
            操作の追加パラメーター
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
      </Docs>
    </Member>
  </Members>
</Type>