<Type Name="SessionHandlerOptions" FullName="Microsoft.ServiceBus.Messaging.SessionHandlerOptions">
  <TypeSignature Language="C#" Value="public class SessionHandlerOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SessionHandlerOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SessionHandlerOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class SessionHandlerOptions" />
  <TypeSignature Language="F#" Value="type SessionHandlerOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="178d0-101">セッション ハンドラーのオプションを表します。</span><span class="sxs-lookup"><span data-stu-id="178d0-101">Represents the options for the session handler.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SessionHandlerOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="178d0-102"><see cref="T:Microsoft.ServiceBus.Messaging.SessionHandlerOptions" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="178d0-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.SessionHandlerOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoComplete">
      <MemberSignature Language="C#" Value="public bool AutoComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoComplete As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoComplete : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="178d0-103">取得またはセッション ハンドラーのオートコンプリート オプションが有効になっているかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="178d0-103">Gets or sets whether the autocomplete option of the session handler is enabled.</span></span></summary>
        <value><span data-ttu-id="178d0-104">セッション ハンドラーのオートコンプリート オプションが有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="178d0-104">true if the autocomplete option of the session handler is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenewTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan AutoRenewTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan AutoRenewTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoRenewTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoRenewTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.AutoRenewTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.AutoRenewTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="178d0-105">セッションの前に必要な時間を取得または設定の状態を更新します。</span><span class="sxs-lookup"><span data-stu-id="178d0-105">Gets or sets the time needed before the session renew its state.</span></span></summary>
        <value><span data-ttu-id="178d0-106">時間に必要なセッションの前に更新の状態。</span><span class="sxs-lookup"><span data-stu-id="178d0-106">The time needed before the session renew its state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionReceived">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.ExceptionReceivedEventArgs&gt; ExceptionReceived" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.ExceptionReceived" />
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
        <summary><span data-ttu-id="178d0-107">例外は、セッションの処理中に受信したときに発生します。</span><span class="sxs-lookup"><span data-stu-id="178d0-107">Occurs when an exception was received during session handling.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentSessions">
      <MemberSignature Language="C#" Value="public int MaxConcurrentSessions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConcurrentSessions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentSessions As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentSessions : int with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MaxConcurrentSessions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="178d0-108">取得または既存のセッションの最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="178d0-108">Gets or sets the maximum number of existing sessions.</span></span></summary>
        <value><span data-ttu-id="178d0-109">既存のセッションの最大数。</span><span class="sxs-lookup"><span data-stu-id="178d0-109">The maximum number of existing sessions.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageWaitTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MessageWaitTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MessageWaitTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageWaitTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MessageWaitTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.SessionHandlerOptions.MessageWaitTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="178d0-110">取得またはメッセージの待機中の有効期限が切れる前に必要な時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="178d0-110">Gets or sets the time needed before the message waiting expires.</span></span></summary>
        <value><span data-ttu-id="178d0-111">メッセージの待機中の有効期限が切れる前に必要な時間。</span><span class="sxs-lookup"><span data-stu-id="178d0-111">The time needed before the message waiting expires.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>