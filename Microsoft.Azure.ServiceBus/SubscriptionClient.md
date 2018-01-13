<Type Name="SubscriptionClient" FullName="Microsoft.Azure.ServiceBus.SubscriptionClient">
  <TypeSignature Language="C#" Value="public class SubscriptionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionClient&#xA;Inherits ClientEntity&#xA;Implements ISubscriptionClient" />
  <TypeSignature Language="F#" Value="type SubscriptionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISubscriptionClient&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.ISubscriptionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             SubscriptionClient は、すべての基本的な対話をサービス バスのサブスクリプションで使用できます。
             </summary>
    <remarks>サービス バスと通信するため、AMQP プロトコルを使用します。 使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />の高度な機能セット。</remarks>
    <example>
             新しい SubscriptionClient を作成します。
             <code>
             ISubscriptionClient subscriptionClient = new SubscriptionClient(
                 namespaceConnectionString,
                 topicName,
                 subscriptionName,
                 ReceiveMode.PeekLock,
                 RetryExponential);
             </code>
            
             メッセージを受信するたびに呼び出されるメッセージのハンドラーを登録します。
             <code>
             subscriptionClient.RegisterMessageHandler(
                    async (message, token) =&gt;
                    {
                        // Process the message
                        Console.WriteLine($"Received message: SequenceNumber:{message.SystemProperties.SequenceNumber} Body:{Encoding.UTF8.GetString(message.Body)}");
            
                        // Complete the message so that it is not received again.
                        // This can be done only if the subscriptionClient is opened in ReceiveMode.PeekLock mode.
                        await subscriptionClient.CompleteAsync(message.SystemProperties.LockToken);
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
      <MemberSignature Language="C#" Value="public SubscriptionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionStringBuilder, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />名前空間とトピックの情報を持ちます。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーのサブスクリプション操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />サブスクリプションに対して操作を実行します。
            </summary>
        <remarks>新たに作成中、最初に開かれると、サブスクリプションへの接続の受信操作します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string connectionString, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string topicPath, string subscriptionName, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (connectionString, topicPath, subscriptionName, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString">Namespace 接続文字列です。 トピック サブスクリプションまたはサブスクリプションの情報を含めないでください。</param>
        <param name="topicPath">トピックへのパス。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーのサブスクリプション操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.SubscriptionClient" />サブスクリプションに対して操作を実行します。
            </summary>
        <remarks>新たに作成中、最初に開かれると、サブスクリプションへの接続の受信操作します。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionClient (string endpoint, string topicPath, string subscriptionName, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string topicPath, string subscriptionName, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.#ctor(System.String,System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SubscriptionClient : string * string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.SubscriptionClient" Usage="new Microsoft.Azure.ServiceBus.SubscriptionClient (endpoint, topicPath, subscriptionName, tokenProvider, transportType, receiveMode, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="receiveMode" Type="Microsoft.Azure.ServiceBus.ReceiveMode" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint">Service Bus の完全修飾ドメイン名。 最も可能性の高い、{yournamespace}. servicebus.windows .net</param>
        <param name="topicPath">トピック パスです。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="tokenProvider">認証のセキュリティ トークンを生成するトークン プロバイダー。</param>
        <param name="transportType">トランスポートの種類。</param>
        <param name="receiveMode">メッセージの受信のモードです。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />します。PeekLock です。</param>
        <param name="retryPolicy">ポリシーのサブスクリプション操作を再試行してください。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <summary>
            サブスクリプションを指定されたエンドポイント、エンティティのパス、およびトークン プロバイダーを使用してクライアントの新しいインスタンスを作成します。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <remarks>ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            メッセージを破棄すると、メッセージの配信回数が増加します。
            この操作は、このクライアントで受信したメッセージでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (Microsoft.Azure.ServiceBus.RuleDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(class Microsoft.Azure.ServiceBus.RuleDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function AddRuleAsync (description As RuleDescription) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : Microsoft.Azure.ServiceBus.RuleDescription -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync description" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(Microsoft.Azure.ServiceBus.RuleDescription)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;AddRuleAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.ServiceBus.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">規則の説明を追加するルールを提供します。</param>
        <summary>
            サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。
            </summary>
        <returns>非同期の追加ルールの操作を表すタスク インスタンス。</returns>
        <remarks>
            規則は、トピックからメッセージがサブスクリプションにアクセスする必要がありますを決定するサブスクリプションを追加できます。
            既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。
            個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。
            複数のフィルターは、論理 OR 条件を使用して相互に結合します。 つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AddRuleAsync (string ruleName, Microsoft.Azure.ServiceBus.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddRuleAsync(string ruleName, class Microsoft.Azure.ServiceBus.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)" />
      <MemberSignature Language="F#" Value="abstract member AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task&#xA;override this.AddRuleAsync : string * Microsoft.Azure.ServiceBus.Filter -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.AddRuleAsync (ruleName, filter)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.AddRuleAsync(System.String,Microsoft.Azure.ServiceBus.Filter)</InterfaceMember>
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
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.Azure.ServiceBus.Filter" />
      </Parameters>
      <Docs>
        <param name="ruleName">To be added.</param>
        <param name="filter">対象となるメッセージが一致するフィルター式です。</param>
        <summary>
            サブスクリプションに達しようとしてトピックからメッセージをフィルター処理の現在のサブスクリプションにルールを追加します。
            </summary>
        <returns>非同期の追加ルールの操作を表すタスク インスタンス。</returns>
        <remarks>
            規則は、トピックからメッセージがサブスクリプションにアクセスする必要がありますを決定するサブスクリプションを追加できます。
            既定の<see cref="T:Microsoft.Azure.ServiceBus.TrueFilter" />という名前のルール<see cref="F:Microsoft.Azure.ServiceBus.RuleDescription.DefaultRuleName" />サブスクリプションの作成中には常に追加します。
            個別の名前を持つ複数のルールは、同じサブスクリプションに追加できます。
            複数のフィルターは、論理 OR 条件を使用して相互に結合します。 つまり、任意のフィルターが成功した場合、メッセージに渡されますサブスクリプション。
            ルール名の最大許容長は、50 文字です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.CompleteAsync lockToken" />
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
            完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。 これにより、サブスクリプションからメッセージが削除されます。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            この操作は、このクライアントで受信したメッセージでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync lockToken" />
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
        <Parameter Name="lockToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lockToken">対応する配信不能メッセージのロック トークンです。</param>
        <summary>
            メッセージを配信不能サブキューに移動します。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能サブキューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />または<see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このクライアントで受信したメッセージでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt; GetRulesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.GetRulesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync () As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="abstract member GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;&#xA;override this.GetRulesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;" Usage="subscriptionClient.GetRulesAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.GetRulesAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;GetRulesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.ServiceBus.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            サブスクリプションに関連付けられているすべてのルールを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;OnClosingAsync&gt;d__61))</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.OperationTimeout" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.Path" />
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
            サブスクリプション クライアントの形式のパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatSubscriptionPath(System.String,System.String)" />
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.PrefetchCount" />
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
        <value>サブスクリプション クライアントが同時に要求メッセージの数。</value>
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
    <Member MemberName="ReceiveMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.ReceiveMode" />
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
            取得、 <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" /> SubscriptionClient 用です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.RegisteredPlugins" />
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
            この SubscriptionClient 現在登録されているプラグインの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
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
        <Parameter Name="registerHandlerOptions" Type="Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
            使用して<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />ポンプの設定を構成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="subscriptionClient.RegisterPlugin serviceBusPlugin" />
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
            登録、 <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> Service Bus からメッセージを受信するために使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.SessionHandlerOptions sessionHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.SessionHandlerOptions -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, sessionHandlerOptions)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)</InterfaceMember>
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
            このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。
            </summary>
        <remarks>受信レートを高速化するプリフェッチを有効にします。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterSessionHandler">
      <MemberSignature Language="C#" Value="public void RegisterSessionHandler (Func&lt;Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterSessionHandler(class System.Func`4&lt;class Microsoft.Azure.ServiceBus.IMessageSession, class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterSessionHandler (handler As Func(Of IMessageSession, Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit&#xA;override this.RegisterSessionHandler : Func&lt;Microsoft.Azure.ServiceBus.IMessageSession, Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="subscriptionClient.RegisterSessionHandler (handler, exceptionReceivedHandler)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})</InterfaceMember>
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
            このハンドラー (<see cref="T:System.Func`4" />) サブスクリプション クライアントが新しいメッセージを受信するたびにでは待機します。
            </summary>
        <remarks>  受信レートを高速化するプリフェッチを有効にします。
            使用して<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />ポンプの設定を構成します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveRuleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveRuleAsync (string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveRuleAsync(string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RemoveRuleAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveRuleAsync (ruleName As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.RemoveRuleAsync : string -&gt; System.Threading.Tasks.Task" Usage="subscriptionClient.RemoveRuleAsync ruleName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISubscriptionClient.RemoveRuleAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SubscriptionClient/&lt;RemoveRuleAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ruleName">ルールの名前。</param>
        <summary>
            によって識別されるサブスクリプションの規則を削除します<paramref name="ruleName" />です。
            </summary>
        <returns>非同期の削除規則の操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionName">
      <MemberSignature Language="C#" Value="public string SubscriptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionName As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionName : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.SubscriptionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.SubscriptionName</InterfaceMember>
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
            サブスクリプションの名前を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicPath">
      <MemberSignature Language="C#" Value="public string TopicPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicPath As String" />
      <MemberSignature Language="F#" Value="member this.TopicPath : string" Usage="Microsoft.Azure.ServiceBus.SubscriptionClient.TopicPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISubscriptionClient.TopicPath</InterfaceMember>
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
            対応するトピックのパスを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SubscriptionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="subscriptionClient.UnregisterPlugin serviceBusPluginName" />
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