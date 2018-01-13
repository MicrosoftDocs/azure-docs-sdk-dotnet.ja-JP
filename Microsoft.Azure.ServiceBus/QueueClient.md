<Type Name="QueueClient" FullName="Microsoft.Azure.ServiceBus.QueueClient">
  <TypeSignature Language="C#" Value="public class QueueClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.IQueueClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.QueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueClient&#xA;Inherits ClientEntity&#xA;Implements IQueueClient" />
  <TypeSignature Language="F#" Value="type QueueClient = class&#xA;    inherit ClientEntity&#xA;    interface IQueueClient&#xA;    interface IReceiverClient&#xA;    interface IClientEntity&#xA;    interface ISenderClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IQueueClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             QueueClient は、すべての基本的な対話 Service Bus キューを使用できます。
             </summary>
    <remarks>使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />または<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />の高度な機能セット。
             Servicebus と通信するため、AMQP プロトコルを使用します。</remarks>
    <example>
             新しい QueueClient を作成します。
             <code>
             IQueueClient queueClient = new QueueClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             キューにメッセージを送信します。
             <code>
             byte[] data = GetData();
             await queueClient.SendAsync(data);
             </code>
            
             メッセージを受信するたびに呼び出されるメッセージのハンドラーを登録します。
             <code>
             queueClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the queueClient is opened in ReceiveMode.PeekLock mode.
                        await queueClient.CompleteAsync(message.SystemProperties.LockToken);
                    },
                    async (exceptionEvent) =&gt;
                    {
                        // Process the exception
                        Console.WriteLine("Exception = " + exceptionEvent.Exception);
                        return Task.CompletedTask;
                    });
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (connectionStringBuilder, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />名前空間およびキューの情報を持ちます。</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーをキューの操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />キューに対して操作を実行します。
            </summary>
        <remarks>最初の送信/受信操作中に開かれると、キューへの新しい接続を作成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (connectionString, entityPath, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace 接続文字列です。 キューの情報を含めないでください。</param>
        <param name="entityPath">キューの名前</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーをキューの操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />キューに対して操作を実行します。
            </summary>
        <remarks>最初の送信/受信操作中に開かれると、キューへの新しい接続を作成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueClient (string endpoint, string entityPath, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.QueueClient : string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.QueueClient" Usage="new Microsoft.Azure.ServiceBus.QueueClient (endpoint, entityPath, tokenProvider, transportType, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="entityPath">キューのパス。</param>
        <param name="tokenProvider">認証のセキュリティ トークンを生成するトークン プロバイダー。</param>
        <param name="transportType">トランスポートの種類。</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーをキューの操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            キューを指定されたエンドポイント、エンティティのパス、およびトークン プロバイダーを使用してクライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken">中止するのには、対応するメッセージのロック トークンです。</param>
        <param name="propertiesToModify">メッセージの破棄中に変更するメッセージのプロパティです。</param>
        <summary>
            破棄、<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロックのトークンを使用します。 これにより、メッセージ処理用にもう一度使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            メッセージを破棄すると、メッセージの配信回数が増加します。
            この操作は、このクライアントで受信したメッセージでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="queueClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.CancelScheduledMessageAsync(System.Int64)</InterfaceMember>
      </Implements>
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
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />をキャンセルできるメッセージのです。</param>
        <summary>
            スケジュールしたメッセージを取り消します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="queueClient.CompleteAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)</InterfaceMember>
      </Implements>
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">完了する、対応するメッセージのロック トークンです。</param>
        <summary>
            完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。 これにより、メッセージがキューから削除されます。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            この操作は、このクライアントで受信したメッセージでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
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
        <param name="lockToken">対応する配信不能メッセージのロック トークンです。</param>
        <param name="propertiesToModify">サブをキューに移動中に変更するメッセージのプロパティです。</param>
        <summary>
            メッセージを配信不能サブキューに移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="queueClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
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
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">対応する配信不能メッセージのロック トークンです。</param>
        <param name="deadLetterReason">メッセージの配信不能の理由です。</param>
        <param name="deadLetterErrorDescription">メッセージの配信不能のエラーの説明。</param>
        <summary>
            メッセージを配信不能サブキューに移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="queueClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.QueueClient/&lt;OnClosingAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.QueueClient.OperationTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.OperationTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            個々 の操作がタイムアウトする期間です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.QueueClient.Path" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キューの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.QueueClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージ フローと、1 つのアプリケーションが要求する前にローカルの取得のためすぐに使用できるメッセージがあることを目指していますによってプリフェッチ速度では、受信を使用します。
            メッセージ数の PrefetchCount をプリフェッチする 0 以外の値を設定します。
            プリフェッチをオフに値を 0 に設定します。
            既定値は 0 です。
            </summary>
        <value>キュー クライアントが同時に要求メッセージの数。</value>
        <remarks>
          <para>
            プリフェッチを有効にすると、クライアントはサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。 メッセージ ポンプが、メッセージが返されます、すぐに利用できる即時の消費量を取得するためと、クライアントはさらに、バック グラウンドでプリフェッチ バッファーへのメッセージの取得を続行します。
            </para>
          <para>
            メッセージは、プリフェッチ バッファーで使用できますが、後続の ReceiveAsync 呼び出しは、バッファーからすぐに満たされ、空き領域ができるように、バック グラウンドでバッファーが補充です。にない場合のメッセージ配信のために使用できる、受信操作は、バッファーのドレインを実行し、まで待機するかどおりをブロックします。
            </para>
          <para>この値に更新プログラムは、サービスの受信呼び出しは、[次へ] を有効になります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueName">
      <MemberSignature Language="C#" Value="public string QueueName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QueueName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.QueueName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueueName As String" />
      <MemberSignature Language="F#" Value="member this.QueueName : string" Usage="Microsoft.Azure.ServiceBus.QueueClient.QueueName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IQueueClient.QueueName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キューの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.QueueClient.ReceiveMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得、 <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> QueueClient 用です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.QueueClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.QueueClient.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この QueueClient 現在登録されているプラグインの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="queueClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="messageHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler">A<see cref="T:System.Func`3" />メッセージを処理します。</param>
        <param name="messageHandlerOptions"><see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />オプション、ポンプの設定を構成するために使用します。</param>
        <summary>
            継続的に、エンティティからメッセージを受信します。 メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。
            このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。
            </summary>
        <remarks>受信レートを高速化するプリフェッチを有効にします。</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler">A<see cref="T:System.Func`3" />メッセージを処理します。</param>
        <param name="exceptionReceivedHandler">A<see cref="T:System.Func`2" />例外時に呼び出されます。
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</param>
        <summary>
            継続的に、エンティティからメッセージを受信します。 メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。
            このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。
            </summary>
        <remarks>受信レートを高速化するプリフェッチを有効にします。
            使用して<see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />ポンプの設定を構成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="queueClient.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin"><see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />を登録するには</param>
        <summary>
            登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このキュー クライアントで使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="queueClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="sessionHandlerOptions" Type="Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
      </Parameters>
      <Docs>
        <param name="handler">A<see cref="T:System.Func`4" />メッセージを処理します。
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="sessionHandlerOptions">オプションは、セッションのポンプの設定を構成するために使用します。</param>
        <summary>
            継続的に、キューからセッション メッセージを受信します。 メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。
            このハンドラー (<see cref="T:System.Func`4" />)、新しいメッセージがキュー クライアントによって受信されるたびにでは待機します。
            </summary>
        <remarks>受信レートを高速化するプリフェッチを有効にします。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="queueClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IQueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="handler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="handler">A<see cref="T:System.Func`4" />メッセージを処理します。
            <see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション情報が含まれており、配信不能完了/破棄/やその他のような操作の実行に使用する必要があります、<see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <param name="exceptionReceivedHandler">A<see cref="T:System.Func`2" />例外時に呼び出されます。
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</param>
        <summary>
            継続的に、キューからセッション メッセージを受信します。 メッセージ ハンドラーを登録し、セッション メッセージを受信する新しいスレッドを開始します。
            このハンドラー (<see cref="T:System.Func`4" />)、新しいメッセージがキュー クライアントによって受信されるたびにでは待機します。
            </summary>
        <remarks>受信レートを高速化するプリフェッチを有効にします。
            使用して<see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />ポンプの設定を構成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.Azure.ServiceBus.Message message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.Azure.ServiceBus.Message message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="queueClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message">スケジュールされるメッセージ</param>
        <param name="scheduleEnqueueTimeUtc">UTC 時刻には、メッセージを処理できるようにする必要があります。</param>
        <summary>
            後で Service Bus に表示するメッセージをスケジュールします。
            </summary>
        <returns>スケジュール設定されたメッセージのシーケンス番号。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.SendAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
      </Implements>
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
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message"><see cref="T:Microsoft.Azure.ServiceBus.Message" /></param>
        <summary>
            Service Bus にメッセージを送信します。
            </summary>
        <returns>非同期操作</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; messageList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; messageList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (messageList As IList(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="queueClient.SendAsync messageList" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})</InterfaceMember>
      </Implements>
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
        <Parameter Name="messageList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messageList">メッセージの一覧</param>
        <summary>
            Service Bus にメッセージの一覧を送信します。
            </summary>
        <returns>非同期操作</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.QueueClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="queueClient.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceBusPluginName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceBusPluginName">名前<see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />登録解除する</param>
        <summary>
            登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>