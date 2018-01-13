<Type Name="IMessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.IMessageReceiver">
  <TypeSignature Language="C#" Value="public interface IMessageReceiver : Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageReceiver implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageReceiver&#xA;Implements IReceiverClient" />
  <TypeSignature Language="F#" Value="type IMessageReceiver = interface&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IReceiverClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             キューとサブスクリプションからメッセージを受信し、それらを認識する、MessageReceiver を使用できます。
             </summary>
    <remarks>
             MessageReceiver は高度な機能を提供する、<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />または<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />です。 たとえば、<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />を必要に応じて、メッセージを受信することができますもする必要しますが、ありますを使用してロックを手動で更新する<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />です。
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.QueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
    <example>
             サブスクリプションからメッセージを受信する新しい MessageReceiver を作成します。
             <code>
             IMessageReceiver messageReceiver = new MessageReceiver(
                 namespaceConnectionString,
                 EntityNameHelper.FormatSubscriptionPath(topicName, subscriptionName),
                 ReceiveMode.PeekLock);
             </code>
            
             サブスクリプションからメッセージを受信します。
             <code>
             var message = await messageReceiver.ReceiveAsync();
             await messageReceiver.CompleteAsync(message.SystemProperties.LockToken);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens"><see cref="T:System.Collections.Generic.IEnumerable`1" />を完了する、対応するメッセージのロック トークンを含んでいます。</param>
        <summary>
            完了する一連の<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロック トークンのリストを使用します。 これにより、サービスからのメッセージが削除されます。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン、<see cref="T:Microsoft.Azure.ServiceBus.Message" />です。</param>
        <param name="propertiesToModify">メッセージを保留中に変更するメッセージのプロパティです。</param>
        <summary>受信側がメッセージの処理を遅延することを示します。</summary>
        <returns>To be added.</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            このメッセージを受信するためにもう一度、将来必要がありますを保存する、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />を使用してメッセージを受信および<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />です。
            遅延メッセージの期限切れのメッセージ、遅延メッセージの期限切れできますも意味に影響しません。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.IMessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>最後のピークされたメッセージのシーケンス番号を取得します。</summary>
        <value>最後のピークされたメッセージのシーケンス番号。</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            受信側またはメッセージの送信元の状態を変更せずには、次の作業中のメッセージをフェッチします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。 ピークが無い場合は null を返します。</returns>
        <remarks>
            最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。 後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。
            異なり、受信したメッセージの数、ピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。
            またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">メッセージ数。</param>
        <summary>
            受信側またはメッセージの送信元の状態を変更することがなく、アクティブなメッセージの次のバッチをフェッチします。
            </summary>
        <returns>一覧の<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。 ピークが無い場合は null を返します。</returns>
        <remarks>
            最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。 後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。
            受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。
            またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">メッセージを読み取る場所からシーケンス番号。</param>
        <summary>
            受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。
            </summary>
        <returns>返す非同期操作、<see cref="T:Microsoft.Azure.ServiceBus.Message" />を読み取るには、次のメッセージを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">メッセージのバッチを参照する開始点です。</param>
        <param name="messageCount">メッセージ数。</param>
        <summary>バッチのメッセージをピークします。</summary>
        <returns>バッチのメッセージをピークします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージ。 メッセージがない場合は null を返します。</returns>
        <remarks>期間の後に操作がタイムアウト<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">受信するメッセージの最大数。</param>
        <summary>
            最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージの一覧です。 メッセージがない場合は null を返します。</returns>
        <remarks>も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</param>
        <summary>
            定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージ。 メッセージがない場合は null を返します。</returns>
        <remarks>
            パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。 これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount">受信するメッセージの最大数。</param>
        <param name="operationTimeout">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</param>
        <summary>
            最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />を使用して<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージの一覧です。 メッセージがない場合は null を返します。</returns>
        <remarks>も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。
            パラメーター <paramref name="operationTimeout" /> (いずれかまたは接続を再確立する必要がある場合、最初の受信時に) 接続を確立するために、受信側にかかる時間が含まれています。 これがスローされる場合は、接続の確立がタイムアウトになる、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusTimeoutException" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveDeferredMessageAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers"><see cref="T:System.Collections.Generic.IEnumerable`1" />を受信するシーケンス番号を含むです。</param>
        <summary>
            受信、<see cref="T:System.Collections.Generic.IList`1" />で識別される遅延メッセージの<paramref name="sequenceNumbers" />します。
            </summary>
        <returns>シーケンス番号によって識別されるメッセージが返されます。 メッセージが見つからない場合は null を返します。
            メッセージが遅延されていない場合をスローします。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="iMessageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">受信するメッセージのシーケンス番号。</param>
        <summary>
            によって識別される特定の遅延メッセージ受信<paramref name="sequenceNumber" />です。
            </summary>
        <returns>メッセージのシーケンス番号によって識別<paramref name="sequenceNumber" />です。 このようなメッセージが存在しない場合は null を返します。
            メッセージは保留されていない場合にスローします。</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="iMessageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            メッセージのロックを更新します。 ロックは、キューに指定された設定に基づいて更新されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。
            メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。
            各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;DateTime&gt; RenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; RenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="iMessageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">メッセージに関連付けられたロック トークンです。</param>
        <summary>
            メッセージのロックを更新します。 ロックは、キューに指定された設定に基づいて更新されます。
            <returns>トークンの有効期限の日付と時刻 (utc) 形式での新しいロックします。</returns></summary>
        <returns>非同期操作です。</returns>
        <remarks>
            メッセージを受信する<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />モードでは、メッセージがロックされているこの受信者インスタンス用のサーバーに指定された期間中 (LockDuration) キュー/サブスクリプションの作成中にします。
            メッセージの処理は、この期間を超える必要がある場合、ロックを更新する必要があります。
            各更新のエンティティに設定 LockDuration によってメッセージがロックされている時間にリセットされます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>