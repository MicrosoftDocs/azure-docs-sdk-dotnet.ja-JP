<Type Name="MessageHandlerOptions" FullName="Microsoft.Azure.ServiceBus.MessageHandlerOptions">
  <TypeSignature Language="C#" Value="public sealed class MessageHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageHandlerOptions" />
  <TypeSignature Language="F#" Value="type MessageHandlerOptions = class" />
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
    <summary>使用してメッセージ ポンプ処理に関連付けられているオプションを提供<see cref="M:Microsoft.Azure.ServiceBus.QueueClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />と<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.RegisterMessageHandler(System.Func{Microsoft.Azure.ServiceBus.Message,System.Threading.CancellationToken,System.Threading.Tasks.Task},Microsoft.Azure.ServiceBus.MessageHandlerOptions)" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageHandlerOptions (Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; exceptionReceivedHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; exceptionReceivedHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.MessageHandlerOptions.#ctor(System.Func{Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.MessageHandlerOptions : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt; -&gt; Microsoft.Azure.ServiceBus.MessageHandlerOptions" Usage="new Microsoft.Azure.ServiceBus.MessageHandlerOptions exceptionReceivedHandler" />
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
        <summary><see cref="T:Microsoft.Azure.ServiceBus.MessageHandlerOptions" /> クラスの新しいインスタンスを初期化します。
            既定値: <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" /> = 1 <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" /> = true <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ReceiveTimeOut" /> 1 分を = <see cref="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" /> 5 分を =
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.AutoComplete" />
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
        <summary>メッセージ ポンプを呼び出す必要があるかどうかを示す値を取得または<see cref="M:Microsoft.Azure.ServiceBus.QueueClient.CompleteAsync(System.String)" />または<see cref="M:Microsoft.Azure.ServiceBus.SubscriptionClient.CompleteAsync(System.String)" />メッセージ、コールバックの処理が完了した後にします。</summary>
        <value>メッセージ操作の実行完了後に自動的に処理を完了する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceivedHandler">
      <MemberSignature Language="C#" Value="public Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs,System.Threading.Tasks.Task&gt; ExceptionReceivedHandler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, class System.Threading.Tasks.Task&gt; ExceptionReceivedHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionReceivedHandler As Func(Of ExceptionReceivedEventArgs, Task)" />
      <MemberSignature Language="F#" Value="member this.ExceptionReceivedHandler : Func&lt;Microsoft.Azure.ServiceBus.ExceptionReceivedEventArgs, System.Threading.Tasks.Task&gt;" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.ExceptionReceivedHandler" />
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
        <summary>例外を受け取ったときに発生します。 メッセージ ポンプによって発生したエラーの通知を有効にします。
            エラーが受信したときに、情報とは、呼び出しは再試行自動的にします。 </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAutoRenewDuration">
      <MemberSignature Language="C#" Value="public TimeSpan MaxAutoRenewDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxAutoRenewDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAutoRenewDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxAutoRenewDuration : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxAutoRenewDuration" />
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
        <summary>取得または内部でロックを自動的に更新する、時間の上限を設定します。 この値が最も長いメッセージ ロック期間; より大きい必要があります。たとえば、LockDuration プロパティです。 </summary>
        <value>これを時にロックが自動的に更新最大期間です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public int MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int with get, set" Usage="Microsoft.Azure.ServiceBus.MessageHandlerOptions.MaxConcurrentCalls" />
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
        <summary>取得またはメッセージ ポンプを開始する必要がありますのコールバックへの同時呼び出しの最大数を設定します。</summary>
        <value>コールバックに同時呼び出しの最大数。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>