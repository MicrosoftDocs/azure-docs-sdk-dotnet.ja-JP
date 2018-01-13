<Type Name="MessageReceiver" FullName="Microsoft.Azure.ServiceBus.Core.MessageReceiver">
  <TypeSignature Language="C#" Value="public class MessageReceiver : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageReceiver extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageReceiver&#xA;Inherits ClientEntity&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type MessageReceiver = class&#xA;    inherit ClientEntity&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             キューとサブスクリプションからメッセージを受信し、それらを認識する、MessageReceiver を使用できます。
             </summary>
    <remarks>
             MessageReceiver は高度な機能を提供する、<see cref="T:Microsoft.Azure.ServiceBus.QueueClient" />または<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />です。 たとえば、<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />を必要に応じて、メッセージを受信することができますもする必要しますが、ありますを使用してロックを手動で更新する<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />です。
             AMQP プロトコルを使用して、サービスと通信します。
             </remarks>
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
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
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />エンティティ レベルの接続の詳細を持ちます。</param>
        <param name="receiveMode"><see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />メッセージを受信する方法を指定するために使用します。 PeekLock モードに既定値です。</param>
        <param name="retryPolicy"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。 既定値は <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /> です。</param>
        <param name="prefetchCount"><see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />この受信者は受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。 既定値は 0 です。</param>
        <summary>
            新しい MessageReceiver を作成、<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />です。
            </summary>
        <remarks>最初の操作中に開かれると、エンティティへの新しい接続を作成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageReceiver (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageReceiver : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.Core.MessageReceiver" Usage="new Microsoft.Azure.ServiceBus.Core.MessageReceiver (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
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
        <Parameter Name="prefetchCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="connectionString">Service Bus との通信に使用される Namespace 接続文字列。 エンティティの詳細が含まれていない必要があります。</param>
        <param name="entityPath">この受信者を表すエンティティのパス。 キューのこれは、名前ですが、パスになりますこのサブスクリプションはします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />、このパスを作成するためにします。</param>
        <param name="receiveMode"><see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />メッセージを受信する方法を指定するために使用します。 PeekLock モードに既定値です。</param>
        <param name="retryPolicy"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount"><see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />この受信者は受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。 既定値は 0 です。</param>
        <summary>
            指定された接続文字列およびエンティティ パスから新しい MessageReceiver を作成します。
            </summary>
        <remarks>最初の操作中に開かれると、エンティティへの新しい接続を作成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.AbandonAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;AbandonAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
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
        <remarks>ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            メッセージを破棄すると、メッセージの配信回数が増加します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockTokens" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.CompleteAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;CompleteAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.CompleteAsync lockToken" />
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
            完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。 これにより、サービスからのメッセージが削除されます。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeadLetterAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.DeferAsync (lockToken, propertiesToModify)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;DeferAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            このメッセージを受信するためにもう一度、将来必要がありますを保存する、<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />を使用してメッセージを受信および<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />です。
            遅延メッセージの期限切れのメッセージ、遅延メッセージの期限切れできますも意味に影響しません。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastPeekedSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastPeekedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastPeekedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastPeekedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastPeekedSequenceNumber : int64" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.LastPeekedSequenceNumber" />
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
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      </Docs>
    </Member>
    <Member MemberName="OnAbandonAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnAbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnAbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnAbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnAbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnAbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnAbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnClosingAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCompleteAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCompleteAsync (System.Collections.Generic.IEnumerable&lt;string&gt; lockTokens);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCompleteAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; lockTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnCompleteAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCompleteAsync (lockTokens As IEnumerable(Of String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnCompleteAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnCompleteAsync lockTokens" />
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
        <param name="lockTokens"></param>
        <summary />
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeadLetterAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null, string deadLetterReason = null, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null, Optional deadLetterReason As String = null, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeadLetterAsync (lockToken, propertiesToModify, deadLetterReason, deadLetterErrorDescription)" />
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
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <param name="deadLetterReason">To be added.</param>
        <param name="deadLetterErrorDescription">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDeferAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnDeferAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnDeferAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnDeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnDeferAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.OnDeferAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.OnDeferAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">To be added.</param>
        <param name="propertiesToModify">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnMessageHandler">
      <MemberSignature Language="C#" Value="protected virtual void OnMessageHandler (Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; callback);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnMessageHandler(class Microsoft.Azure.ServiceBus.MessageHandlerOptions registerHandlerOptions, class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnMessageHandler(Microsoft.Azure.ServiceBus.MessageHandlerOptions,System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnMessageHandler (registerHandlerOptions As MessageHandlerOptions, callback As Func(Of Message, CancellationToken, Task))" />
      <MemberSignature Language="F#" Value="abstract member OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.OnMessageHandler : Microsoft.Azure.ServiceBus.MessageHandlerOptions * Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.OnMessageHandler (registerHandlerOptions, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
        <Parameter Name="callback" Type="System.Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="registerHandlerOptions">To be added.</param>
        <param name="callback">To be added.</param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPeekAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync (long fromSequenceNumber, int messageCount = 1);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnPeekAsync(int64 fromSequenceNumber, int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnPeekAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnPeekAsync (fromSequenceNumber As Long, Optional messageCount As Integer = 1) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnPeekAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnPeekAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnPeekAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber"></param>
        <param name="messageCount"></param>
        <summary />
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync (int maxMessageCount, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveAsync(int32 maxMessageCount, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveAsync (maxMessageCount As Integer, serverWaitTime As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveAsync (maxMessageCount, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxMessageCount" Type="System.Int32" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxMessageCount"></param>
        <param name="serverWaitTime"></param>
        <summary />
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync (long[] sequenceNumbers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; OnReceiveDeferredMessageAsync(int64[] sequenceNumbers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnReceiveDeferredMessageAsync(System.Int64[])" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnReceiveDeferredMessageAsync (sequenceNumbers As Long()) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.OnReceiveDeferredMessageAsync : int64[] -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.OnReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnReceiveDeferredMessageAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumbers" Type="System.Int64[]" />
      </Parameters>
      <Docs>
        <param name="sequenceNumbers">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRenewLockAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;DateTime&gt; OnRenewLockAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.DateTime&gt; OnRenewLockAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OnRenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnRenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.OnRenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.OnRenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;OnRenewLockAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken"></param>
        <summary />
        <returns>Asynchronour 操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.OperationTimeout" />
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
      <MemberSignature Language="C#" Value="public virtual string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />
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
        <summary>この受信者を表すエンティティのパス。 キューのこれは、名前ですが、パスになりますこのサブスクリプションはします。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync</InterfaceMember>
      </Implements>
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
            最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。 後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。
            受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。
            またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; PeekAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekAsync(System.Int32)</InterfaceMember>
      </Implements>
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
            最初に呼び出す<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekAsync" />この受信者の最初の作業中のメッセージをフェッチします。 後続の各呼び出しは、エンティティの後続のメッセージをフェッチします。
            受信したメッセージとは異なりピーク メッセージには、それに関連付けられたロック トークンがないし、ため完了/破棄/遅延/配信不能になりました/Renewed は指定できません。
            またとは異なり<see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />、このメソッドがフェッチされいても遅延メッセージ (ただし越えたメッセージではなく)
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekBySequenceNumberAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync (long fromSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; PeekBySequenceNumberAsync(int64 fromSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync fromSequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function PeekBySequenceNumberAsync (fromSequenceNumber As Long, messageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.PeekBySequenceNumberAsync : int64 * int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.PeekBySequenceNumberAsync (fromSequenceNumber, messageCount)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.PeekBySequenceNumberAsync(System.Int64,System.Int32)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;PeekBySequenceNumberAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fromSequenceNumber" Type="System.Int64" />
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="fromSequenceNumber">メッセージのバッチを参照する開始点です。</param>
        <param name="messageCount">取得するメッセージの数。</param>
        <summary>バッチのメッセージをピークします。</summary>
        <returns>バッチのメッセージをピークします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.PrefetchCount" />
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
        <value>メッセージの受信者が同時に要求メッセージの数。</value>
        <remarks>
          <para>
            プリフェッチを有効にすると、受信側はサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。 初期の単一の受信/ReceiveAsync 呼び出ししたがって取得するメッセージに対して返されるとすぐに利用可能な即時の消費量と、クライアントでは、バック グラウンドでプリフェッチ バッファーが満杯にさらにメッセージの取得に進みます。
            </para>
          <para>
            メッセージは、プリフェッチ バッファーで使用できますが、後続の ReceiveAsync 呼び出しは、バッファーからすぐに満たされ、空き領域ができるように、バック グラウンドでバッファーが補充です。にない場合のメッセージ配信のために使用できる、受信操作は、バッファーのドレインを実行し、まで待機するかどおりをブロックします。
            </para>
          <para>プリフェッチ同等のでも、 <see cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" /> Api です。</para>
          <para>この値に更新プログラムは、サービスの受信呼び出しは、[次へ] を有効になります。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync</InterfaceMember>
      </Implements>
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
            定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージ。 メッセージがない場合は null を返します。</returns>
        <remarks>期間の後に操作がタイムアウト<see cref="P:Microsoft.Azure.ServiceBus.ClientEntity.OperationTimeout" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync (int maxMessageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt;&gt; ReceiveAsync(int32 maxMessageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync maxMessageCount" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32)</InterfaceMember>
      </Implements>
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
            最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。
            </summary>
        <returns>受信したメッセージの一覧です。 メッセージがない場合は null を返します。</returns>
        <remarks>も少ない受信<paramref name="maxMessageCount" />メッセージは空のエンティティを示す値ではありません。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (operationTimeout As TimeSpan) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout">タイムアウトになる前にメッセージを受信するためクライアントが待機するを期間します。</param>
        <summary>
            定義されているエンティティからメッセージを受信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxMessageCount As Integer, operationTimeout As TimeSpan) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveAsync (maxMessageCount, operationTimeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveAsync(System.Int32,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
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
            最大値を受け取る<paramref name="maxMessageCount" />によって定義されているエンティティからのメッセージ<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.Path" />を使用して<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />モード。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumbers As IEnumerable(Of Long)) As Task(Of IList(Of Message))" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;&#xA;override this.ReceiveDeferredMessageAsync : seq&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumbers" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Collections.Generic.IEnumerable{System.Int64})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
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
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveDeferredMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; ReceiveDeferredMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveDeferredMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveDeferredMessageAsync (sequenceNumber As Long) As Task(Of Message)" />
      <MemberSignature Language="F#" Value="abstract member ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;&#xA;override this.ReceiveDeferredMessageAsync : int64 -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Message&gt;" Usage="messageReceiver.ReceiveDeferredMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.ReceiveDeferredMessageAsync(System.Int64)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;ReceiveDeferredMessageAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
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
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.DeferAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      </Docs>
    </Member>
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.ReceiveMode" />
      <MemberType>Property</MemberType>
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
            取得、<see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />現在受信機のです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在登録されているプラグインの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, messageHandlerOptions)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="messageReceiver.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
        <param name="exceptionReceivedHandler">A<see cref="T:System.Func`2" />を使用して例外を通知します。</param>
        <summary>
            継続的に、エンティティからメッセージを受信します。 メッセージ ハンドラーを登録し、メッセージを受信する新しいスレッドを開始します。
            このハンドラー (<see cref="T:System.Func`3" />)、受信側で新しいメッセージを受信するたびにでは待機します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="messageReceiver.RegisterPlugin serviceBusPlugin" />
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
            登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このレシーバーと共に使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLockAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLockAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="messageReceiver.RenewLockAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>
            ロック トークンで指定されたメッセージのロックを更新します。 ロックは、キューに指定された設定に基づいて更新されます。
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.RenewLockAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync (lockToken As String) As Task(Of DateTime)" />
      <MemberSignature Language="F#" Value="abstract member RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;&#xA;override this.RenewLockAsync : string -&gt; System.Threading.Tasks.Task&lt;DateTime&gt;" Usage="messageReceiver.RenewLockAsync lockToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.IMessageReceiver.RenewLockAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageReceiver/&lt;RenewLockAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
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
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageReceiver.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="messageReceiver.UnregisterPlugin serviceBusPluginName" />
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
        <param name="serviceBusPluginName"><see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />の登録解除するプラグイン。</param>
        <summary>
            登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>