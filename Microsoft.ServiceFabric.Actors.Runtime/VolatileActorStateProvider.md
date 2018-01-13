<Type Name="VolatileActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider">
  <TypeSignature Language="C#" Value="public class VolatileActorStateProvider : Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, Microsoft.ServiceFabric.Data.IStateProviderReplica2, System.Fabric.IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolatileActorStateProvider extends System.Object implements class Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider, class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2, class System.Fabric.IStateProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class VolatileActorStateProvider&#xA;Implements IActorStateProvider, IStateProvider, IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type VolatileActorStateProvider = class&#xA;    interface IActorStateProvider&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica&#xA;    interface IStateProvider&#xA;    interface VolatileLogicalTimeManager.ISnapshotHandler&#xA;    interface IActorStateProviderInternal" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Fabric.IStateProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            実装を提供<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター状態がメモリ内に保持し、揮発性です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" /> のインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolatileActorStateProvider (System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.#ctor(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider : System.Fabric.ReplicatorSettings -&gt; Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" Usage="new Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider replicatorSettings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="replicatorSettings">
            A<see cref="T:System.Fabric.ReplicatorSettings" />複製物作成会社の設定を説明します。
            </param>
        <summary>
            インスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />で複製物作成会社の設定を指定します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-ActorActivatedAsync&gt;d__24))</AttributeName>
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
        <param name="actorId">アクティブ化したアクターの ID です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した id に置き換えます。 アクターのライセンス認証プロセスの一部としてこのメソッドが呼び出されます 
            </summary>
        <returns> 非同期のアクターのアクティブ化通知の処理を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IActorStateProvider.ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">状態の有無を確認する対象のアクターの ID。</param>
        <param name="stateName">有無を確認するアクター状態の名前。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アクター状態プロバイダーに指定した状態の名前を持つ、アクター状態が含まれているかどうかをチェックします。
            </summary>
        <returns>
            非同期チェック操作を表すタスク。 TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを削除するアクターの ID。</param>
        <param name="reminderName">削除するアラームの名前。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            存在する場合は、指定されたアクター アラームを削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reminderNames" Type="System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reminderNames">削除するアラームのセット。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定された通知のセットを削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; IActorStateProvider.EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">列挙可能なを作成する対象のアクターの ID。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定されたアクターに関連付けられているすべての状態名の列挙可能なが作成されます。
            </summary>
        <returns>
            非同期の列挙操作を表すタスク。 TResult パラメーターの値は、指定されたアクターに関連付けられているすべての州名の列挙です。
            </returns>
        <remarks>
            アクター状態プロバイダーから返された列挙子は、安全に読み取りと同時に使用し、状態プロバイダーに書き込みます。 状態プロバイダーのスナップショットの一貫したビューを表します。
            </remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; IActorStateProvider.GetActorsAsync (int itemsCount, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(int32 itemsCount, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="itemsCount" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="itemsCount">返される要求された項目の数。</param>
        <param name="continuationToken">
            クエリから結果を開始する継続トークンです。
            継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。
            </param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            状態プロバイダーから ActorIds を取得します。
            </summary>
        <returns>サーバーへの呼び出しの非同期操作を表すタスク。</returns>
        <remarks>
            <paramref name="continuationToken" />この API の呼び出し時にアクター状態プロバイダーの状態に対する相対パスです。 アクターの状態プロバイダーの変更を記述する場合 (つまり新しいアクターがアクティブ化または既存のアクターが削除されます) API と継続の間にこれを呼び出す前に、状態が変更された) の前の呼び出しからのトークンを指定して、結果はされたエントリを含めることがあります既に以前の呼び出しでフェッチします。
            </remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize">
      <MemberSignature Language="C#" Value="void IActorStateProvider.Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (actorTypeInfo As ActorTypeInformation) Implements IActorStateProvider.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorTypeInfo" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInfo">アクター クラスの型情報</param>
        <summary>
            関連付けられているアクター型の型情報を使用してアクター状態プロバイダーを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; IActorStateProvider.LoadRemindersAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">非同期の読み込み操作のキャンセル トークン。</param>
        <summary>
            アクター状態プロバイダーに含まれているすべてのアラームを読み込みます。
            </summary>
        <returns>
            非同期ロード操作を表すタスク。 TResult パラメーターの値は、アクター状態プロバイダーに含まれているすべてのアクター アラームのコレクションです。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;T&gt; IActorStateProvider.LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">アクターの状態の特定の状態名に関連付けられている値の型。</typeparam>
        <param name="actorId">状態の読み込み先のアクターの ID。</param>
        <param name="stateName">読み込みにアクター状態の名前。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定された状態の名前に関連付けられているアクターの状態を読み込みます。
            </summary>
        <returns>
            非同期ロード操作を表すタスク。 TResult のパラメーターの値には、特定の状態名に関連付けられているアクター状態の値が含まれています。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">指定された状態の名前に関連付けられているアクターの状態は存在しません。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを所有しているアクターの ID</param>
        <param name="reminder">正常に完了したアクターに送信します。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アラームが起動し、そのコールバックの実行が終了したときに、このメソッドが呼び出される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常にします。
            </summary>
        <returns>
            非同期の通知コールバックを表すタスクでは、通知の処理が完了しました。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-RemoveActorAsync&gt;d__29))</AttributeName>
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
        <param name="actorId">状態を削除するアクターの ID です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            すべての既存の状態と指定されたアクターにアトミックに関連付けられている通知を削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを保存する対象のアクターの ID。</param>
        <param name="reminder">保存するアクターのお知らせします。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定されたアクター アラームを保存します。 指定した名前のアクター アラームが存在しない場合は、それ以外の場合と同じ名前のアクター アラームを既存のアクター アラームが更新を追加します。 
            </summary>
        <returns>非同期の保存操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IActorStateProvider.SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Actors#Runtime#IActorStateProvider#SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Actors-Runtime-IActorStateProvider-SaveStateAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorId" Type="Microsoft.ServiceFabric.Actors.ActorId" />
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">状態の変更を保存する対象のアクターの ID。</param>
        <param name="stateChanges">状態の変更を保存するコレクション。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定したアクター状態の変更のセットをアトミックに保存します。
            </summary>
        <returns>非同期の保存操作を表すタスク。</returns>
        <remarks>
            状態変更のコレクションには、指定された状態の名前の 1 つの項目を含める必要があります。
            保存先に既に存在するか、存在しないアクター状態の更新/削除するアクターの状態を追加しようとしています。 操作は失敗します。
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            ときに<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind" />は<see cref="F:Microsoft.ServiceFabric.Actors.Runtime.StateChangeKind.None" /></exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements IStateProviderReplica.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Abort</InterfaceMember>
      </Implements>
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
            状態プロバイダーのレプリカを強制的に中止します。
            </summary>
        <remarks>
            これは一般に、ノードで、永続的な障害が検出されたときに、または Service Fabric は、内部エラーのため、レプリカのライフ サイクルを確実に管理できませんに発生します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Function BackupAsync (backupCallback As Func(Of BackupInfo, CancellationToken, Task(Of Boolean))) As Task Implements IStateProviderReplica.BackupAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupCallback">バックアップ フォルダーがローカルで作成された、ノード外に移動する準備ができているときに呼び出されるコールバック。</param>
        <summary>
            このアクター状態プロバイダーによって管理されている状態の完全バックアップを実行します
            </summary>
        <returns>非同期のバックアップ操作を表すタスク。</returns>
        <remarks>
            バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.BackupAsync (Microsoft.ServiceFabric.Data.BackupOption option, TimeSpan timeout, System.Threading.CancellationToken cancellationToken, Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; backupCallback);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(valuetype Microsoft.ServiceFabric.Data.BackupOption option, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken, class System.Func`3&lt;class Microsoft.ServiceFabric.Data.BackupInfo, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; backupCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="option" Type="Microsoft.ServiceFabric.Data.BackupOption" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="backupCallback" Type="System.Func&lt;Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="option">バックアップ用のオプションです。</param>
        <param name="timeout">バックアップのタイムアウト。</param>
        <param name="cancellationToken">バックアップのキャンセル トークン。</param>
        <param name="backupCallback">バックアップ フォルダーの準備が呼び出されるコールバック。</param>
        <summary>
            このアクター状態プロバイダーによって管理されている状態のバックアップを実行します。
            </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>
            バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider/&lt;Microsoft-ServiceFabric-Data-IStateProviderReplica-ChangeRoleAsync&gt;d__42))</AttributeName>
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
        <param name="newRole">プライマリまたはセカンダリなど、新しいレプリカ ロール。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            そのロールが変更される、たとえばプライマリまたはセカンダリに、状態プロバイダーのレプリカを通知します。
            </summary>
        <returns>非同期の変更の役割の操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
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
            状態プロバイダーの複製が正常にクローズします。
            </summary>
        <returns>非同期の close 操作を表すタスク。</returns>
        <remarks>
            これは一般に、レプリカのコードにアップグレードされている、負荷分散のため、レプリカが移動されてまたは一時的なエラーが検出されたときに発生します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize">
      <MemberSignature Language="C#" Value="void IStateProviderReplica.Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Sub Initialize (initializationParameters As StatefulServiceInitializationParameters) Implements IStateProviderReplica.Initialize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">サービス名、パーティション id、レプリカの id、およびコード パッケージ情報などのサービスの初期化情報。</param>
        <summary>
            サービスの初期化情報を使用して、状態プロバイダーのレプリカを初期化します。
            </summary>
        <remarks>
            複雑な処理を初期化中に行う必要はありません。 OpenAsync では、高価なまたは実行時間の長いの初期化を行う必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; IStateProviderReplica.OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">これが新規または既存のレプリカであるかどうかを示します。</param>
        <param name="partition">このレプリカが属しているパーティション。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            使用するため、状態プロバイダーのレプリカを開きます。
            </summary>
        <returns>
            非同期の open 操作を表すタスク。 結果には、パーティション内の他の状態プロバイダーのレプリカ間で状態のレプリケーションを担当するレプリケーターが含まれています。
            </returns>
        <remarks>
            この時点でのタスクを開始状態プロバイダーの初期化を拡張します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Function RestoreAsync (backupFolderPath As String) As Task Implements IStateProviderReplica.RestoreAsync" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            </param>
        <summary>
            によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。
            </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
            バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProviderReplica.RestoreAsync (string backupFolderPath, Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(string backupFolderPath, valuetype Microsoft.ServiceFabric.Data.RestorePolicy restorePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.Microsoft#ServiceFabric#Data#IStateProviderReplica#RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Data.IStateProviderReplica.RestoreAsync(System.String,Microsoft.ServiceFabric.Data.RestorePolicy,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupFolderPath" Type="System.String" />
        <Parameter Name="restorePolicy" Type="Microsoft.ServiceFabric.Data.RestorePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupFolderPath">
            レプリカがから復元するディレクトリ。
            </param>
        <param name="restorePolicy">復元のポリシー。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            によって作成されたバックアップを復元<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />または<see cref="M:Microsoft.ServiceFabric.Data.IStateProviderReplica.BackupAsync(Microsoft.ServiceFabric.Data.BackupOption,System.TimeSpan,System.Threading.CancellationToken,System.Func{Microsoft.ServiceFabric.Data.BackupInfo,System.Threading.CancellationToken,System.Threading.Tasks.Task{System.Boolean}})" />です。
            </summary>
        <returns>非同期の復元操作を表すタスク。</returns>
        <remarks>
            バックアップ/復元がサポートされていない<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;bool&gt;&gt; OnDataLossAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; OnDataLossAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnDataLossAsync As Func(Of CancellationToken, Task(Of Boolean))" />
      <MemberSignature Language="F#" Value="member this.OnDataLossAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;bool&gt;&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnDataLossAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または疑いのあるデータ損失の可能性の中に呼び出される関数を設定します。
            </summary>
        <value>
            データ損失のコールバック関数を表す関数。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync { set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; OnRestoreCompletedAsync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
      <MemberSignature Language="VB.NET" Value="Public Property OnRestoreCompletedAsync As Func(Of CancellationToken, Task)" />
      <MemberSignature Language="F#" Value="member this.OnRestoreCompletedAsync : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&gt;" Usage="Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.OnRestoreCompletedAsync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Post 復元が呼び出される関数はレプリカで実行されています。
            </summary>
        <value>
            復元時に関数を表すには、コールバック関数が完了しました。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyContext">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyContext () As IOperationDataStream Implements IStateProvider.GetCopyContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyContext</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>作成され、プライマリ レプリカにコンテキストを送信する開かれた後は、セカンダリ レプリカ上のコンテキストを取得します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</para>
        </returns>
        <remarks>
          <para>プライマリ レプリカがコンテキストを分析しを使用して状態を返送<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />です。</para>
          <para>
            <see cref="M:System.Fabric.IStateProvider.GetCopyContext" />新しく作成された、アイドルなセカンダリ レプリカで呼び出され、非同期的に、プライマリ レプリカとの双方向メッセージ交換を確立するためのメカニズムを提供します。 セカンダリ レプリカは、送信<see cref="T:System.Fabric.OperationData" />オブジェクトをプライマリ レプリカがセカンダリ レプリカでコンテキストを収集する場合の進行状況を判断できます。 プライマリ レプリカは、必要な状態に戻すを送信して応答します。
                参照してください<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />交換の一方のプライマリ レプリカにします。 </para>
          <para>メモリ内のサービスでは、<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドは呼び出されません、セカンダリ レプリカの状態は認識されている (空され、状態のすべてが必要)。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetCopyState">
      <MemberSignature Language="C#" Value="System.Fabric.IOperationDataStream IStateProvider.GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Fabric.IOperationDataStream System.Fabric.IStateProvider.GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream Implements IStateProvider.GetCopyState" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para>最大最終シーケンス番号 (LSN) を使用してコピー ストリームに配置する必要があります、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />メソッドです。
            この数より大きい Lsn が経由でレプリケーション ストリームの一部として、セカンダリ レプリカに配信される、<see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" />メソッドです。</para>
        </param>
        <param name="copyContext">
          <para><see cref="T:System.Fabric.IOperationDataStream" />を格納している、<see cref="T:System.Fabric.OperationData" />セカンダリ レプリカによって作成されるオブジェクト。 </para>
        </param>
        <summary>
          <para>プライマリ レプリカのセカンダリ レプリカを作成する必要がある状態を取得します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Fabric.IOperationDataStream" /> を返します。</para>
        </returns>
        <remarks>
          <para>同様に<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />により、セカンダリ レプリカを使用して、プライマリ レプリカにコンテキストを送信する、 <see cref="T:System.Fabric.IOperationDataStream" />、<see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />により、プライマリ レプリカで応答する、<see cref="T:System.Fabric.IOperationDataStream" />です。 ストリームには使用して、セカンダリ レプリカに配信されるオブジェクトが含まれています、<see cref="M:System.Fabric.IStateReplicator.GetCopyStream" />のメソッド、<see cref="T:System.Fabric.FabricReplicator" />クラスです。 オブジェクトを実装<see cref="T:System.Fabric.IOperation" />し、指定されたデータが含まれています。 </para>
          <para> プライマリ レプリカは、この呼び出しを受け取る、それを作成し、返す別<see cref="T:System.Fabric.IOperationDataStream" />を格納している<see cref="T:System.Fabric.OperationData" />です。 <see cref="T:System.Fabric.OperationData" />セカンダリ レプリカが次々 に提供されているために必要なデータ/状態を表す<paramref name="upToSequenceNumber" />最大 LSN。 どの程度およびセカンダリ レプリカを経由で提供されるコンテキスト情報を使用して送信されるどの状態を持つを特定できる<see cref="M:System.Fabric.IStateProvider.GetCopyContext" />メソッドです。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="long IStateProvider.GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance int64 System.Fabric.IStateProvider.GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Function GetLastCommittedSequenceNumber () As Long Implements IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>サービスがコミットされた最後のシーケンス番号を取得します。 </para>
        </summary>
        <returns>
          <para><see cref="T:System.Int64" /> を返します。</para>
        </returns>
        <remarks>
          <para>データの損失が疑われると、最初の起動時に、永続的な状態がある場合に、サービスでこのメソッドが呼び出されます。 ステートフル サービス レプリカ起動すると、以前の更新から可能性がありますが保存されるデータを復元するオプションがあります。
            このようないくつかの状態に復元するか、現在の進行状況がそのデータの最後に書き込まれたシーケンス番号です。 揮発性サービスは、単に 0 を返します。
            によって現在コミット進行状況がわかるため、フェールオーバー中に新しいプライマリ選択を判断するこのメソッドは、メモと呼ばれる、<see cref="T:System.Fabric.FabricReplicator" />その時点でクラスです。 </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.OnDataLossAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;bool&gt; IStateProvider.OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; System.Fabric.IStateProvider.OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>このレプリカ セット内のレプリカのな書き込みクォーラムが失われていることと、そのためデータが失われる可能性がありますが発生したことを示します。 レプリカ セットは、プライマリ レプリカが含まれているレプリカの大部分で構成されます。 </para>
        </summary>
        <returns>
          <para>返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.Boolean" />状態が変更されたかどうかを示すです。 メソッドが true を返します、変更されたときまたは変更されていない場合、false が返されます。</para>
        </returns>
        <remarks>
          <para>Service Fabric ランタイムが、プライマリ レプリカが含まれており、レプリカのクォーラムの障害発生時に新しいプライマリ レプリカと、すぐに、新しいプライマリ レプリカでこのメソッドを呼び出します。 データ損失の可能性が通知をプライマリ レプリカは、外部データ ソースからの状態を復元することもできます。 またはが現在の状態で実行を続行できます。 サービスが、現在の状態で実行され続ける場合は、状態の変更が行われていないことを示す、このメソッドから false を返します。 復元または不完全な作業は、ロールバックなどの状態を変更した場合は true を返します。 True が返される場合はその他のレプリカの状態が不適切な想定されます。
            そのため、Service Fabric ランタイムでは、レプリカ セットから他のレプリカを削除し、それらを再作成します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Fabric.IStateProvider.UpdateEpochAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task IStateProvider.UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task System.Fabric.IStateProvider.UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.VolatileActorStateProvider.System#Fabric#IStateProvider#UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>新しい <see cref="T:System.Fabric.Epoch" />。</para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> 以前のエポックで発見された最大のシーケンス番号 (LSN)。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>レプリカ セットの構成が変更の理由で変更または、プライマリ レプリカへの変更をしようとしましたが、レプリカを示します。 変更は、エラーまたは以前のプライマリ レプリカの負荷分散のために発生します。 エポックの変更は、特定のプライマリ レプリカによって送信された実際の構成の期間に操作を分割することによって、バリアとして機能します。</para>
        </summary>
        <returns>
          <para><see cref="T:System.Threading.Tasks.Task" /> を返します。</para>
        </returns>
        <remarks>
          <para>レプリカ セットのプライマリ レプリカが変更されているか、変更が試みられたために、このメソッドが呼び出されます。 セカンダリ レプリカは、新しいプライマリ レプリカになるとしているか、間違っている場合、新しいプライマリ レプリカにこのメソッドを受信、発生したレプリケーション ストリームから新しいプライマリ レプリカから最初の操作を取得しようとするときにします。 プライマリ レプリカでは、試行が失敗した、プライマリ レプリカをスワップする場合は、このメソッドを受け取ることがあります。</para>
          <para>内の情報、<see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />メソッドは、レプリカが受信した各エポックとそれらに含まれる最大の LSN の一覧、進行状況のベクトルを維持するためにサービスを有効にします。 現在適用されている最大の LSN と進行状況のベクター データは、セカンダリ レプリカをどのように操作の進行を記述するコピー操作中に送信するのに便利です。 コピー操作中に、セカンダリ レプリカから受信した進行状況のベクトルを比較するには、セカンダリ レプリカが最新かどうか、どの状態は、セカンダリ レプリカに送信する必要があり、セカンダリ レプリカが false の進行状況を行われたかどうかを判断するプライマリ レプリカが有効にします。 False の進行状況は、以前のエポックの LSN が、プライマリ レプリカを受信する LSN よりも大きいことを意味します。 </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>