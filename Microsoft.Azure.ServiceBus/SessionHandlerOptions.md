<Type Name="SessionHandlerOptions" FullName="Microsoft.Azure.ServiceBus.SessionHandlerOptions">
  <TypeSignature Language="C#" Value="public sealed class SessionHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SessionHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SessionHandlerOptions" />
  <TypeSignature Language="F#" Value="type SessionHandlerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>ポンプ処理を使用してセッションに関連付けられているオプションを提供<see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />と<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterSessionHandler(System.Func{Microsoft.Azure.ServiceBus.IMessageSession,Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.SessionHandlerOptions)" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionHandlerOptions (Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.SessionHandlerOptions.#ctor(System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.SessionHandlerOptions : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; Microsoft.Azure.ServiceBus.SessionHandlerOptions" Usage="new Microsoft.Azure.ServiceBus.SessionHandlerOptions exceptionReceivedHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionReceivedHandler" Type="System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;" />
      </Parameters>
      <Docs>
        <param name="exceptionReceivedHandler">A<see cref="T:System.Func`2" />例外時に呼び出されます。
            <see cref="T:Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs" />例外に関するコンテキスト情報が含まれています。</param>
        <summary><see cref="T:Microsoft.Azure.ServiceBus.SessionHandlerOptions" /> クラスの新しいインスタンスを初期化します。
            既定値: <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" /> = 2000 <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" /> = true <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" /> 1 分を = <see cref="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" /> 5 分を =
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセッション ハンドラーのオートコンプリート オプションが有効になっているかどうかを設定します。</summary>
        <value>セッション ハンドラーのオートコンプリート オプションが有効である場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; ExceptionReceivedHandler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; ExceptionReceivedHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task)" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedHandler : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt;" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.ExceptionReceivedHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>例外を受け取ったときに発生します。 セッションのポンプによって発生したエラーの通知を有効にします。
            エラーが受信したときに、情報とは、呼び出しは再試行自動的にします。 </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAutoRenewDuration">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAutoRenewDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAutoRenewDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAutoRenewDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAutoRenewDuration : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxAutoRenewDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または対象のセッションのロックが自動的に更新期間を設定します。</summary>
        <value>セッションがその状態を更新する期間です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentSessions">
      <MemberSignature Language="C#" Value="public int MaxConcurrentSessions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentSessions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentSessions As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentSessions : int with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberType>Property</MemberType>
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
        <summary>取得またはユーザーが同時に処理する既存のセッションの最大数を設定します。</summary>
        <value>ユーザーが同時に処理するセッションの最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageWaitTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MessageWaitTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MessageWaitTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageWaitTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MessageWaitTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはメッセージの受信を待機する時間を設定します。</summary>
        <value>メッセージの受信を待機する時間。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>