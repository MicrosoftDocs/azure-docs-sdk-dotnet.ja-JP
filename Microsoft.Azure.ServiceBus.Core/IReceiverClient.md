<Type Name="IReceiverClient" FullName="Microsoft.Azure.ServiceBus.Core.IReceiverClient">
  <TypeSignature Language="C#" Value="public interface IReceiverClient : Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IReceiverClient implements class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IReceiverClient&#xA;Implements IClientEntity" />
  <TypeSignature Language="F#" Value="type IReceiverClient = interface&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
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
            メッセージを受信するための共通の機能の記述に使用されるインターフェイス<see cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />と<see cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />です。
            </summary>
    <remarks>使用して<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />の高度な機能セット。</remarks>
    <altmember cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.IQueueClient" />
    <altmember cref="T:Microsoft.Azure.ServiceBus.ISubscriptionClient" />
  </Docs>
  <Members>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbandonAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.AbandonAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbandonAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.AbandonAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">中止するのには、対応するメッセージのロック トークンです。</param>
        <param name="propertiesToModify">メッセージの破棄中に変更するメッセージのプロパティです。</param>
        <summary>
            破棄、<see cref="T:Microsoft.Azure.ServiceBus.Message" />ロックのトークンを使用します。 これにより、メッセージ処理用にもう一度使用できます。
            </summary>
        <returns>To be added.</returns>
        <remarks>ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            メッセージを破棄すると、メッセージの配信回数が増加します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync (string lockToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CompleteAsync(string lockToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync (lockToken As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CompleteAsync : string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.CompleteAsync lockToken" />
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
        <param name="lockToken">完了する、対応するメッセージのロック トークンです。</param>
        <summary>
            完了、<see cref="T:Microsoft.Azure.ServiceBus.Message" />のロック トークンを使用します。 これにより、メッセージがキューから削除されます。
            </summary>
        <returns>非同期操作です。</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, Optional propertiesToModify As IDictionary(Of String, Object) = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, propertiesToModify)" />
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
        <param name="lockToken">対応する配信不能メッセージのロック トークンです。</param>
        <param name="propertiesToModify">サブをキューに移動中に変更するメッセージのプロパティです。</param>
        <summary>
            メッセージを配信不能サブキューに移動します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string lockToken, string deadLetterReason, string deadLetterErrorDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeadLetterAsync(string lockToken, string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.DeadLetterAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (lockToken As String, deadLetterReason As String, Optional deadLetterErrorDescription As String = null) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeadLetterAsync : string * string * string -&gt; System.Threading.Tasks.Task" Usage="iReceiverClient.DeadLetterAsync (lockToken, deadLetterReason, deadLetterErrorDescription)" />
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
            ロック トークンは含まれて<see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.LockToken" />場合にのみ、<see cref="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />に設定されている<see cref="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />です。
            を配信不能キューからメッセージを受信するために必要になります、新しい<see cref="T:Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />、対応するパスにします。
            使用することができます<see cref="M:Microsoft.Azure.ServiceBus.EntityNameHelper.FormatDeadLetterPath(System.String)" />これを支援します。
            この操作は、このレシーバーによって受信されたメッセージをでのみ実行できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.Path" />
      <MemberType>Property</MemberType>
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
            パスを取得、<see cref="T:Microsoft.Azure.ServiceBus.Core.IReceiverClient" />です。 これは、キューの名前またはサブスクリプションの完全なパスのいずれかです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
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
        <value>To be added.</value>
        <remarks>
          <para>
            プリフェッチを有効にすると、受信側はサイレント モードでどのようなアプリケーションすぐに確認のより PrefetchCount 上限に達するまで、多くのメッセージを取得します。 初期の単一の受信/ReceiveAsync 呼び出ししたがって取得するメッセージに対して返されるとすぐに利用可能な即時の消費量と、クライアントでは、バック グラウンドでプリフェッチ バッファーが満杯にさらにメッセージの取得に進みます。
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiveMode As ReceiveMode" />
      <MemberSignature Language="F#" Value="member this.ReceiveMode : Microsoft.Azure.ServiceBus.ReceiveMode" Usage="Microsoft.Azure.ServiceBus.Core.IReceiverClient.ReceiveMode" />
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
    <Member MemberName="RegisterMessageHandler">
      <MemberSignature Language="C#" Value="public void RegisterMessageHandler (Func&lt;Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; handler, Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RegisterMessageHandler(class System.Func`3&lt;class Microsoft.Azure.ServiceBus.Message, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; handler, class Microsoft.Azure.ServiceBus.MessageHandlerOptions messageHandlerOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), registerHandlerOptions As MessageHandlerOptions)" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Microsoft.Azure.ServiceBus.MessageHandlerOptions -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, messageHandlerOptions)" />
      <MemberType>Method</MemberType>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterMessageHandler (handler As Func(Of Message, CancellationToken, Task), exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="abstract member RegisterMessageHandler : Func&lt;Microsoft.Azure.ServiceBus.Message, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; unit" Usage="iReceiverClient.RegisterMessageHandler (handler, exceptionReceivedHandler)" />
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
            使用して<see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />ポンプの設定を構成します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>