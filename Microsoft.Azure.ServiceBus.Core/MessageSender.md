<Type Name="MessageSender" FullName="Microsoft.Azure.ServiceBus.Core.MessageSender">
  <TypeSignature Language="C#" Value="public class MessageSender : Microsoft.Azure.ServiceBus.ClientEntity, Microsoft.Azure.ServiceBus.Core.IMessageSender" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageSender extends Microsoft.Azure.ServiceBus.ClientEntity implements class Microsoft.Azure.ServiceBus.Core.IMessageSender, class Microsoft.Azure.ServiceBus.Core.ISenderClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Core.MessageSender" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageSender&#xA;Inherits ClientEntity&#xA;Implements IMessageSender" />
  <TypeSignature Language="F#" Value="type MessageSender = class&#xA;    inherit ClientEntity&#xA;    interface IMessageSender&#xA;    interface ISenderClient&#xA;    interface IClientEntity" />
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
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageSender</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
             <span data-ttu-id="7c7b8-101">キューまたはトピックにメッセージを送信、MessageSender を使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-101">The MessageSender can be used to send messages to Queues or Topics.</span></span>
             </summary>
    <remarks><span data-ttu-id="7c7b8-102">これは、AMQP プロトコルを使用して、サービスと通信します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-102">This uses AMQP protocol to communicate with service.</span></span></remarks>
    <example>
             <span data-ttu-id="7c7b8-103">キューに送信する新しい MessageSender を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-103">Create a new MessageSender to send to a Queue</span></span>
             <code>
             IMessageSender messageSender = new MessageSender(
                 namespaceConnectionString,
                 queueName)
             </code>
            
             <span data-ttu-id="7c7b8-104">メッセージを送信する</span><span class="sxs-lookup"><span data-stu-id="7c7b8-104">Send message</span></span>
             <code>
             byte[] data = GetData();
             await messageSender.SendAsync(data);
             </code></example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageSender (Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder connectionStringBuilder, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.#ctor(Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageSender : Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.Core.MessageSender" Usage="new Microsoft.Azure.ServiceBus.Core.MessageSender (connectionStringBuilder, retryPolicy)" />
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
        <param name="connectionStringBuilder"><span data-ttu-id="7c7b8-105"><see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" />エンティティ レベルの接続の詳細を持ちます。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-105">The <see cref="T:Microsoft.Azure.ServiceBus.ServiceBusConnectionStringBuilder" /> having entity level connection details.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="7c7b8-106"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-106">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="7c7b8-107">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="7c7b8-107">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-108">新しい AMQP MessageSender を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-108">Creates a new AMQP MessageSender.</span></span>
            </summary>
        <remarks><span data-ttu-id="7c7b8-109">最初の操作中に開かれると、エンティティへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-109">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageSender (string connectionString, string entityPath, Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string entityPath, class Microsoft.Azure.ServiceBus.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.#ctor(System.String,System.String,Microsoft.Azure.ServiceBus.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.Core.MessageSender : string * string * Microsoft.Azure.ServiceBus.RetryPolicy -&gt; Microsoft.Azure.ServiceBus.Core.MessageSender" Usage="new Microsoft.Azure.ServiceBus.Core.MessageSender (connectionString, entityPath, retryPolicy)" />
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
        <param name="connectionString"><span data-ttu-id="7c7b8-110">Service Bus との通信に使用される Namespace 接続文字列。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-110">Namespace connection string used to communicate with Service Bus.</span></span> <span data-ttu-id="7c7b8-111">エンティティの詳細が含まれていない必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-111">Must not contain Entity details.</span></span></param>
        <param name="entityPath"><span data-ttu-id="7c7b8-112">エンティティのパスにこのセンダが接続する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-112">The path of the entity this sender should connect to.</span></span></param>
        <param name="retryPolicy"><span data-ttu-id="7c7b8-113"><see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> Service Bus との通信に使用されます。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-113">The <see cref="T:Microsoft.Azure.ServiceBus.RetryPolicy" /> that will be used when communicating with Service Bus.</span></span> <span data-ttu-id="7c7b8-114">既定値は<see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span><span class="sxs-lookup"><span data-stu-id="7c7b8-114">Defaults to <see cref="P:Microsoft.Azure.ServiceBus.RetryPolicy.Default" /></span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-115">新しい AMQP MessageSender を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-115">Creates a new AMQP MessageSender.</span></span>
            </summary>
        <remarks><span data-ttu-id="7c7b8-116">最初の操作中に開かれると、エンティティへの新しい接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-116">Creates a new connection to the entity, which is opened during the first operation.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelScheduledMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelScheduledMessageAsync (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelScheduledMessageAsync(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.CancelScheduledMessageAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelScheduledMessageAsync (sequenceNumber As Long) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task&#xA;override this.CancelScheduledMessageAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="messageSender.CancelScheduledMessageAsync sequenceNumber" />
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
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageSender/&lt;CancelScheduledMessageAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber"><span data-ttu-id="7c7b8-117"><see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" />をキャンセルできるメッセージのです。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-117">The <see cref="P:Microsoft.Azure.ServiceBus.Message.SystemPropertiesCollection.SequenceNumber" /> of the message to be cancelled.</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-118">スケジュールしたメッセージを取り消します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-118">Cancels a message that was scheduled.</span></span>
            </summary>
        <returns><span data-ttu-id="7c7b8-119">非同期操作</span><span class="sxs-lookup"><span data-stu-id="7c7b8-119">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClosingAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task OnClosingAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task OnClosingAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.OnClosingAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnClosingAsync () As Task" />
      <MemberSignature Language="F#" Value="override this.OnClosingAsync : unit -&gt; System.Threading.Tasks.Task" Usage="messageSender.OnClosingAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageSender/&lt;OnClosingAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7c7b8-120">接続を閉じます。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-120">Closes the connection.</span></span></summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationTimeout">
      <MemberSignature Language="C#" Value="public override TimeSpan OperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan OperationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageSender.OperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Property OperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.OperationTimeout : TimeSpan with get, set" Usage="Microsoft.Azure.ServiceBus.Core.MessageSender.OperationTimeout" />
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
            <span data-ttu-id="7c7b8-121">個々 の操作がタイムアウトする期間です。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-121">Duration after which individual operations will timeout.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public virtual string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />
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
            <span data-ttu-id="7c7b8-122">MessageSender のエンティティのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-122">Gets the entity path of the MessageSender.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisteredPlugins">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt; RegisteredPlugins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.Core.MessageSender.RegisteredPlugins" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property RegisteredPlugins As IList(Of ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="member this.RegisteredPlugins : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;" Usage="Microsoft.Azure.ServiceBus.Core.MessageSender.RegisteredPlugins" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.ServiceBus.IClientEntity.RegisteredPlugins</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c7b8-123">このセンダには、現在登録されているプラグインの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-123">Gets a list of currently registered plugins for this sender.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.ServiceBus.Core.MessageSender.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      </Docs>
    </Member>
    <Member MemberName="RegisterPlugin">
      <MemberSignature Language="C#" Value="public override void RegisterPlugin (Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void RegisterPlugin(class Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin serviceBusPlugin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.RegisterPlugin(Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin)" />
      <MemberSignature Language="F#" Value="override this.RegisterPlugin : Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin -&gt; unit" Usage="messageSender.RegisterPlugin serviceBusPlugin" />
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
        <param name="serviceBusPlugin"><span data-ttu-id="7c7b8-124">登録する <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-124">The <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to register.</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-125">登録、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />このセンダーで使用します。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-125">Registers a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" /> to be used with this sender.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleMessageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ScheduleMessageAsync (Microsoft.Azure.ServiceBus.Message message, DateTimeOffset scheduleEnqueueTimeUtc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int64&gt; ScheduleMessageAsync(class Microsoft.Azure.ServiceBus.Message message, valuetype System.DateTimeOffset scheduleEnqueueTimeUtc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.ScheduleMessageAsync(Microsoft.Azure.ServiceBus.Message,System.DateTimeOffset)" />
      <MemberSignature Language="F#" Value="abstract member ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;&#xA;override this.ScheduleMessageAsync : Microsoft.Azure.ServiceBus.Message * DateTimeOffset -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="messageSender.ScheduleMessageAsync (message, scheduleEnqueueTimeUtc)" />
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
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageSender/&lt;ScheduleMessageAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" />
        <Parameter Name="scheduleEnqueueTimeUtc" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="7c7b8-126"><see cref="T:Microsoft.Azure.ServiceBus.Message" />ようにスケジュールする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-126">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> that needs to be scheduled.</span></span></param>
        <param name="scheduleEnqueueTimeUtc"><span data-ttu-id="7c7b8-127">UTC 時刻には、メッセージを処理できるようにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-127">The UTC time at which the message should be available for processing</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-128">後で Service Bus に表示するメッセージをスケジュールします。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-128">Schedules a message to appear on Service Bus at a later time.</span></span>
            </summary>
        <returns><span data-ttu-id="7c7b8-129">スケジュール設定されたメッセージのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-129">The sequence number of the message that was scheduled.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.Azure.ServiceBus.Message message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class Microsoft.Azure.ServiceBus.Message message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.SendAsync(Microsoft.Azure.ServiceBus.Message)" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : Microsoft.Azure.ServiceBus.Message -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendAsync message" />
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
        <param name="message"><span data-ttu-id="7c7b8-130"><see cref="T:Microsoft.Azure.ServiceBus.Message" />を送信するには</span><span class="sxs-lookup"><span data-stu-id="7c7b8-130">The <see cref="T:Microsoft.Azure.ServiceBus.Message" /> to send</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-131">定義に従ってエンティティにメッセージを送信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />です。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-131">Sends a message to the entity as described by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />.</span></span>
            </summary>
        <returns><span data-ttu-id="7c7b8-132">非同期操作</span><span class="sxs-lookup"><span data-stu-id="7c7b8-132">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; messageList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.ServiceBus.Message&gt; messageList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.SendAsync(System.Collections.Generic.IList{Microsoft.Azure.ServiceBus.Message})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (messageList As IList(Of Message)) As Task" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.SendAsync : System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt; -&gt; System.Threading.Tasks.Task" Usage="messageSender.SendAsync messageList" />
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
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.ServiceBus.Core.MessageSender/&lt;SendAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.ServiceBus.Message&gt;" />
      </Parameters>
      <Docs>
        <param name="messageList"><span data-ttu-id="7c7b8-133"><see cref="T:System.Collections.Generic.IList`1" />を送信するには</span><span class="sxs-lookup"><span data-stu-id="7c7b8-133">The <see cref="T:System.Collections.Generic.IList`1" /> to send</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-134">定義に従ってエンティティにメッセージの一覧を送信<see cref="P:Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />です。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-134">Sends a list of messages to the entity as described by <see cref="P:Microsoft.Azure.ServiceBus.Core.MessageSender.Path" />.</span></span>
            </summary>
        <returns><span data-ttu-id="7c7b8-135">非同期操作</span><span class="sxs-lookup"><span data-stu-id="7c7b8-135">An asynchronous operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterPlugin">
      <MemberSignature Language="C#" Value="public override void UnregisterPlugin (string serviceBusPluginName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void UnregisterPlugin(string serviceBusPluginName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Core.MessageSender.UnregisterPlugin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub UnregisterPlugin (serviceBusPluginName As String)" />
      <MemberSignature Language="F#" Value="override this.UnregisterPlugin : string -&gt; unit" Usage="messageSender.UnregisterPlugin serviceBusPluginName" />
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
        <param name="serviceBusPluginName"><span data-ttu-id="7c7b8-136">名前<see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" />登録解除する</span><span class="sxs-lookup"><span data-stu-id="7c7b8-136">The name <see cref="P:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin.Name" /> to be unregistered</span></span></param>
        <summary>
            <span data-ttu-id="7c7b8-137">登録を解除、<see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />です。</span><span class="sxs-lookup"><span data-stu-id="7c7b8-137">Unregisters a <see cref="T:Microsoft.Azure.ServiceBus.Core.ServiceBusPlugin" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>