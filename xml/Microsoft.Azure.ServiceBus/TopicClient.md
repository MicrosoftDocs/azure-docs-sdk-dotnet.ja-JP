<Type Name="TopicClient" FullName="Microsoft.Azure.ServiceBus.TopicClient">
  <TypeSignature Language="C#" Value="public class TopicClient : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TopicClient extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity, class Microsoft.Azure.ServiceBus.ITopicClient" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.TopicClient" />
  <TypeSignature Language="VB.NET" Value="Public Class TopicClient&#xA;Inherits ClientEntity&#xA;Implements ITopicClient" />
  <TypeSignature Language="F#" Value="type TopicClient = class&#xA;    inherit ClientEntity&#xA;    interface ITopicClient&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.ITopicClient</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="1075b-101">TopicClient を Service Bus トピックのすべての基本的な通信に使用できます。</span><span class="sxs-lookup"><span data-stu-id="1075b-101">TopicClient can be used for all basic interactions with a Service Bus topic.</span></span>
             </summary>
    <remarks><span data-ttu-id="1075b-102">Servicebus と通信するため、AMQP プロトコルを使用します。</span><span class="sxs-lookup"><span data-stu-id="1075b-102">It uses AMQP protocol for communicating with servicebus.</span></span></remarks>
    <example>
             <span data-ttu-id="1075b-103">新しい TopicClient を作成します。</span><span class="sxs-lookup"><span data-stu-id="1075b-103">Create a new TopicClient</span></span>
             <code>
             ITopicClient topicClient = new TopicClient(
                 namespaceConnectionString,
                 topicName,
                 RetryExponential);
             </code>
            
             <span data-ttu-id="1075b-104">トピックにメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="1075b-104">Send a message to the topic:</span></span>
             <code>
             byte[] data = GetData();
             await topicClient.SendAsync(data);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (connectionStringBuilder, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionStringBuilder" Type="Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionStringBuilder">
          <span data-ttu-id="1075b-105"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />名前空間とトピックの情報を持ちます。</span><span class="sxs-lookup"><span data-stu-id="1075b-105"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having namespace and topic information.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="1075b-106">ポリシーのトピックの操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="1075b-106">Retry policy for topic operations.</span></span> <span data-ttu-id="1075b-107">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="1075b-107">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="1075b-108">新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.TopicClient" />トピックに対して操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="1075b-108">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.TopicClient" /> to perform operations on a topic.</span></span>
            </summary>
        <remarks><span data-ttu-id="1075b-109">最初の送信操作中に開かれるトピックへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="1075b-109">Creates a new connection to the topic, which is opened during the first send operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : string * string * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (connectionString, entityPath, retryPolicy)" />
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
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="1075b-110">Namespace 接続文字列です。</span><span class="sxs-lookup"><span data-stu-id="1075b-110">Namespace connection string.</span></span> <span data-ttu-id="1075b-111">トピックの情報が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="1075b-111">Must not contain topic information.</span></span></param>
        <param name="entityPath"><span data-ttu-id="1075b-112">トピックへのパス</span><span class="sxs-lookup"><span data-stu-id="1075b-112">Path to the topic</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="1075b-113">ポリシーのトピックの操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="1075b-113">Retry policy for topic operations.</span></span> <span data-ttu-id="1075b-114">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="1075b-114">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="1075b-115">新しいインスタンスを作成<see cref="T:Microsoft.Azure.ServiceBus.TopicClient" />トピックに対して操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="1075b-115">Instantiates a new <see cref="T:Microsoft.Azure.ServiceBus.TopicClient" /> to perform operations on a topic.</span></span>
            </summary>
        <remarks><span data-ttu-id="1075b-116">最初の送信操作中に開かれるトピックへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="1075b-116">Creates a new connection to the topic, which is opened during the first send operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TopicClient (string endpoint, string entityPath, Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, Microsoft.Azure.ServiceBus.TransportType transportType = Microsoft.Azure.ServiceBus.TransportType.Amqp, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endpoint, string entityPath, class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider tokenProvider, valuetype Microsoft.Azure.ServiceBus.TransportType transportType, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.ITokenProvider,Microsoft.Azure.ServiceBus.TransportType,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.TopicClient : string * string * Microsoft.Azure.ServiceBus.Primitives.ITokenProvider * Microsoft.Azure.ServiceBus.TransportType * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.TopicClient" Usage="new Microsoft.Azure.ServiceBus.TopicClient (endpoint, entityPath, tokenProvider, transportType, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
        <Parameter Name="transportType" Type="Microsoft.Azure.ServiceBus.TransportType" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.ServiceBus.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="endpoint"><span data-ttu-id="1075b-117">Service Bus の完全修飾ドメイン名。</span><span class="sxs-lookup"><span data-stu-id="1075b-117">Fully qualified domain name for Service Bus.</span></span> <span data-ttu-id="1075b-118">最も可能性の高い、{yournamespace}. servicebus.windows .net</span><span class="sxs-lookup"><span data-stu-id="1075b-118">Most likely, {yournamespace}.servicebus.windows.net</span></span></param>
        <param name="entityPath"><span data-ttu-id="1075b-119">トピック パスです。</span><span class="sxs-lookup"><span data-stu-id="1075b-119">Topic path.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="1075b-120">認証のセキュリティ トークンを生成するトークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="1075b-120">Token provider which will generate security tokens for authorization.</span></span></param>
        <param name="transportType"><span data-ttu-id="1075b-121">トランスポートの種類。</span><span class="sxs-lookup"><span data-stu-id="1075b-121">Transport type.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="1075b-122">ポリシーのトピックの操作を再試行してください。</span><span class="sxs-lookup"><span data-stu-id="1075b-122">Retry policy for topic operations.</span></span> <span data-ttu-id="1075b-123">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="1075b-123">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="1075b-124">トピックを指定されたエンドポイント、エンティティのパス、およびトークン プロバイダーを使用してクライアントの新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="1075b-124">Creates a new instance of the Topic client using the specified endpoint, entity path, and token provider.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="topicClient.CancelScheduledMessageAsync sequenceNumber" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.CancelScheduledMessageAsync(System.Int64)</InterfaceMember>
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
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="1075b-125"><see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />をキャンセルできるメッセージのです。</span><span class="sxs-lookup"><span data-stu-id="1075b-125">The <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> of the message to be cancelled.</span></span></param>
        <summary>
            <span data-ttu-id="1075b-126">スケジュールしたメッセージを取り消します。</span><span class="sxs-lookup"><span data-stu-id="1075b-126">Cancels a message that was scheduled.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="topicClient.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.TopicClient/&lt;OnClosingAsync&gt;d__34))</AttributeName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.TopicClient.OperationTimeout" />
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
            <span data-ttu-id="1075b-127">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="1075b-127">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.TopicClient.Path" />
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
            <span data-ttu-id="1075b-128">トピックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1075b-128">Gets the name of the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.TopicClient.RegisteredPlugins" />
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
            <span data-ttu-id="1075b-129">この TopicClient 現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1075b-129">Gets a list of currently registered plugins for this TopicClient.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="topicClient.RegisterPlugin serviceBusPlugin" />
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
        <param name="serviceBusPlugin"><span data-ttu-id="1075b-130"><see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />を登録するには</span><span class="sxs-lookup"><span data-stu-id="1075b-130">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register</span></span></param>
        <summary>
            <span data-ttu-id="1075b-131">登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このトピックのクライアントで使用します。</span><span class="sxs-lookup"><span data-stu-id="1075b-131">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this topic client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.Azure.ServiceBus.Message message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.Azure.ServiceBus.Message message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="topicClient.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1075b-132"><see cref="T:Microsoft.Azure.ServiceBus.Message" />ようにスケジュールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1075b-132">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that needs to be scheduled.</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="1075b-133">UTC 時刻には、メッセージを処理できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="1075b-133">The UTC time at which the message should be available for processing.</span></span></param>
        <summary>
            <span data-ttu-id="1075b-134">後で Service Bus に表示するメッセージをスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="1075b-134">Schedules a message to appear on Service Bus at a later time.</span></span>
            </summary>
        <returns><span data-ttu-id="1075b-135">スケジュール設定されたメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="1075b-135">The sequence number of the message that was scheduled.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.SendAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync message" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(Microsoft.Azure.ServiceBus.Message)</InterfaceMember>
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
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="1075b-136"><see cref="T:Microsoft.Azure.ServiceBus.Message" /></span><span class="sxs-lookup"><span data-stu-id="1075b-136">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /></span></span></param>
        <summary>
            <span data-ttu-id="1075b-137">Service Bus にメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="1075b-137">Sends a message to Service Bus.</span></span>
            </summary>
        <returns><span data-ttu-id="1075b-138">非同期操作</span><span class="sxs-lookup"><span data-stu-id="1075b-138">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; messageList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; messageList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (messageList As IList(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="topicClient.SendAsync messageList" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Core.ISenderClient.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})</InterfaceMember>
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
        <Parameter Name="messageList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messageList"><span data-ttu-id="1075b-139">メッセージの一覧</span><span class="sxs-lookup"><span data-stu-id="1075b-139">The list of messages</span></span></param>
        <summary>
            <span data-ttu-id="1075b-140">Service Bus にメッセージの一覧を送信します。</span><span class="sxs-lookup"><span data-stu-id="1075b-140">Sends a list of messages to Service Bus.</span></span>
            </summary>
        <returns><span data-ttu-id="1075b-141">非同期操作</span><span class="sxs-lookup"><span data-stu-id="1075b-141">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.TopicClient.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string" Usage="Microsoft.Azure.ServiceBus.TopicClient.TopicName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.ITopicClient.TopicName</InterfaceMember>
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
            <span data-ttu-id="1075b-142">トピックの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="1075b-142">Gets the name of the topic.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.TopicClient.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="topicClient.UnregisterPlugin serviceBusPluginName" />
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
        <param name="serviceBusPluginName"><span data-ttu-id="1075b-143">名前<see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />登録解除する</span><span class="sxs-lookup"><span data-stu-id="1075b-143">The name <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> to be unregistered</span></span></param>
        <summary>
            <span data-ttu-id="1075b-144">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="1075b-144">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>