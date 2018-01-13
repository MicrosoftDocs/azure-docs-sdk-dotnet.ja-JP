<Type Name="IActorStateManager" FullName="Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager">
  <TypeSignature Language="C#" Value="public interface IActorStateManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActorStateManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActorStateManager" />
  <TypeSignature Language="F#" Value="type IActorStateManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            状態を管理するメソッドを公開するインターフェイスを表す、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.Actor" />です。
            このインターフェイスはによって実装<see cref="P:Microsoft.ServiceFabric.Actors.Runtime.Actor.StateManager" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddOrUpdateStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; AddOrUpdateStateAsync&lt;T&gt; (string stateName, T addValue, Func&lt;string,T,T&gt; updateValueFactory, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; AddOrUpdateStateAsync&lt;T&gt;(string stateName, !!T addValue, class System.Func`3&lt;string, !!T, !!T&gt; updateValueFactory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddOrUpdateStateAsync``1(System.String,``0,System.Func{System.String,``0,``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddOrUpdateStateAsync : string * 'T * Func&lt;string, 'T, 'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.AddOrUpdateStateAsync (stateName, addValue, updateValueFactory, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="addValue" Type="T" />
        <Parameter Name="updateValueFactory" Type="System.Func&lt;System.String,T,T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">追加または更新するアクター状態の名前です。</param>
        <param name="addValue">存在しないかどうかに追加するアクター状態の値です。</param>
        <param name="updateValueFactory">存在する場合に更新するアクター状態の値を生成するファクトリ関数。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アクターを追加します。 特定の状態名、または存在する場合、指定した状態の名前で状態を更新が存在しない場合の状態。 
            </summary>
        <returns>
            非同期の追加または更新操作を表すタスク。 TResult のパラメーターの値には、追加/更新がアクター状態の値が含まれています。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.ArgumentNullException"> 指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.AddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.AddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">追加するアクター状態の名前です。</param>
        <param name="value">追加するアクター状態の値です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アクターを追加します。 特定の状態の名前と状態。
            </summary>
        <returns>
            表す非同期のタスクは、操作を追加します。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            アクター状態の特定の状態名既に存在します。
            </exception>
        <exception cref="T:System.ArgumentNullException">指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="ClearCacheAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ClearCacheAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearCacheAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ClearCacheAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearCacheAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.ClearCacheAsync cancellationToken" />
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
            すべてのキャッシュされたアクター状態とで実行される任意のサービス操作をクリア<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />の最新の状態の保存操作以降。
            </summary>
        <returns>
            非同期キャッシュのクリア操作を表すタスク。
            </returns>
        <remarks>
            実行されるすべての操作<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager" />最後に保存操作が、キャッシュをクリアするクリアされ、次の保存操作には含まれません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainsStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainsStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainsStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.ContainsStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainsStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.ContainsStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">アクター状態の名前。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した名前のアクター状態が存在するかを確認します。
            </summary>
        <returns>
            非同期チェック操作を表すタスク。 TResult パラメーターの値が<c>true</c>指定した名前と状態がそれ以外の場合に存在する場合は<c>false</c>です。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> 指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetOrAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetOrAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetOrAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetOrAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOrAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetOrAddStateAsync (stateName, value, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">アクター状態を取得または追加の名前です。</param>
        <param name="value">存在しないかどうかに追加するアクター状態の値です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            存在する場合は、指定された状態の名前を持つ、アクターの状態を取得します。 存在しない場合は、作成し、指定した名前と値を持つ新しい状態。
            </summary>
        <returns>
            表す非同期のタスクは、取得か、操作を追加します。 パラメーターには、アクター状態の値が含まれています。 TResult の値は、状態の名前を指定します。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.ArgumentNullException"> 指定された状態の名前が null です。
            有効な状態名の文字列を提供します。</exception>
        <exception cref="T:System.OperationCanceledException">指定されたを使用して、要求が取り消されました<paramref name="cancellationToken" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; GetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iActorStateManager.GetStateAsync (stateName, cancellationToken)" />
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
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">取得するアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した状態の名前を持つ、アクターの状態を取得します。
            </summary>
        <returns>
            非同期の get 操作を表すタスク。 パラメーターには、アクター状態の値が含まれています。 TResult の値は、状態の名前を指定します。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            アクター状態の特定の状態名がありません。
            </exception>
        <exception cref="T:System.ArgumentNullException">指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetStateNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetStateNamesAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetStateNamesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.GetStateNamesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStateNamesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="iActorStateManager.GetStateNamesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            現在のアクターのすべてのアクターの状態名の列挙可能なが作成されます。
            </summary>
        <returns>
            非同期の列挙操作を表すタスク。 TResult パラメーターの値は、すべてのアクターの状態名の列挙です。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.RemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.RemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">削除するアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した状態の名前を持つ、アクターの状態を削除します。
            </summary>
        <returns>非同期の削除操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Collections.Generic.KeyNotFoundException">
            アクター状態の特定の状態名がありません。
            </exception>
        <exception cref="T:System.ArgumentNullException"> 指定された状態の名前が null です。 </exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveStateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SaveStateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SaveStateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SaveStateAsync cancellationToken" />
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
            キャッシュされた状態の変更を保存 (追加/更新/削除) 最後の呼び出し以降に行われた<see cref="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SaveStateAsync(System.Threading.CancellationToken)" />アクター ランタイムによって、またはユーザーによって明示的にします。
            </summary>
        <returns>
            非同期の保存操作を表すタスク。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.SetStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iActorStateManager.SetStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">設定するアクター状態の名前です。</param>
        <param name="value">アクター状態の値です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            アクターを持つ状態特定の状態名を指定した値を設定します。
            指定した名前のアクター状態が存在しない場合が追加されます。
            </summary>
        <returns>
            一連の非同期操作を表すタスク。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.ArgumentNullException">指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryAddStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryAddStateAsync&lt;T&gt; (string stateName, T value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryAddStateAsync&lt;T&gt;(string stateName, !!T value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryAddStateAsync``1(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryAddStateAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryAddStateAsync (stateName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="value" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">追加するアクター状態の名前です。</param>
        <param name="value">追加するアクター状態の値です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。
            これは省略可能な既定値<see cref="P:System.Threading.CancellationToken.None" /></param>
        <summary>
            アクターを追加する操作は、指定された状態の名前と値を持つ状態します。 同じ名前を持つ、アクター状態は既に存在する場合は false を返します。 
            </summary>
        <returns>
            操作をブール値を表すタスクを非同期に追加します。 True を返しますの場合、値が正常に追加し、false の場合と同じ名前のアクター状態既に存在します。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.ArgumentNullException">指定された状態の名前が null です。
            有効な状態名の文字列を提供します。</exception>
        <exception cref="T:System.OperationCanceledException">指定されたを使用して、要求が取り消されました<paramref name="cancellationToken" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryGetStateAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt; TryGetStateAsync&lt;T&gt; (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype Microsoft.ServiceFabric.Data.ConditionalValue`1&lt;!!T&gt;&gt; TryGetStateAsync&lt;T&gt;(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryGetStateAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryGetStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;'T&gt;&gt;" Usage="iActorStateManager.TryGetStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Data.ConditionalValue&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">特定の状態名に関連付けられている値の型。</typeparam>
        <param name="stateName">取得するアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した状態の名前を持つ、アクター状態の取得を試みます。
            </summary>
        <returns>
            非同期の get 操作を表すタスク。 TResult パラメーターの値が含まれる<see cref="T:Microsoft.ServiceFabric.Data.ConditionalValue`1" />存在する場合は、アクターの状態が存在するかどうかとアクター状態の値を示すです。
            </returns>
        <remarks>
            状態値の型<typeparamref name="T" />する必要があります<see href="https://msdn.microsoft.com/library/ms731923.aspx">データ コントラクト</see>シリアル化可能です。
            </remarks>
        <exception cref="T:System.ArgumentNullException">指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
    <Member MemberName="TryRemoveStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TryRemoveStateAsync (string stateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; TryRemoveStateAsync(string stateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.IActorStateManager.TryRemoveStateAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TryRemoveStateAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iActorStateManager.TryRemoveStateAsync (stateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateName">削除するアクター状態の名前です。</param>
        <param name="cancellationToken">キャンセル要求を監視するためのトークン。</param>
        <summary>
            指定した状態の名前を持つ、アクター状態の削除を試みます。
            </summary>
        <returns>
            非同期の削除操作を表すタスク。 TResult のパラメーターの値は、状態が正常に削除されたかどうかを示します。
            </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> 指定された状態の名前が null です。</exception>
        <exception cref="T:System.OperationCanceledException">操作が取り消されました。</exception>
      </Docs>
    </Member>
  </Members>
</Type>