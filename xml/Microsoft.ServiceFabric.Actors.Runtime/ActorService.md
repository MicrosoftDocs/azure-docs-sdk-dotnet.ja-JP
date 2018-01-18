<Type Name="ActorService" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorService">
  <TypeSignature Language="C#" Value="public class ActorService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Actors.IActorService, Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorService extends Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase implements class Microsoft.ServiceFabric.Actors.IActorService, class Microsoft.ServiceFabric.Services.Remoting.IService" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorService&#xA;Inherits StatefulServiceBase&#xA;Implements IActorService, IService" />
  <TypeSignature Language="F#" Value="type ActorService = class&#xA;    inherit StatefulServiceBase&#xA;    interface IActorService&#xA;    interface IService" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.IActorService</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="439c0-101">ベース Microsoft Service Fabric アクターの信頼性の高いサービスの基本クラスを表します。</span><span class="sxs-lookup"><span data-stu-id="439c0-101">Represents the base class for Microsoft Service Fabric based reliable actors service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="439c0-102">アクターが、任意のサービス レベルの動作をオーバーライドする場合は、独自のカスタム アクター サービスを実装するには、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="439c0-102">Derive from this class to implement your own custom actor service if you want to override any service level behavior for your actors.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorService (System.Fabric.StatefulServiceContext context, Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo, Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; actorFactory = null, Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; stateManagerFactory = null, Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider stateProvider = null, Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatefulServiceContext context, class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo, class System.Func`3&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorService, class Microsoft.ServiceFabric.Actors.ActorId, class Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; actorFactory, class System.Func`3&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorBase, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; stateManagerFactory, class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider stateProvider, class Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.#ctor(System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation,System.Func{Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase},System.Func{Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager},Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (context As StatefulServiceContext, actorTypeInfo As ActorTypeInformation, Optional actorFactory As Func(Of ActorService, ActorId, ActorBase) = null, Optional stateManagerFactory As Func(Of ActorBase, IActorStateProvider, IActorStateManager) = null, Optional stateProvider As IActorStateProvider = null, Optional settings As ActorServiceSettings = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.ActorService : System.Fabric.StatefulServiceContext * Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation * Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService, Microsoft.ServiceFabric.Actors.ActorId, Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt; * Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase, Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt; * Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider * Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorService" Usage="new Microsoft.ServiceFabric.Actors.Runtime.ActorService (context, actorTypeInfo, actorFactory, stateManagerFactory, stateProvider, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="context" Type="System.Fabric.StatefulServiceContext" />
        <Parameter Name="actorTypeInfo" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
        <Parameter Name="actorFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.ActorBase&gt;" />
        <Parameter Name="stateManagerFactory" Type="System.Func&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorBase,Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider,Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager&gt;" />
        <Parameter Name="stateProvider" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />
        <Parameter Name="settings" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="439c0-103">サービス コンテキスト アクター サービスは、の下で動作します。</span><span class="sxs-lookup"><span data-stu-id="439c0-103">Service context the actor service is operating under.</span></span></param>
        <param name="actorTypeInfo"><span data-ttu-id="439c0-104">アクターの型情報。</span><span class="sxs-lookup"><span data-stu-id="439c0-104">The type information of the Actor.</span></span></param>
        <param name="actorFactory"><span data-ttu-id="439c0-105">アクター オブジェクトを作成するファクトリ メソッド。</span><span class="sxs-lookup"><span data-stu-id="439c0-105">The factory method to create Actor objects.</span></span></param>
        <param name="stateManagerFactory"><span data-ttu-id="439c0-106">作成するファクトリ メソッド<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /></span><span class="sxs-lookup"><span data-stu-id="439c0-106">The factory method to create <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /></span></span></param>
        <param name="stateProvider"><span data-ttu-id="439c0-107">保存し、アクター オブジェクトの状態にアクセスする状態プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="439c0-107">The state provider to store and access the state of the Actor objects.</span></span></param>
        <param name="settings"><span data-ttu-id="439c0-108">アクター サービスの動作を構成するために使用する設定です。</span><span class="sxs-lookup"><span data-stu-id="439c0-108">The settings used to configure the behavior of the Actor service.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-109"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="439c0-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActorTypeInformation">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation ActorTypeInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation ActorTypeInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.ActorTypeInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActorTypeInformation As ActorTypeInformation" />
      <MemberSignature Language="F#" Value="member this.ActorTypeInformation : Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.ActorTypeInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="439c0-110">アクター サービスの ActorTypeInformation を取得します。</span><span class="sxs-lookup"><span data-stu-id="439c0-110">Gets the ActorTypeInformation for actor service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="439c0-111"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />サービスのレプリカによってホストされているアクターです。</span><span class="sxs-lookup"><span data-stu-id="439c0-111"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" /> for the actor hosted by the service replica.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceReplicaListeners">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceReplicaListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.CreateServiceReplicaListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateServiceReplicaListeners () As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="override this.CreateServiceReplicaListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;" Usage="actorService.CreateServiceReplicaListeners " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="439c0-112">オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />です。</span><span class="sxs-lookup"><span data-stu-id="439c0-112">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />.</span></span>
            </summary>
        <returns><span data-ttu-id="439c0-113">などの文字列のエンドポイントのペア {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="439c0-113">Endpoint string pairs like {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorService.DeleteActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Microsoft#ServiceFabric#Actors#IActorService#DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.IActorService.DeleteActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;Microsoft-ServiceFabric-Actors-IActorService-DeleteActorAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId"><span data-ttu-id="439c0-114"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />を削除するアクターのです。</span><span class="sxs-lookup"><span data-stu-id="439c0-114">The <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" /> of the actor to be deleted.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="439c0-115">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="439c0-115">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-116">アクター サービスからアクターを削除します。</span><span class="sxs-lookup"><span data-stu-id="439c0-116">Deletes an Actor from the Actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="439c0-117">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="439c0-117">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="439c0-118">アクティブなアクターが非アクティブ化し、状態プロバイダーからの状態も削除されます。</span><span class="sxs-lookup"><span data-stu-id="439c0-118">An active actor, will be deactivated and its state will also be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="439c0-119">アクティブでアクターの状態は、状態プロバイダーから削除されます。</span><span class="sxs-lookup"><span data-stu-id="439c0-119">An in-active actor's state will be deleted from state provider.</span></span></para>
          <para><span data-ttu-id="439c0-120">このメソッドは、システムに存在しないアクター id 呼び出されると、no-op されます。</span><span class="sxs-lookup"><span data-stu-id="439c0-120">If this method is called for a non-existent actor id in the system, it will be a no-op.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; IActorService.GetActorsAsync (Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.Query.ActorInformation&gt;&gt; Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Microsoft#ServiceFabric#Actors#IActorService#GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.IActorService.GetActorsAsync(Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
        <param name="continuationToken"><span data-ttu-id="439c0-121">クエリから結果を開始する継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="439c0-121">A continuation token to start querying the results from.</span></span>
            <span data-ttu-id="439c0-122">継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。</span><span class="sxs-lookup"><span data-stu-id="439c0-122">A null value of continuation token means start returning values form the beginning.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="439c0-123">操作を取り消す通知を配信します。</span><span class="sxs-lookup"><span data-stu-id="439c0-123">Propagates notification that operations should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-124">アクター サービスを照会することによってアクターの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="439c0-124">Gets the list of Actors by querying the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="439c0-125">サーバーへの呼び出しの非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="439c0-125">A task that represents the asynchronous operation of call to server.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="actorService.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="439c0-126">オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />です。</span><span class="sxs-lookup"><span data-stu-id="439c0-126">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;OnChangeRoleAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole"><span data-ttu-id="439c0-127">レプリカの新しいロール。</span><span class="sxs-lookup"><span data-stu-id="439c0-127">The new role for the replica.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="439c0-128">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="439c0-128">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-129">オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="439c0-129">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="439c0-130">レプリカがプライマリになったときに実行される非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="439c0-130">A task that represents the asynchronous operation performed when the replica becomes primary.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorService/&lt;OnCloseAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="439c0-131">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="439c0-131">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-132">オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="439c0-132">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="439c0-133">レプリカが閉じられたときに実行される非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="439c0-133">A task that represents the asynchronous operation performed when the replica is closed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemotingListener">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener RemotingListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.RemotingListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemotingListener As RemotingListener" />
      <MemberSignature Language="F#" Value="member this.RemotingListener : Microsoft.ServiceFabric.Services.Remoting.RemotingListener" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.RemotingListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="439c0-134">これは、使用されているアクター サービスのリスナーのどのバージョン (V1、V2or Compact) を決定します。</span><span class="sxs-lookup"><span data-stu-id="439c0-134">This determines which version(V1,V2or Compact) of actor service listener is being used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="actorService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="439c0-135">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="439c0-135">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="439c0-136">オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="439c0-136">Overrides <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="439c0-137">レプリカがプライマリになったときにアラームを読み込む非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="439c0-137">A task that represents the asynchronous operation of loading reminders when the replica becomes primary.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="439c0-138">このメソッドをオーバーライドする必要がある場合、オーバーライドされたメソッドからこのメソッドを呼び出すことを確認してください。</span><span class="sxs-lookup"><span data-stu-id="439c0-138">If you need to override this method, please make sure to call this method from your overridden method.</span></span>
            <span data-ttu-id="439c0-139">オーバーライドされたメソッドの実装が指定されたガイドラインに準拠しているかどうかを確認も<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />します。</span><span class="sxs-lookup"><span data-stu-id="439c0-139">Also make sure your implementation of overridden method conforms to the guideline specified for <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />.</span></span> 
            <span data-ttu-id="439c0-140"><para>これに失敗すると、フェールオーバーが発生することができます、再構成のまたはアップグレード、アクター サービス スタックをサービスの可用性に影響を与えることができます。</para></span><span class="sxs-lookup"><span data-stu-id="439c0-140"><para> Failing to do so can cause failover, reconfiguration or upgrade of your actor service to get stuck and can impact availibility of your service. </para></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As ActorServiceSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorServiceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="439c0-141">アクター サービスの設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="439c0-141">Gets the settings for the actor service.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="439c0-142">アクター サービスの設定です。</span><span class="sxs-lookup"><span data-stu-id="439c0-142">Settings for the actor service.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateProvider">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider StateProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider StateProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorService.StateProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateProvider As IActorStateProvider" />
      <MemberSignature Language="F#" Value="member this.StateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorService.StateProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="439c0-143">取得、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービスの状態プロバイダーを表すです。</span><span class="sxs-lookup"><span data-stu-id="439c0-143">Gets a <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> that represents the state provider for the actor service.</span></span>
            </summary>
        <value>
          <span data-ttu-id="439c0-144"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービスの状態プロバイダーを表すです。</span><span class="sxs-lookup"><span data-stu-id="439c0-144"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> representing the state provider for the actor service.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>