<Type Name="SessionClient" FullName="Microsoft.Azure.ServiceBus.SessionClient">
  <TypeSignature Language="C#" Value="public sealed class SessionClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionClient&#xA;Inherits ClientEntity&#xA;Implements ISessionClient" />
  <TypeSignature Language="F#" Value="type SessionClient = class&#xA;    inherit ClientEntity&#xA;    interface ISessionClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.ISessionClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             セッションのクライアントは、同じセッション Id ですべてのメッセージと対話するために使用するセッション オブジェクトを受け入れるように使用できます。
             </summary>
    <remarks>
             任意のセッションまたは特定のセッションを受け入れることができます (によって識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />セッション クライアントを使用します。
             セッションを同意すると、としてそれを使用できます、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />同じセッション id を持つメッセージのみを受信します。参照してください<see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション オブジェクトの使用法をします。
             これは、AMQP プロトコルを使用して、サービスと通信します。
             </remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <example>
             新しい SessionClient を作成するには
             <code>
             ISessionClient sessionClient = new SessionClient(
                 namespaceConnectionString,
                 queueName,
                 ReceiveMode.PeekLock);
             </code>
            
             指定したセッション Id のセッション オブジェクトを受信するには
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync(sessionId);
             </code>
            
             任意のセッションを受信するには
             <code>
             IMessageSession session = await sessionClient.AcceptMessageSessionAsync();
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionStringBuilder, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="receiveMode"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" />メッセージを受信する方法を指定するために使用します。 PeekLock モードに既定値です。</param>
        <param name="retryPolicy"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> ServiceBus との通信に使用されます。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" />セッション オブジェクトは、受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。 既定値は 0 です。</param>
        <summary>
            新しい SessionClient を作成します。<see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /></summary>
        <remarks>すべてのセッション オブジェクトに使用すると、エンティティに新しい接続を作成するこのクライアントを使用して受け入れられます。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.ReceiveMode receiveMode = Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null, int prefetchCount = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, valuetype Microsoft.Azure.ServiceBus.ReceiveMode receiveMode, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy, int32 prefetchCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.ReceiveMode,Microsoft.Azure.ServiceBus.RetryPolicy,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionClient : string * string * Microsoft.Azure.ServiceBus.ReceiveMode * Microsoft.Azure.ServiceBus.RetryPolicy * int -&gt; Microsoft.Azure.ServiceBus.SessionClient" Usage="new Microsoft.Azure.ServiceBus.SessionClient (connectionString, entityPath, receiveMode, retryPolicy, prefetchCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <param name="entityPath">この受信者を表すエンティティのパス。 キューのこれは、名前ですが完全なパスを指定このサブスクリプションの場合。</param>
        <param name="receiveMode"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.ReceiveMode" />メッセージを受信する方法を指定するために使用します。 PeekLock モードに既定値です。</param>
        <param name="retryPolicy"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> ServiceBus との通信に使用されます。 既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></param>
        <param name="prefetchCount"><see cref="P:Microsoft.Azure.ServiceBus.SessionClient.PrefetchCount" />セッション オブジェクトは、受信操作が保留されているかどうかに関係なくアクティブに受信メッセージの数の上限を指定します。 既定値は 0 です。</param>
        <summary>
            指定された接続文字列およびエンティティ パスから新しい SessionClient を作成します。
            </summary>
        <remarks>すべてのセッション オブジェクトに使用すると、エンティティに新しい接続を作成するこのクライアントを使用して受け入れられます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。
            個別のセッションは、追加プラグインをさらに登録できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sessionId">SessionId そのすべてのメッセージ内に存在します。</param>
        <summary>
            によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。
            個別のセッションは、追加プラグインをさらに登録できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime">呼び出しが 次のセッションをフェッチする待機時間の長さ。</param>
        <summary>
            任意のセッション オブジェクトを取得<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />そのわかり、sessionId のメッセージの受信に使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。
            個別のセッションは、追加プラグインをさらに登録できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync (string sessionId, TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync(string sessionId, valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;&#xA;override this.AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="sessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;AcceptMessageSessionAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">SessionId そのすべてのメッセージ内に存在します。</param>
        <param name="serverWaitTime">呼び出しが 次のセッションをフェッチする待機時間の長さ。</param>
        <summary>
            によって識別される特定のセッション オブジェクトを取得<paramref name="sessionId" />そのわかり、sessionId のメッセージの受信に使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>登録されているすべてのプラグイン<see cref="T:Microsoft.Azure.ServiceBus.SessionClient" />それぞれに適用される<see cref="T:Microsoft.Azure.ServiceBus.MessageSession" />は受け入れられます。
            個別のセッションは、追加プラグインをさらに登録できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityPath">
      <MemberSignature Language="C#" Value="public string EntityPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.SessionClient.EntityPath" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            エンティティのパスを取得します。 これは、キューの名前またはサブスクリプションの完全なパスのいずれかです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="sessionClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.SessionClient/&lt;OnClosingAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionClient.OperationTimeout" />
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
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.SessionClient.RegisteredPlugins" />
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
            現在登録されているプラグインの一覧を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="sessionClient.RegisterPlugin serviceBusPlugin" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)</InterfaceMember>
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
        <Parameter Name="serviceBusPlugin" Type="Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />
      </Parameters>
      <Docs>
        <param name="serviceBusPlugin">登録する <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />。</param>
        <summary>
            登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このレシーバーと共に使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="sessionClient.UnregisterPlugin serviceBusPluginName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.IClientEntity.UnregisterPlugin(System.String)</InterfaceMember>
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