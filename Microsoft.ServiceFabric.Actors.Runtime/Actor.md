<Type Name="Actor" FullName="Microsoft.ServiceFabric.Actors.Runtime.Actor">
  <TypeSignature Language="C#" Value="public abstract class Actor : Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Actor extends Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Actor&#xA;Inherits ActorBase" />
  <TypeSignature Language="F#" Value="type Actor = class&#xA;    inherit ActorBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Actors.Runtime.ActorBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            関連付けられている複数の信頼性の高い '名前付き' 状態を持つことができるアクターを表します。
            </summary>
    <remarks>
            アクターのガベージ コレクションとのフェールオーバーの制限の状態が保持されます。 状態の取得と格納がアクター状態プロバイダーによって提供される<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />です。
            </remarks>
    <altmember cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorBase" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Actor (Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, Microsoft.ServiceFabric.Actors.ActorId actorId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Actors.Runtime.ActorService actorService, class Microsoft.ServiceFabric.Actors.ActorId actorId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.#ctor(Microsoft.ServiceFabric.Actors.Runtime.ActorService,Microsoft.ServiceFabric.Actors.ActorId)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.Actor : Microsoft.ServiceFabric.Actors.Runtime.ActorService * Microsoft.ServiceFabric.Actors.ActorId -&gt; Microsoft.ServiceFabric.Actors.Runtime.Actor" Usage="new Microsoft.ServiceFabric.Actors.Runtime.Actor (actorService, actorId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actorService" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorService" />
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
      </Parameters>
      <Docs>
        <param name="actorService">
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorService" />このアクターのインスタンスをホストします。
            </param>
        <param name="actorId">
            <see cref="T:Microsoft.ServiceFabric.Actors.ActorId" />アクターのインスタンスのです。
            </param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task SaveStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task SaveStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Function SaveStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.SaveStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="actor.SaveStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            状態の変更を保存 (追加/更新/削除) 最後の呼び出し以降に行われた<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.Actor.SaveStateAsync" />アクターに関連付けられているアクター状態プロバイダーにします。
            </summary>
        <returns>非同期の保存操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager StateManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager StateManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateManager As IActorStateManager" />
      <MemberSignature Language="F#" Value="member this.StateManager : Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" Usage="Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態マネージャーを取得<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />get/追加/更新/削除する状態をという名前を使用できます。
            </summary>
        <value>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />アクター状態の管理に使用できます。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>