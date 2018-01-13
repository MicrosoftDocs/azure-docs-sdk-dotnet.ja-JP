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
            <span data-ttu-id="f0add-101">アクター サービス レベルで呼び出すことができるメソッドを含むインターフェイスを定義します。</span><span class="sxs-lookup"><span data-stu-id="f0add-101">Defines the interface containing methods which can be called at Actor Service level.</span></span>
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
          <span data-ttu-id="f0add-102"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />削除するアクターです。</span><span class="sxs-lookup"><span data-stu-id="f0add-102"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor to be deleted.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f0add-103">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="f0add-103">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="f0add-104">アクター サービスからアクターを削除します。</span><span class="sxs-lookup"><span data-stu-id="f0add-104">Deletes an Actor from the Actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="f0add-105">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="f0add-105">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f0add-106">アクティブなアクターが非アクティブ化し、状態プロバイダーからの状態も削除されます。</span><span class="sxs-lookup"><span data-stu-id="f0add-106">An active actor, will be deactivated and its state will also be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="f0add-107">アクティブでアクターの状態は、状態プロバイダーから削除されます。</span><span class="sxs-lookup"><span data-stu-id="f0add-107">An in-active actor's state will be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="f0add-108">このメソッドは、システムに存在しないアクター id 呼び出されると、no-op されます。</span><span class="sxs-lookup"><span data-stu-id="f0add-108">If this method is called for a non-existent actor id in the system, it will be a no-op.</span></span></para>
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
        <param name="continuationToken"><span data-ttu-id="f0add-109">クエリから結果を開始する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="f0add-109">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="f0add-110">継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</span><span class="sxs-lookup"><span data-stu-id="f0add-110">A null value of continuation token means start returning values form the beginning.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f0add-111">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="f0add-111">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="f0add-112">アクター サービスを照会することによってアクターの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f0add-112">Gets the list of Actors by querying the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="f0add-113">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="f0add-113">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>