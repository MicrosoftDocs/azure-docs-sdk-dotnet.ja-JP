<Type Name="IActorStateProvider" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider">
  <TypeSignature Language="C#" Value="public interface IActorStateProvider : Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateProvider implements class Microsoft.ServiceFabric.Data.IStateProviderReplica, class Microsoft.ServiceFabric.Data.IStateProviderReplica2" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateProvider&#xA;Implements IStateProviderReplica2" />
  <TypeSignature Language="F#" Value="type IActorStateProvider = interface&#xA;    interface IStateProviderReplica2&#xA;    interface IStateProviderReplica" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Data.IStateProviderReplica2</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            アクター状態プロバイダーは、アクター ランタイムと通信するために実装する必要があるインターフェイスを表します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorActivatedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActorActivatedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ActorActivatedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ActorActivatedAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ActorActivatedAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ActorActivatedAsync (actorId, cancellationToken)" />
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
        <param name="actorId">アクティブ化したアクターの ID です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定したアクターの ID を持つアクターのアクティブ化プロセスの一部として呼び出され、
            </summary>
        <returns>非同期のアクターのアクティブ化通知の処理を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ContainsStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateProvider.ContainsStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId">状態の有無を確認する対象のアクターの ID です。</param>
        <param name="stateName">有無を確認するアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アクター状態プロバイダーに指定されたアクター ID の名前を指定した状態で、アクター状態が含まれるかどうか確認します
            </summary>
        <returns>
            非同期チェック操作を表すタスク。 TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, string reminderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteReminderAsync (actorId, reminderName, cancellationToken)" />
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
        <Parameter Name="reminderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを削除するアクターの ID です。</param>
        <param name="reminderName">削除するアラームの名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            存在する場合は、指定された通知の名前を持つアクター アラームを削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRemindersAsync (System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; reminderNames, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteRemindersAsync(class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.ServiceFabric.Actors.ActorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;string&gt;&gt; reminderNames, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.DeleteRemindersAsync(System.Collections.Generic.IReadOnlyDictionary{Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteRemindersAsync : System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.ServiceFabric.Actors.ActorId, System.Collections.Generic.IReadOnlyCollection&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.DeleteRemindersAsync (reminderNames, cancellationToken)" />
      <MemberType>Method</MemberType>
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
    <Member MemberName="EnumerateStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; EnumerateStateNamesAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; EnumerateStateNamesAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.EnumerateStateNamesAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnumerateStateNamesAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateProvider.EnumerateStateNamesAsync (actorId, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId">列挙可能なを作成する対象のアクターの ID です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定したアクターの ID に関連付けられたすべての状態名の列挙可能な作成します。
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
    <Member MemberName="GetActorsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync (int numItemsToReturn, Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Query.PagedResult`1&lt;class Microsoft.ServiceFabric.Actors.ActorId&gt;&gt; GetActorsAsync(int32 numItemsToReturn, class Microsoft.ServiceFabric.Actors.Query.ContinuationToken continuationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.GetActorsAsync(System.Int32,Microsoft.ServiceFabric.Actors.Query.ContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActorsAsync : int * Microsoft.ServiceFabric.Actors.Query.ContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;" Usage="iActorStateProvider.GetActorsAsync (numItemsToReturn, continuationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Query.PagedResult&lt;Microsoft.ServiceFabric.Actors.ActorId&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="numItemsToReturn" Type="System.Int32" />
        <Parameter Name="continuationToken" Type="Microsoft.ServiceFabric.Actors.Query.ContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="numItemsToReturn">返される要求された項目の数。</param>
        <param name="continuationToken">
            クエリから結果を開始する継続トークンです。
            継続トークンの null 値は、開始、先頭の値の形式を返すことを意味します。
            </param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            状態プロバイダーから要求された ActorID の数を取得します。
            </summary>
        <returns>サーバーへの呼び出しの非同期操作を表すタスク。</returns>
        <remarks>
            <paramref name="continuationToken" />この API の呼び出し時にアクター状態プロバイダーの状態に対する相対パスです。 アクターの状態プロバイダーの変更を記述する場合 (つまり新しいアクターがアクティブ化または既存のアクターが削除されます) API と継続の間にこれを呼び出す前に、状態が変更された) の前の呼び出しからのトークンを指定して、結果はされたエントリを含めることがあります既に以前の呼び出しでフェッチします。
            </remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation actorTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.Initialize(Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation -&gt; unit" Usage="iActorStateProvider.Initialize actorTypeInformation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorTypeInformation" Type="Microsoft.ServiceFabric.Actors.Runtime.ActorTypeInformation" />
      </Parameters>
      <Docs>
        <param name="actorTypeInformation">アクター クラスの型情報</param>
        <summary>
            関連付けられているアクター型の型情報を使用してアクター状態プロバイダーを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadRemindersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt; LoadRemindersAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadRemindersAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadRemindersAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Actors.Runtime.IActorReminderCollection&gt;" Usage="iActorStateProvider.LoadRemindersAsync cancellationToken" />
      <MemberType>Method</MemberType>
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
    <Member MemberName="LoadStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LoadStateAsync&lt;T&gt; (Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; LoadStateAsync&lt;T&gt;(class Microsoft.ServiceFabric.Actors.ActorId actorId, string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.LoadStateAsync``1(Microsoft.ServiceFabric.Actors.ActorId,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadStateAsync : Microsoft.ServiceFabric.Actors.ActorId * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateProvider.LoadStateAsync (actorId, stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
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
        <param name="actorId">状態の読み込み先のアクターの ID です。</param>
        <param name="stateName">読み込みにアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定されたアクター ID の指定した状態の名前に関連付けられているアクターの状態を読み込みます
            </summary>
        <returns>
            非同期ロード操作を表すタスク。 TResult のパラメーターの値には、特定の状態名に関連付けられているアクター状態の値が含まれています。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">指定された状態の名前に関連付けられているアクターの状態は存在しません。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReminderCallbackCompletedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReminderCallbackCompletedAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReminderCallbackCompletedAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.ReminderCallbackCompletedAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReminderCallbackCompletedAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.ReminderCallbackCompletedAsync (actorId, reminder, cancellationToken)" />
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
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを所有しているアクターの ID</param>
        <param name="reminder">正常に完了したアクターに送信します。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アラームが起動し、そのコールバックの実行が終了したときに呼び出される<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IRemindable.ReceiveReminderAsync(System.String,System.Byte[],System.TimeSpan,System.TimeSpan)" />が正常にします。
            </summary>
        <returns>
            非同期の通知コールバックを表すタスクでは、通知の処理が完了しました。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveActorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveActorAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveActorAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.RemoveActorAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveActorAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.RemoveActorAsync (actorId, cancellationToken)" />
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
        <param name="actorId">状態を削除するアクターの ID です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            すべての既存の状態と原子的に指定されたアクターの ID に関連付けられた通知を削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveReminderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveReminderAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveReminderAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class Microsoft.ServiceFabric.Actors.Runtime.IActorReminder reminder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveReminderAsync(Microsoft.ServiceFabric.Actors.ActorId,Microsoft.ServiceFabric.Actors.Runtime.IActorReminder,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveReminderAsync : Microsoft.ServiceFabric.Actors.ActorId * Microsoft.ServiceFabric.Actors.Runtime.IActorReminder * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveReminderAsync (actorId, reminder, cancellationToken)" />
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
        <Parameter Name="reminder" Type="Microsoft.ServiceFabric.Actors.Runtime.IActorReminder" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">アラームを保存する対象のアクターの ID です。</param>
        <param name="reminder">アクター アラームを保存します。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定したアクター ID アラームを保存します。 指定した名前のアクター アラームが存在しない場合は、それ以外の場合と同じ名前のアクター アラームを既存のアクター アラームが更新を追加します。 
            </summary>
        <returns>非同期の保存操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (Microsoft.ServiceFabric.Actors.ActorId actorId, System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(class Microsoft.ServiceFabric.Actors.ActorId actorId, class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; stateChanges, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider.SaveStateAsync(Microsoft.ServiceFabric.Actors.ActorId,System.Collections.Generic.IReadOnlyCollection{Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : Microsoft.ServiceFabric.Actors.ActorId * System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateProvider.SaveStateAsync (actorId, stateChanges, cancellationToken)" />
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
        <Parameter Name="stateChanges" Type="System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.ServiceFabric.Actors.Runtime.ActorStateChange&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="actorId">状態の変更を保存する対象のアクターの ID です。</param>
        <param name="stateChanges">状態の変更を保存するコレクション。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            保存指定されたアクターのセット状態の変更、指定したアクターの ID をアトミックにします。
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
  </Members>
</Type>