<Type Name="MessageReceiver" FullName="Microsoft.ServiceBus.Messaging.MessageReceiver">
  <TypeSignature Language="C#" Value="public abstract class MessageReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessageReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessageReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IMessageBrowser" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> MessageReceiver クラスは、メッセージ コンテナーからメッセージを受信し、それらを承認に使用します。 </summary>
    <remarks>あるメッセージの配信メカニズムでは提供されません既定すべて時間信頼性の高いメッセージ受信に注意してください。 Service Bus は、システムの外になった後に、メッセージを削除します。 配信の保証 PeekLock 配信モードを使用することができます。
                      <example><code>
                      //********************************************************************************
             //                             Sending messages to a Queue
             //********************************************************************************
             
             送信者 MessageSender myMessageSender 作成 myQueueClient.CreateSender(SendMode.Default); を =
             
             メッセージ ボックスの一覧を送信&lt;文字列&gt;問題新しいリストを =&lt;文字列&gt;(); (var 問題に関連した問題) foreach {myMessageSender.Send (新しい BrokeredMessage(issue));}
             </code></example><example><code>
             //********************************************************************************
             //                           Recieving messages from a Queue
             //********************************************************************************
             
             受信者 MessageReceiver myMessageReceiver 作成 myQueueClient.CreateReceiver(ReceiveMode.PeekLock); を =
             
             メッセージを受信する (int カウント = 0 になります。 カウント&lt;Issues.Count; 数 + +) {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}
             </code></example><example><code>
             //********************************************************************************
             //                    Receiving messages from a particular session
             //********************************************************************************
             
             サブスクリプション クライアント SubscriptionClient mySubscriptionClient を作成するファクトリを = です。CreateSubscriptionClient(mySubscription) です。
             
             受信者 MessageReceiver myMessageReceiver 作成 mySubscriptionClient.AcceptMessageSession(ReceiveMode.PeekLock); を =
            
             メッセージを受信する (int カウント = 0; 数 * lt;Issues.Count です。+ +) カウント {var メッセージ = myMessageReceiver.Receive(); message.Complete() です。}
             </code></example></remarks>
  </Docs>
  <Members>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid -&gt; unit&#xA;override this.Abandon : Guid -&gt; unit" Usage="messageReceiver.Abandon lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</param>
        <summary>メッセージを破棄し、メッセージのロックの所有権を放棄します。</summary>
        <remarks>メッセージの受信者は、キュー/トピックからメッセージを取得します。 失敗した場合、このメソッドを呼び出す必要があります。 Service Bus には、メッセージの配信回数が 1 ずつ増分されます。 メッセージの受信者は今すぐ、メッセージが再度表示されるか、配信不能キューに移動を試行できますか。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abandon(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Abandon : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Abandon (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Abandon(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>メッセージを破棄し、メッセージのロックの所有権を放棄します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、破棄するロックされているメッセージ インスタンスにバインドします。</param>
        <summary>非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.AbandonAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>非同期的にメッセージを破棄し、メッセージのロックの所有権を放棄します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BatchFlushInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バッチのフラッシュ間隔を取得します。</summary>
        <value>バッチのフラッシュ間隔。 既定値は、20 ミリ秒です。</value>
        <remarks>SbmpTransportSetting.BatchFlushInterval 経由でその値を設定することができます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchingEnabled">
      <MemberSignature Language="C#" Value="protected bool BatchingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BatchingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property BatchingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BatchingEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.BatchingEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バッチ処理が有効になっているかどうかを示す値を取得します。</summary>
        <value>バッチ処理が有効である場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Complete(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Complete(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Complete : Guid -&gt; unit&#xA;override this.Complete : Guid -&gt; unit" Usage="messageReceiver.Complete lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Complete(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。 これはピーク ロックのモードでメッセージが受信したときにのみ使用できます。 ロック トークンは、完了するか、メッセージを破棄する内部的に使用されます。</param>
        <summary>メッセージの受信操作を完了します。
            AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</summary>
        <remarks> このメソッドは、メッセージの確実な配信の受信機と Service Bus との間のハンドシェイクとして使用されます。 このメソッドを呼び出す前に、受信側に失敗した場合、メッセージがキューに保持されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <summary>非同期的にメッセージの受信操作を完了します。
            AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatch">
      <MemberSignature Language="C#" Value="public void CompleteBatch (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CompleteBatch(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CompleteBatch (lockTokens As IEnumerable(Of Guid))" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatch : seq&lt;Guid&gt; -&gt; unit&#xA;override this.CompleteBatch : seq&lt;Guid&gt; -&gt; unit" Usage="messageReceiver.CompleteBatch lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatch(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens">ロック トークン。</param>
        <summary>メッセージのバッチの受信操作を完了します。
            AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteBatchAsync (System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteBatchAsync (lockTokens As IEnumerable(Of Guid)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteBatchAsync : seq&lt;Guid&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteBatchAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.CompleteBatchAsync(System.Collections.Generic.IEnumerable{System.Guid})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="lockTokens">ロック トークン。</param>
        <summary>非同期的にメッセージのバッチの受信操作を完了します。
            AMQP を使用して場合、この操作はこのレシーバーによって受信されたメッセージをでのみ実行できます。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid -&gt; unit&#xA;override this.DeadLetter : Guid -&gt; unit" Usage="messageReceiver.DeadLetter lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <summary>配信不能メッセージを配信不能キューに移動します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.DeadLetter : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>配信不能メッセージを配信不能キューに移動します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeadLetter(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetter(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="abstract member DeadLetter : Guid * string * string -&gt; unit&#xA;override this.DeadLetter : Guid * string * string -&gt; unit" Usage="messageReceiver.DeadLetter (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetter(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <param name="deadLetterReason">メッセージの配信不能の理由です。</param>
        <param name="deadLetterErrorDescription">メッセージの配信不能のエラーの説明。</param>
        <summary>配信不能メッセージを配信不能キューに移動します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <summary>非同期的に配信不能メッセージを配信不能キューに移動します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>非同期的に配信不能メッセージを配信不能キューに移動します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (Guid lockToken, string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(valuetype System.Guid lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As Guid, deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : Guid * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeadLetterAsync(System.Guid,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークンは、ロックされているメッセージ インスタンスにバインドします。</param>
        <param name="deadLetterReason">メッセージの配信不能の理由です。</param>
        <param name="deadLetterErrorDescription">メッセージの配信不能のエラーの説明。</param>
        <summary>非同期的に配信不能メッセージを配信不能キューに移動します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid)" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid -&gt; unit&#xA;override this.Defer : Guid -&gt; unit" Usage="messageReceiver.Defer lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />です。 これはピーク ロックのモードでメッセージが受信したときにのみ使用できます。 ロック トークンは、完了するか、メッセージを破棄する内部的に使用されます。</param>
        <summary>受信側がメッセージの処理を遅延することを示します。</summary>
        <remarks>ユーザーを保留する前にする必要がありますを確保メッセージの受信確認を後で取得します。 </remarks>
        <exception cref="P:Microsoft.ServiceBus.Common.Fx.Exception">受信コンテキストが null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Defer(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="abstract member Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit&#xA;override this.Defer : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="messageReceiver.Defer (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Defer(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>受信側がメッセージの処理を遅延することを示します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <summary>非同期的にメッセージの処理を延期します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (Guid lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(valuetype System.Guid lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As Guid, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : Guid * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.DeferAsync(System.Guid,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.Guid" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="lockToken">ロック トークン。</param>
        <param name="propertiesToModify">変更するプロパティです。</param>
        <summary>非同期的にメッセージの処理を延期します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockToken">
      <MemberSignature Language="C#" Value="protected static Guid GetLockToken (Microsoft.ServiceBus.Messaging.BrokeredMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig valuetype System.Guid GetLockToken(class Microsoft.ServiceBus.Messaging.BrokeredMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken(Microsoft.ServiceBus.Messaging.BrokeredMessage)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockToken (message As BrokeredMessage) As Guid" />
      <MemberSignature Language="F#" Value="static member GetLockToken : Microsoft.ServiceBus.Messaging.BrokeredMessage -&gt; Guid" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockToken message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.ServiceBus.Messaging.BrokeredMessage" />
      </Parameters>
      <Docs>
        <param name="message"><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />ロック トークンを取得します。</param>
        <summary>メッセージにバインドされているロック トークンを取得します。</summary>
        <returns>メッセージのロック トークンです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLockTokens">
      <MemberSignature Language="C#" Value="protected static System.Collections.Generic.IEnumerable&lt;Guid&gt; GetLockTokens (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; GetLockTokens(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GetLockTokens (messages As IEnumerable(Of BrokeredMessage)) As IEnumerable(Of Guid)" />
      <MemberSignature Language="F#" Value="static member GetLockTokens : seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; -&gt; seq&lt;Guid&gt;" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.GetLockTokens messages" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
      </Parameters>
      <Docs>
        <param name="messages">ロック トークンを取得するメッセージのコレクション。</param>
        <summary>指定されたメッセージのコレクションからロックのトークンのコレクションを取得します。</summary>
        <returns>指定されたメッセージからロックのトークンのコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected internal virtual T GetProperty&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance !!T GetProperty&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.GetProperty``1" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Function GetProperty(Of T) () As T" />
      <MemberSignature Language="F#" Value="abstract member GetProperty : unit -&gt; 'T&#xA;override this.GetProperty : unit -&gt; 'T" Usage="messageReceiver.GetProperty " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T"></typeparam>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public virtual long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定が、メッセージのシーケンス番号の最後のピークします。</summary>
        <value>メッセージのシーケンス番号は最後ピークします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiveMode Mode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.ReceiveMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.Messaging.ReceiveMode with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージを取得します受信モード。</summary>
        <value>メッセージは受信モードです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="protected internal virtual bool OffsetInclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbandon">
      <MemberSignature Language="C#" Value="protected virtual void OnAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnAbandon (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    タイムアウト期間。 </param>
        <summary> 破棄操作を実行します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAbandon">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAbandon (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAbandon(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginAbandon(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAbandon : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginAbandon (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="propertiesToModify"> 変更するプロパティです。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnAbandon または BeginAbandon 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージを破棄し、そのロックを解放する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; deliveryTags, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; deliveryTags, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;ArraySegment&lt;byte&gt;&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, deliveryTags, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="deliveryTags" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="deliveryTags"> 配信のタグのコレクション。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnComplete または BeginComplete 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginComplete">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginComplete (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnComplete または BeginComplete 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージの受信を完了する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="propertiesToModify"> 変更するプロパティです。</param>
        <param name="deadLetterReason"> 理由の配信不能メッセージ。</param>
        <param name="deadLetterErrorDescription"> 配信不能のエラーの説明メッセージ。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnDeadLetter または BeginDeadLetter 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />配信不能キューにメッセージの配信できなかったを移動する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginDefer">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginDefer (trackingContext, lockTokens, propertiesToModify, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="propertiesToModify"> 変更するプロパティです。</param>
        <param name="fromSync"> 同期の開始。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>OnDefer または BeginDefer 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />メッセージの処理を中断する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginPeek">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginPeek (trackingContext, fromSequenceNumber, messageCount, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="fromSequenceNumber"> 操作を開始する位置のシーケンス番号。</param>
        <param name="messageCount"> メッセージの数。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>BeginPeek 操作の呼び出し時に実行します。</summary>
        <returns>操作の結果。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, bool fromSync, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, bool fromSync, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Boolean,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * bool * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginRenewMessageLocks (trackingContext, lockTokens, fromSync, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="fromSync" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="lockTokens"> ロックのトークンのコレクションはロックされているメッセージ インスタンスにバインドされます。</param>
        <param name="fromSync"> 同期の開始時刻です。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback"> 操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>メッセージのロックの OnBegin 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />ロック メッセージの処理を更新する非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, sequenceNumbers, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="sequenceNumbers"> SequenceNumbers です。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="callback"> コールバック。 </param>
        <param name="state">    状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージの数。 </param>
        <param name="serverWaitTime"> サーバーがタイムアウトするまでの時間を待機します。 </param>
        <param name="callback">     コールバック。 </param>
        <param name="state">        状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginTryReceive2 (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceive2(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceive2(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceive2 : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceive2 (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージの数。 </param>
        <param name="serverWaitTime"> サーバーがタイムアウトするまでの時間を待機します。 </param>
        <param name="callback">     コールバック。 </param>
        <param name="state">        状態。 </param>
        <summary> Begin try を実行するアクションを受信します。 </summary>
        <returns> が必要です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginTryReceiveEventData (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginTryReceiveEventData(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnBeginTryReceiveEventData(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginTryReceiveEventData : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messageReceiver.OnBeginTryReceiveEventData (trackingContext, messageCount, serverWaitTime, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="trackingContext">この操作を追跡、トランザクションが関連付けられているコンテキスト情報。</param>
        <param name="messageCount">受信メッセージの数。</param>
        <param name="serverWaitTime">時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state"> 非同期操作に関する状態情報を含むユーザー定義のオブジェクト。</param>
        <summary>イベント データの OnTryReceive または BeginTryReceive 操作の呼び出し時に実行します。</summary>
        <returns><see cref="T:System.IAsyncResult" />イベント データを受信しようとする非同期操作を参照します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnComplete (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnComplete(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnComplete(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit&#xA;override this.OnComplete : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnComplete (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="timeout">    タイムアウト期間。 </param>
        <summary> 完全なアクションを実行します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetter">
      <MemberSignature Language="C#" Value="protected virtual void OnDeadLetter (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDeadLetter(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDeadLetter(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit&#xA;override this.OnDeadLetter : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * TimeSpan -&gt; unit" Usage="messageReceiver.OnDeadLetter (trackingContext, lockTokens, propertiesToModify, deadLetterReason, deadLetterErrorDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"></param>
        <param name="deadLetterReason">  メッセージの配信不能の理由です。 </param>
        <param name="deadLetterErrorDescription">  メッセージの配信不能の説明情報。 </param>
        <param name="timeout">    タイムアウト期間。 </param>
        <summary> 配信不能メッセージ キュー アクションへの移行を実行します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDefer">
      <MemberSignature Language="C#" Value="protected virtual void OnDefer (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDefer(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnDefer(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.Collections.Generic.IDictionary{System.String,System.Object},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit&#xA;override this.OnDefer : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * System.Collections.Generic.IDictionary&lt;string, obj&gt; * TimeSpan -&gt; unit" Usage="messageReceiver.OnDefer (trackingContext, lockTokens, propertiesToModify, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="lockTokens"> ロック トークン。 </param>
        <param name="propertiesToModify"></param>
        <param name="timeout">    タイムアウト期間。 </param>
        <summary> Defer アクションを実行します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAbandon">
      <MemberSignature Language="C#" Value="protected abstract void OnEndAbandon (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndAbandon(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndAbandon(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndAbandon (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndAbandon : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndAbandon result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <summary>最後の破棄アクションを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndComplete">
      <MemberSignature Language="C#" Value="protected abstract void OnEndComplete (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndComplete(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndComplete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndComplete (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndComplete : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndComplete result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <summary>最後の完全なアクションを実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDeadLetter">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDeadLetter (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDeadLetter(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDeadLetter(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDeadLetter (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDeadLetter : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDeadLetter result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />を非同期的に完了した操作を参照するオブジェクト。</param>
        <summary>配信不能メッセージ キュー アクションへの移行は終了を実行します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndDefer">
      <MemberSignature Language="C#" Value="protected abstract void OnEndDefer (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnEndDefer(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndDefer(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnEndDefer (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member OnEndDefer : IAsyncResult -&gt; unit" Usage="messageReceiver.OnEndDefer result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <summary>最後の実行アクションを延期します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndPeek">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnEndPeek(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndPeek(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndPeek (result As IAsyncResult) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member OnEndPeek : IAsyncResult -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnEndPeek result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">操作の結果。</param>
        <summary>EndPeek 操作を実行します。</summary>
        <returns>メッセージの一覧。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected abstract System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnEndRenewMessageLocks (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnEndRenewMessageLocks(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndRenewMessageLocks(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndRenewMessageLocks (result As IAsyncResult) As IEnumerable(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnEndRenewMessageLocks : IAsyncResult -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnEndRenewMessageLocks result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">操作の結果。</param>
        <summary>メッセージ ロック EndRenew アクションを実行します。</summary>
        <returns>A<see cref="T:System.Collections.Generic.IEnumerable`1" />ロック メッセージのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <param name="messages">受信したメッセージのコレクションです。</param>
        <summary>最後の実行の受信アクションを再試行してください。</summary>
        <returns>これが成功した場合は true。失敗した場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceive2">
      <MemberSignature Language="C#" Value="protected abstract bool OnEndTryReceive2 (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceive2(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceive2(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndTryReceive2 (result As IAsyncResult, ByRef messages As IEnumerable(Of BrokeredMessage)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceive2 : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceive2 (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <param name="messages">受信したメッセージのコレクションです。</param>
        <summary>最後の実行の受信アクションを再試行してください。</summary>
        <returns>これが成功した場合は true。失敗した場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndTryReceiveEventData">
      <MemberSignature Language="C#" Value="protected virtual bool OnEndTryReceiveEventData (IAsyncResult result, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnEndTryReceiveEventData(class System.IAsyncResult result, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnEndTryReceiveEventData(System.IAsyncResult,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData}@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnEndTryReceiveEventData (result As IAsyncResult, ByRef messages As IEnumerable(Of EventData)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool&#xA;override this.OnEndTryReceiveEventData : IAsyncResult *  -&gt; bool" Usage="messageReceiver.OnEndTryReceiveEventData (result, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="result">結果。</param>
        <param name="messages">受信したメッセージのコレクションです。</param>
        <summary>イベント データの EndTryReceive アクションを実行します。</summary>
        <returns>これが成功した場合は true。失敗した場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessage">
      <MemberSignature Language="C#" Value="public void OnMessage (Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessage(class System.Action`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessage (callback As Action(Of BrokeredMessage), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessage : Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessage (callback, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Action&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback">この操作は完了時に呼び出すメソッド。</param>
        <param name="options">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</param>
        <summary>イベント駆動型メッセージ ポンプにメッセージを処理します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageAsync">
      <MemberSignature Language="C#" Value="public void OnMessageAsync (Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt; callback, Microsoft.ServiceBus.Messaging.OnMessageOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void OnMessageAsync(class System.Func`2&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage, class System.Threading.Tasks.Task&gt; callback, class Microsoft.ServiceBus.Messaging.OnMessageOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnMessageAsync(System.Func{Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task},Microsoft.ServiceBus.Messaging.OnMessageOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub OnMessageAsync (callback As Func(Of BrokeredMessage, Task), options As OnMessageOptions)" />
      <MemberSignature Language="F#" Value="member this.OnMessageAsync : Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage, System.Threading.Tasks.Task&gt; * Microsoft.ServiceBus.Messaging.OnMessageOptions -&gt; unit" Usage="messageReceiver.OnMessageAsync (callback, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.OnMessageOptions" />
      </Parameters>
      <Docs>
        <param name="callback">この操作は完了時に呼び出すメソッド。</param>
        <param name="options">指定します、<see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />メッセージ ポンプをインスタンス化するオプションです。</param>
        <summary>イベント駆動型メッセージ ポンプにメッセージを非同期的に処理します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeek">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, long fromSequenceNumber, int messageCount, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; OnPeek(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int64 fromSequenceNumber, int32 messageCount, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnPeek(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int64,System.Int32,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.OnPeek : Microsoft.ServiceBus.Tracing.TrackingContext * int64 * int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.OnPeek (trackingContext, fromSequenceNumber, messageCount, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> 追跡コンテキスト。</param>
        <param name="fromSequenceNumber"> ここに表示する場所からシーケンス番号。</param>
        <param name="messageCount"> メッセージの数。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <summary>ピーク操作の呼び出し時に実行します。</summary>
        <returns>メッセージをピークします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewMessageLocks">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;DateTime&gt; OnRenewMessageLocks (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;Guid&gt; lockTokens, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;valuetype System.DateTime&gt; OnRenewMessageLocks(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.Guid&gt; lockTokens, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnRenewMessageLocks(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Guid},System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;&#xA;override this.OnRenewMessageLocks : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;Guid&gt; * TimeSpan -&gt; seq&lt;DateTime&gt;" Usage="messageReceiver.OnRenewMessageLocks (trackingContext, lockTokens, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="lockTokens" Type="System.Collections.Generic.IEnumerable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="trackingContext"> 追跡コンテキスト。</param>
        <param name="lockTokens"> ロック トークン。</param>
        <param name="timeout"> 時間間隔、操作は、タイムアウトになるまで待機します。</param>
        <summary>メッセージのロックの更新アクションを実行します。</summary>
        <returns>更新されたロック メッセージです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers, TimeSpan timeout, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers, valuetype System.TimeSpan timeout, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Collections.Generic.IEnumerable{System.Int64},System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * seq&lt;int64&gt; * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, sequenceNumbers, timeout, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="sequenceNumbers"> 配信確認メッセージ。 </param>
        <param name="timeout">  タイムアウト期間。 </param>
        <param name="messages"> [out]メッセージ。 </param>
        <summary> 再試行を実行するアクションを受信します。 </summary>
        <returns> 成功した場合、false が失敗した場合は true。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTryReceive">
      <MemberSignature Language="C#" Value="protected virtual bool OnTryReceive (Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int messageCount, TimeSpan serverWaitTime, out System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; messages);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnTryReceive(class Microsoft.ServiceBus.Tracing.TrackingContext trackingContext, int32 messageCount, valuetype System.TimeSpan serverWaitTime, [out] class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp; messages) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.OnTryReceive(Microsoft.ServiceBus.Tracing.TrackingContext,System.Int32,System.TimeSpan,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.BrokeredMessage}@)" />
      <MemberSignature Language="F#" Value="abstract member OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool&#xA;override this.OnTryReceive : Microsoft.ServiceBus.Tracing.TrackingContext * int * TimeSpan *  -&gt; bool" Usage="messageReceiver.OnTryReceive (trackingContext, messageCount, serverWaitTime, messages)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="trackingContext" Type="Microsoft.ServiceBus.Tracing.TrackingContext" />
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="messages" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="trackingContext">使用する TrackingContext です。</param>
        <param name="messageCount"> メッセージの数。 </param>
        <param name="serverWaitTime">  サーバーがタイムアウトするまでの時間を待機します。 </param>
        <param name="messages">     [out]メッセージ。 </param>
        <summary> 再試行を実行するアクションを受信します。 </summary>
        <returns> 成功した場合、false が失敗した場合は true。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public abstract string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>に対して相対的なキューまたはトピックのパスを取得、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />ベース アドレス。</summary>
        <value>キューまたはトピックのパスを表す文字列。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを読み取ります。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />を読み取るには、次のメッセージを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Peek">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Peek (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Peek(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Peek(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Peek (fromSequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Peek : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Peek fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.Peek(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">メッセージを読み取る場所からシーケンス番号。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを読み取ります。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />を読み取るには、次のメッセージを表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (fromSequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">メッセージを読み取る場所からシーケンス番号。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、次のメッセージを非同期に読み取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">メッセージの数。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく次のバッチのメッセージを読み取ります。</summary>
        <returns>読み取られるメッセージのバッチです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; PeekBatch(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatch(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatch (fromSequenceNumber As Long, messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.PeekBatch : int64 * int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.PeekBatch (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatch(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">バッチ メッセージの読み取りにどこからシーケンス番号。</param>
        <param name="messageCount">メッセージの数。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく次のバッチのメッセージを読み取ります。</summary>
        <returns>読み取られるメッセージのバッチです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">メッセージの数。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、メッセージの次のバッチを非同期に読み取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync (long fromSequenceNumber, int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; PeekBatchAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.PeekBatchAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBatchAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.PeekBatchAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.PeekBatchAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageBrowser.PeekBatchAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">バッチ メッセージの読み取りにどこからシーケンス番号。</param>
        <param name="messageCount">メッセージの数。</param>
        <summary>受信側またはメッセージの送信元の状態を変更することがなく、メッセージの次のバッチを非同期に読み取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</summary>
        <value>メッセージの受信者が同時に要求メッセージの数。</value>
        <remarks> サーバーに次の受信呼び出しで有効になります。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>受信、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が現在のキューまたはトピックからです。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</returns>
        <remarks>Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (sequenceNumber As Long) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : int64 -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">受信するメッセージのシーケンス番号。</param>
        <summary>現在のキューまたはトピックからメッセージを受信します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</returns>
        <remarks>Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、要求された sequenceNumber を持つメッセージを配置することはできません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Receive (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Receive(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (serverWaitTime As TimeSpan) As BrokeredMessage" />
      <MemberSignature Language="F#" Value="abstract member Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage&#xA;override this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="messageReceiver.Receive serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.Receive(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">操作がタイムアウトする前に、期間、サーバーが待機します。</param>
        <summary>受信、<see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />が現在のキューまたはトピックからです。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />受信したメッセージを表すです。</returns>
        <remarks>Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的に、現在のキューまたはトピックからメッセージを受信します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (sequenceNumber As Long) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">受信するメッセージのシーケンス番号。</param>
        <summary>非同期的に、現在のキューまたはトピックからメッセージを受信します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (serverWaitTime As TimeSpan) As Task(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">操作がタイムアウトする前に、期間、サーバーが待機します。</param>
        <summary>非同期的に、現在のキューまたはトピックからメッセージを受信します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (sequenceNumbers As IEnumerable(Of Long)) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : seq&lt;int64&gt; -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">シーケンス番号。</param>
        <summary>メッセージのバッチを受け取ります。</summary>
        <returns>メッセージのバッチです。</returns>
        <remarks>Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、要求された sequenceNumber を持つメッセージを配置することはできません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">バッチに返されるメッセージの数。 これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</param>
        <summary>メッセージのバッチを受け取ります。</summary>
        <returns>メッセージのバッチです。</returns>
        <remarks>Null は、操作を指定すると、タイムアウトを超えましたまたはいますが、成功した操作は、これ以上メッセージを受信する場合、この API で返さことができます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatch">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt; ReceiveBatch(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatch (messageCount As Integer, serverWaitTime As TimeSpan) As IEnumerable(Of BrokeredMessage)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&#xA;override this.ReceiveBatch : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;" Usage="messageReceiver.ReceiveBatch (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatch(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount">バッチに返されるメッセージの数。 これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</param>
        <param name="serverWaitTime">サーバーは、時間を待機します。</param>
        <summary>メッセージのバッチを受け取ります。</summary>
        <returns>メッセージのバッチです。</returns>
        <remarks>Null 値によって返されるこの API 操作を超えた場合、指定したタイムアウトまたは操作に成功しましたが、これ以上メッセージを受信することがあります。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (System.Collections.Generic.IEnumerable&lt;long&gt; sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;int64&gt; sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Collections.Generic.IEnumerable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">シーケンス番号。</param>
        <summary>非同期的にメッセージのバッチを受け取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync messageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount">バッチに返されるメッセージの数。 これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</param>
        <summary>非同期的にメッセージのバッチを受け取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync (int messageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt; ReceiveBatchAsync(int32 messageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveBatchAsync (messageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IEnumerable(Of BrokeredMessage))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;&#xA;override this.ReceiveBatchAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;" Usage="messageReceiver.ReceiveBatchAsync (messageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.IMessageReceiver.ReceiveBatchAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.BrokeredMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="messageCount">バッチに返されるメッセージの数。 これは、概算値よりも少ないまたは複数のメッセージとして<paramref name="messageCount" />返される可能性があります。</param>
        <param name="serverWaitTime">サーバーは、時間を待機します。</param>
        <summary>非同期的にメッセージのバッチを受け取ります。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverStartTime">
      <MemberSignature Language="C#" Value="protected internal virtual Nullable&lt;DateTime&gt; ReceiverStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ReceiverStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property ReceiverStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ReceiverStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.ReceiverStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または受信側の開始時刻を設定します。</summary>
        <value>受信側の開始時刻です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOffset">
      <MemberSignature Language="C#" Value="protected internal virtual string StartOffset { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Property StartOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartOffset : string with get, set" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.StartOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはオフセットの開始位置を設定します。</summary>
        <value>オフセットの開始点です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportsGetRuntimeEntityDescription">
      <MemberSignature Language="C#" Value="protected internal abstract bool SupportsGetRuntimeEntityDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride ReadOnly Property SupportsGetRuntimeEntityDescription As Boolean" />
      <MemberSignature Language="F#" Value="member this.SupportsGetRuntimeEntityDescription : bool" Usage="Microsoft.ServiceBus.Messaging.MessageReceiver.SupportsGetRuntimeEntityDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>