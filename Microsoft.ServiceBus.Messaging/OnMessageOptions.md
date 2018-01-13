<Type Name="OnMessageOptions" FullName="Microsoft.ServiceBus.Messaging.OnMessageOptions">
  <TypeSignature Language="C#" Value="public sealed class OnMessageOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OnMessageOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OnMessageOptions" />
  <TypeSignature Language="F#" Value="type OnMessageOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>使用してメッセージ ポンプ処理に関連付けられているオプションを提供<see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />と<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.OnMessage(System.Action{Microsoft.ServiceBus.Messaging.BrokeredMessage})" />です。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OnMessageOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.OnMessageOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.OnMessageOptions" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージ ポンプを呼び出す必要があるかどうかを示す値を取得または<see cref="M:Microsoft.ServiceBus.Messaging.QueueClient.Complete(System.Guid)" />または<see cref="M:Microsoft.ServiceBus.Messaging.SubscriptionClient.Complete(System.Guid)" />メッセージ、コールバックの処理が完了した後にします。</summary>
        <value>メッセージ操作の実行完了後に自動的に処理を完了する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenewTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan AutoRenewTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoRenewTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoRenewTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenewTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoRenewTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.AutoRenewTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または内部でロックを自動的に更新する、時間の上限を設定します。 この値が最も長いメッセージ ロック期間; より大きい必要があります。たとえば、LockDuration プロパティです。 </summary>
        <value>これを時にロックが自動的に更新最大期間です。 既定値は、5 分間この値を設定して<see cref="F:System.TimeSpan.Zero" />ロックが自動的に更新されません。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.OnMessageOptions.ExceptionReceived" />
      <MemberSignature Language="VB.NET" Value="Public Event ExceptionReceived As EventHandler(Of ExceptionReceivedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.ExceptionReceived : EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " Usage="member this.ExceptionReceived : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>例外を受け取ったときに発生します。 メッセージ ポンプによって発生したエラーの通知を有効にします。
            エラーが受信したときに、情報とは、呼び出しは再試行自動的にします。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentCalls">
      <MemberSignature Language="C#" Value="public int MaxConcurrentCalls { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.OnMessageOptions.MaxConcurrentCalls" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentCalls As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentCalls : int with get, set" Usage="Microsoft.ServiceBus.Messaging.OnMessageOptions.MaxConcurrentCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
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