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
            ベース Microsoft Service Fabric アクターの信頼性の高いサービスの基本クラスを表します。
            </summary>
    <remarks>
            アクターが、任意のサービス レベルの動作をオーバーライドする場合は、独自のカスタム アクター サービスを実装するには、このクラスから派生します。
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
        <param name="context">サービス コンテキスト アクター サービスは、の下で動作します。</param>
        <param name="actorTypeInfo">アクターの型情報。</param>
        <param name="actorFactory">アクター オブジェクトを作成するファクトリ メソッド。</param>
        <param name="stateManagerFactory">作成するファクトリ メソッド<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" /></param>
        <param name="stateProvider">保存し、アクター オブジェクトの状態にアクセスする状態プロバイダー。</param>
        <param name="settings">アクター サービスの動作を構成するために使用する設定です。</param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" /> クラスの新しいインスタンスを初期化します。
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
            アクター サービスの ActorTypeInformation を取得します。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />サービスのレプリカによってホストされているアクターです。
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
            オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.CreateServiceReplicaListeners" />です。
            </summary>
        <returns>などの文字列のエンドポイントのペア {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</returns>
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
        <param name="actorId"><see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />を削除するアクターのです。</param>
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
            オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnAbort" />です。
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
        <param name="newRole">レプリカの新しいロール。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />です。
            </summary>
        <returns>レプリカがプライマリになったときに実行される非同期操作を表すタスク。</returns>
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
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.OnCloseAsync(System.Threading.CancellationToken)" />です。
            </summary>
        <returns>レプリカが閉じられたときに実行される非同期操作を表すタスク。</returns>
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
            これは、使用されているアクター サービスのリスナーのどのバージョン (V1、V2or Compact) を決定します。
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
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            オーバーライド<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />です。
            </summary>
        <returns>
            レプリカがプライマリになったときにアラームを読み込む非同期操作を表すタスク。
            </returns>
        <remarks>
            このメソッドをオーバーライドする必要がある場合、オーバーライドされたメソッドからこのメソッドを呼び出すことを確認してください。
            オーバーライドされたメソッドの実装が指定されたガイドラインに準拠しているかどうかを確認も<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase.RunAsync(System.Threading.CancellationToken)" />します。 
            <para>これに失敗すると、フェールオーバーが発生することができます、再構成のまたはアップグレード、アクター サービス スタックをサービスの可用性に影響を与えることができます。</para></remarks>
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
            アクター サービスの設定を取得します。 
            </summary>
        <value>
            アクター サービスの設定です。
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
            取得、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービスの状態プロバイダーを表すです。
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービスの状態プロバイダーを表すです。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>