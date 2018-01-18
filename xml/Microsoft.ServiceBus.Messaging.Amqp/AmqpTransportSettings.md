<Type Name="AmqpTransportSettings" FullName="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings">
  <TypeSignature Language="C#" Value="public sealed class AmqpTransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AmqpTransportSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AmqpTransportSettings" />
  <TypeSignature Language="F#" Value="type AmqpTransportSettings = class&#xA;    interface ITransportSettings&#xA;    interface IServiceBusSecuritySettings" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="76cc3-101">メッセージ キューのプロトコルの高度なトランスポート設定を表します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-101">Represents the Advanced Message Queuing Protocol transport settings.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AmqpTransportSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="76cc3-102"><see cref="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="76cc3-103">取得またはトランスポートに関連付けられているバッチのフラッシュ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-103">Gets or sets the batch flush interval associated with the transport.</span></span></summary>
        <value><span data-ttu-id="76cc3-104">トランスポートに関連付けられているバッチ フラッシュ間隔。</span><span class="sxs-lookup"><span data-stu-id="76cc3-104">The batch flush interval associated with the transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="amqpTransportSettings.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ITransportSettings.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="76cc3-105">現在のインスタンスのコピーである新しいオブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-105">Creates a new object that is a copy of the current instance.</span></span></summary>
        <returns><span data-ttu-id="76cc3-106">このインスタンスのコピーである新しいオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="76cc3-106">A new object that is a copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableLinkRedirect">
      <MemberSignature Language="C#" Value="public bool EnableLinkRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableLinkRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableLinkRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableLinkRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableLinkRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableLinkRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="76cc3-107">取得またはこのトランスポートはサーバーのバックエンドにリダイレクトする準備ができているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-107">Gets or sets a value indicating whether this transport is ready to be redirected to the server backend.</span></span> </summary>
        <value> <span data-ttu-id="76cc3-108">このトランスポートは、サーバーで許可されるリダイレクトに参加する必要がある場合は true。</span><span class="sxs-lookup"><span data-stu-id="76cc3-108">true if this transport wants to participate in redirect allowed by the server.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="76cc3-109">取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-109">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="76cc3-110">クライアントがアクセスする場合は true。<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />を使用して<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="76cc3-110">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxFrameSize">
      <MemberSignature Language="C#" Value="public int MaxFrameSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxFrameSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.MaxFrameSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxFrameSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxFrameSize : int with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.MaxFrameSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="76cc3-111">取得または最大フレーム サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-111">Gets or sets the maximum frame size.</span></span></summary>
        <value><span data-ttu-id="76cc3-112">最大フレーム サイズです。</span><span class="sxs-lookup"><span data-stu-id="76cc3-112">The maximum frame size.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseSslStreamSecurity">
      <MemberSignature Language="C#" Value="public bool UseSslStreamSecurity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseSslStreamSecurity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.UseSslStreamSecurity" />
      <MemberSignature Language="VB.NET" Value="Public Property UseSslStreamSecurity As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseSslStreamSecurity : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.UseSslStreamSecurity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="76cc3-113">SSL ストリームがカスタム バインド要素を使用するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="76cc3-113">Gets a value that indicates whether the SSL stream uses a custom binding element.</span></span></summary>
        <value><span data-ttu-id="76cc3-114">SSL ストリームで使用できるカスタム バインド要素である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="76cc3-114">true if the SSL stream uses a custom binding element; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>