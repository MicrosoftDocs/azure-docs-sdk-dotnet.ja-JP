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
            Service Fabric ランタイムにアクターとアクター サービスの種類を登録するメソッドが含まれています。 型を登録するには、アクターとアクター サービスのインスタンスを作成するランタイムすることができます。 Https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-lifecycle アクターのライフ サイクルの詳細についてを参照してください。
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
        <typeparam name="TActor">アクターを実装する型。</typeparam>
        <param name="timeout">登録操作のキャンセルするまでのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            Service Fabric ランタイムにアクター型を登録します。 これにより、このアクターのインスタンスを作成するランタイム。
            </summary>
        <returns>Service Fabric ランタイムにアクターの種類を登録する非同期操作を表すタスクを返します。</returns>
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
        <typeparam name="TActor">型の実装するアクターです。</typeparam>
        <param name="actorServiceFactory">新しいアクター サービスを作成するデリゲート。</param>
        <param name="timeout">登録操作のキャンセルするまでのタイムアウト期間。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            Service Fabric ランタイムにアクター サービスを登録します。 これにより、ランタイムにアクター サービスのレプリカのインスタンスを作成できます。
            </summary>
        <returns>Repre 末尾アクターを登録する非同期操作では Service Fabric ランタイムとサービスを提供するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>