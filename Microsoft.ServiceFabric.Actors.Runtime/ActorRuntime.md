<Type Name="ActorRuntime" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime">
  <TypeSignature Language="C#" Value="public static class ActorRuntime" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed ActorRuntime extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRuntime" />
  <TypeSignature Language="F#" Value="type ActorRuntime = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5451c-101">Service Fabric ランタイムにアクターとアクター サービスの種類を登録するメソッドが含まれています。</span><span class="sxs-lookup"><span data-stu-id="5451c-101">Contains methods to register actor and actor service types with Service Fabric runtime.</span></span> <span data-ttu-id="5451c-102">型を登録するには、アクターとアクター サービスのインスタンスを作成するランタイムすることができます。</span><span class="sxs-lookup"><span data-stu-id="5451c-102">Registering the types allows the runtime to create instances of the actor and the actor service.</span></span> <span data-ttu-id="5451c-103">Https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-lifecycle アクターのライフ サイクルの詳細についてを参照してください。</span><span class="sxs-lookup"><span data-stu-id="5451c-103">See https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-lifecycle for more information on the lifecycle of an actor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="RegisterActorAsync&lt;TActor&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RegisterActorAsync&lt;TActor&gt; (TimeSpan timeout = null, System.Threading.CancellationToken cancellationToken = null) where TActor : Microsoft.ServiceFabric.Actors.Runtime.ActorBase;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RegisterActorAsync&lt;(class Microsoft.ServiceFabric.Actors.Runtime.ActorBase) TActor&gt;(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime.RegisterActorAsync``1(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterActorAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task (requires 'Actor :&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorBase)" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime.RegisterActorAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime/&lt;RegisterActorAsync&gt;d__2`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActor">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Actors.Runtime.ActorBase</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TActor"><span data-ttu-id="5451c-104">アクターを実装する型。</span><span class="sxs-lookup"><span data-stu-id="5451c-104">The type implementing the actor.</span></span></typeparam>
        <param name="timeout"><span data-ttu-id="5451c-105">登録操作のキャンセルするまでのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="5451c-105">A timeout period after which the registration operation will be canceled.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5451c-106">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="5451c-106">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5451c-107">Service Fabric ランタイムにアクター型を登録します。</span><span class="sxs-lookup"><span data-stu-id="5451c-107">Registers an actor type with Service Fabric runtime.</span></span> <span data-ttu-id="5451c-108">これにより、このアクターのインスタンスを作成するランタイム。</span><span class="sxs-lookup"><span data-stu-id="5451c-108">This allows the runtime to create instances of this actor.</span></span>
            </summary>
        <returns><span data-ttu-id="5451c-109">Service Fabric ランタイムにアクターの種類を登録する非同期操作を表すタスクを返します。</span><span class="sxs-lookup"><span data-stu-id="5451c-109">returns a task that represents the asynchronous operation to register actor type with Service Fabric runtime.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterActorAsync&lt;TActor&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RegisterActorAsync&lt;TActor&gt; (Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation,Microsoft.ServiceFabric.Actors.Runtime.ActorService&gt; actorServiceFactory, TimeSpan timeout = null, System.Threading.CancellationToken cancellationToken = null) where TActor : Microsoft.ServiceFabric.Actors.Runtime.ActorBase;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RegisterActorAsync&lt;(class Microsoft.ServiceFabric.Actors.Runtime.ActorBase) TActor&gt;(class System.Func`3&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation, class Microsoft.ServiceFabric.Actors.Runtime.ActorService&gt; actorServiceFactory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime.RegisterActorAsync``1(System.Func{System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation,Microsoft.ServiceFabric.Actors.Runtime.ActorService},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterActorAsync : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation, Microsoft.ServiceFabric.Actors.Runtime.ActorService&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task (requires 'Actor :&gt; Microsoft.ServiceFabric.Actors.Runtime.ActorBase)" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime.RegisterActorAsync (actorServiceFactory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.ActorRuntime/&lt;RegisterActorAsync&gt;d__3`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TActor">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Actors.Runtime.ActorBase</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorServiceFactory" Type="System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation,Microsoft.ServiceFabric.Actors.Runtime.ActorService&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TActor"><span data-ttu-id="5451c-110">型の実装するアクターです。</span><span class="sxs-lookup"><span data-stu-id="5451c-110">The Type implementing actor.</span></span></typeparam>
        <param name="actorServiceFactory"><span data-ttu-id="5451c-111">新しいアクター サービスを作成するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="5451c-111">The delegate that creates new actor service.</span></span></param>
        <param name="timeout"><span data-ttu-id="5451c-112">登録操作のキャンセルするまでのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="5451c-112">A timeout period after which the registration operation will be canceled.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="5451c-113">キャンセル要求を監視するためのトークン。</span><span class="sxs-lookup"><span data-stu-id="5451c-113">The token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="5451c-114">Service Fabric ランタイムにアクター サービスを登録します。</span><span class="sxs-lookup"><span data-stu-id="5451c-114">Registers an actor service with Service Fabric runtime.</span></span> <span data-ttu-id="5451c-115">これにより、ランタイムにアクター サービスのレプリカのインスタンスを作成できます。</span><span class="sxs-lookup"><span data-stu-id="5451c-115">This allows the runtime to create instances of the replicas for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="5451c-116">Repre 末尾アクターを登録する非同期操作では Service Fabric ランタイムとサービスを提供するタスク。</span><span class="sxs-lookup"><span data-stu-id="5451c-116">A task that repre sents the asynchronous operation to register actor service with Service Fabric runtime.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>