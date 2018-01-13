<Type Name="IActorService" FullName="Microsoft.ServiceFabric.Actors.IActorService">
  <TypeSignature Language="C#" Value="public interface IActorService : Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorService implements class Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.IActorService" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorService&#xA;Implements IService" />
  <TypeSignature Language="F#" Value="type IActorService = interface&#xA;    interface IService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アクター サービス レベルで呼び出すことができるメソッドを含むインターフェイスを定義します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteActorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteActorAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorService.DeleteActorAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">
          <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />削除するアクターです。</param>
        <param name="cancellationToken">操作を取り消す通知を配信します。</param>
        <summary>
            アクター サービスからアクターを削除します。
            </summary>
        <returns>サーバーへの呼び出しの非同期操作を表すタスク。</returns>
        <remarks>
          <para>アクティブなアクターが非アクティブ化し、状態プロバイダーからの状態も削除されます。</para>
          <para>アクティブでアクターの状態は、状態プロバイダーから削除されます。</para>
          <para>このメソッドは、システムに存在しないアクター id 呼び出されると、no-op されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActorsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; GetActorsAsync (Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; GetActorsAsync(class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActorsAsync : Microsoft.ServiceFabric.Actors.Query.ContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt;" Usage="iActorService.GetActorsAsync (continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">クエリから結果を開始する継続トークンです。
            継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</param>
        <param name="cancellationToken">操作を取り消す通知を配信します。</param>
        <summary>
            アクター サービスを照会することによってアクターの一覧を取得します。
            </summary>
        <returns>サーバーへの呼び出しの非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>