<Type Name="ISessionClient" FullName="Microsoft.Azure.ServiceBus.ISessionClient">
  <TypeSignature Language="C#" Value="public interface ISessionClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISessionClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ISessionClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISessionClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type ISessionClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.IClientEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             セッションのクライアントについて説明します。 セッションのクライアントは、同じセッション Id ですべてのメッセージと対話するために使用するセッション オブジェクトを受け入れるように使用できます。
             </summary>
    <remarks>
             任意のセッションまたは特定のセッションを受け入れることができます (によって識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />セッション クライアントを使用します。
             セッションを同意すると、としてそれを使用できます、<see cref="T:Microsoft.Azure.ServiceBus.Core.MessageReceiver" />同じセッション id を持つメッセージのみを受信します。参照してください<see cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />セッション オブジェクトの使用法をします。
             <example>新しい SessionClient を作成するには
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
             </code></example></remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.IMessageSession" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.SessionClient" />
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.IMessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync sessionId" />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
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
        <param name="serverWaitTime">呼び出しが待機する対象の次のセッションをフェッチする時間です。</param>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.ISessionClient.AcceptMessageSessionAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (sessionId As String, serverWaitTime As TimeSpan) As Task(Of IMessageSession)" />
      <MemberSignature Language="F#" Value="abstract member AcceptMessageSessionAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.IMessageSession&gt;" Usage="iSessionClient.AcceptMessageSessionAsync (sessionId, serverWaitTime)" />
      <MemberType>Method</MemberType>
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
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="sessionId">SessionId そのすべてのメッセージ内に存在します。</param>
        <param name="serverWaitTime">呼び出しが待機する対象の次のセッションをフェッチする時間です。</param>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntityPath As String" />
      <MemberSignature Language="F#" Value="member this.EntityPath : string" Usage="Microsoft.Azure.ServiceBus.ISessionClient.EntityPath" />
      <MemberType>Property</MemberType>
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
  </Members>
</Type>