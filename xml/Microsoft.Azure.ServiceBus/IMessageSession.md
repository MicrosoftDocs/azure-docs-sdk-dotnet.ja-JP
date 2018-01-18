<Type Name="IMessageSession" FullName="Microsoft.Azure.ServiceBus.IMessageSession">
  <TypeSignature Language="C#" Value="public interface IMessageSession : Microsoft.Azure.ServiceBus.Core.IMessageReceiver" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMessageSession implements class Microsoft.Azure.ServiceBus.Core.IMessageReceiver, class Microsoft.Azure.ServiceBus.Core.IReceiverClient, class Microsoft.Azure.ServiceBus.IClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.IMessageSession" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMessageSession&#xA;Implements IMessageReceiver" />
  <TypeSignature Language="F#" Value="type IMessageSession = interface&#xA;    interface IMessageReceiver&#xA;    interface IReceiverClient&#xA;    interface IClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Core.IMessageReceiver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d475f-101">セッション オブジェクトを表します。</span><span class="sxs-lookup"><span data-stu-id="d475f-101">Describes a Session object.</span></span> <span data-ttu-id="d475f-102">セッションでの操作を実行する IMessageSession を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d475f-102">IMessageSession can be used to perform operations on sessions.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="d475f-103">サービス バス セッション、AMQP 1.0 プロトコルでは"Groups"とも呼ばれますとは、一連の関連メッセージをバインド解除済みです。</span><span class="sxs-lookup"><span data-stu-id="d475f-103">Service Bus Sessions, also called 'Groups' in the AMQP 1.0 protocol, are unbounded sequences of related messages.</span></span> <span data-ttu-id="d475f-104">ServiceBus では、セッションでメッセージの順序を保証します。</span><span class="sxs-lookup"><span data-stu-id="d475f-104">ServiceBus guarantees ordering of messages in a session.</span></span>
            </para>
      <para>
            <span data-ttu-id="d475f-105">センダは、セッションを作成することができますを設定してトピックまたはキューにメッセージを送信するときに、<see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" />メッセージのプロパティをいくつかのアプリケーションには、一意識別子を定義します。</span><span class="sxs-lookup"><span data-stu-id="d475f-105">Any sender can create a session when submitting messages into a Topic or Queue by setting the <see cref="P:Microsoft.Azure.ServiceBus.Message.SessionId" /> property on Message to some application defined unique identifier.</span></span> <span data-ttu-id="d475f-106">AMQP 1.0 プロトコル レベルでは、この値は、グループ id プロパティにマップされます。</span><span class="sxs-lookup"><span data-stu-id="d475f-106">At the AMQP 1.0 protocol level, this value maps to the group-id property.</span></span>
            </para>
      <para>
            <span data-ttu-id="d475f-107">セッションは、キューまたはトピックのサブスクリプションで、セッションのセッション Id で、少なくとも 1 つのメッセージが表示される時に存在するようになります。</span><span class="sxs-lookup"><span data-stu-id="d475f-107">Sessions come into existence when there is at least one message with the session's SessionId in the Queue or Topic subscription.</span></span>
            <span data-ttu-id="d475f-108">セッションが存在する場合は定義されている時点、またはセッションの有効期限が切れる場合または非表示のジェスチャです。</span><span class="sxs-lookup"><span data-stu-id="d475f-108">Once a Session exists, there is no defined moment or gesture for when the session expires or disappears.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; GetStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; GetStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetStateAsync () As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member GetStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iMessageSession.GetStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d475f-109">セッション状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="d475f-109">Gets the session state.</span></span>
            </summary>
        <returns><span data-ttu-id="d475f-110">バイト配列としてセッション状態。</span><span class="sxs-lookup"><span data-stu-id="d475f-110">The session state as byte array.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.Azure.ServiceBus.IMessageSession.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d475f-111">時刻を取得するセッションで識別される<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />はこのクライアント用になるまでにロックします。</span><span class="sxs-lookup"><span data-stu-id="d475f-111">Gets the time that the session identified by <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" /> is locked until for this client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewSessionLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewSessionLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewSessionLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.RenewSessionLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewSessionLockAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member RenewSessionLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.RenewSessionLockAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d475f-112">指定されたセッションで、ロックの更新、<see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />です。</span><span class="sxs-lookup"><span data-stu-id="d475f-112">Renews the lock on the session specified by the <see cref="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />.</span></span> <span data-ttu-id="d475f-113">ロックは、エンティティに指定された設定に基づいて更新されます。</span><span class="sxs-lookup"><span data-stu-id="d475f-113">The lock will be renewed based on the setting specified on the entity.</span></span>
            </summary>
        <returns><span data-ttu-id="d475f-114">非同期操作</span><span class="sxs-lookup"><span data-stu-id="d475f-114">The asynchronous operation</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="d475f-115">セッションを承諾すると、セッションによってロックされてクライアントのインスタンスの指定された期間、サービス キュー/サブスクリプションの作成中に。</span><span class="sxs-lookup"><span data-stu-id="d475f-115">When you accept a session, the session is locked for this client instance by the service for a duration as specified during the Queue/Subscription creation.</span></span>
            <span data-ttu-id="d475f-116">セッションの処理は、この期間を超える必要がある場合、セッション ロックを更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d475f-116">If processing of the session requires longer than this duration, the session-lock needs to be renewed.</span></span> <span data-ttu-id="d475f-117">各更新のエンティティに設定 LockDuration によってセッションがロックされている時間にリセットされます。</span><span class="sxs-lookup"><span data-stu-id="d475f-117">For each renewal, it resets the time the session is locked by the LockDuration set on the Entity.</span></span>
            </para>
          <para>
            <span data-ttu-id="d475f-118">セッションの更新は、同様のセッションですべてのメッセージを更新します。</span><span class="sxs-lookup"><span data-stu-id="d475f-118">Renewal of session renews all the messages in the session as well.</span></span> <span data-ttu-id="d475f-119">各メッセージを更新することがない必要があります。</span><span class="sxs-lookup"><span data-stu-id="d475f-119">Each individual message need not be renewed.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string" Usage="Microsoft.Azure.ServiceBus.IMessageSession.SessionId" />
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
            <span data-ttu-id="d475f-120">セッション Id を取得します。</span><span class="sxs-lookup"><span data-stu-id="d475f-120">Gets the SessionId.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SetStateAsync (byte[] sessionState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetStateAsync(unsigned int8[] sessionState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.IMessageSession.SetStateAsync(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function SetStateAsync (sessionState As Byte()) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetStateAsync : byte[] -&gt; System.Threading.Tasks.Task" Usage="iMessageSession.SetStateAsync sessionState" />
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
        <Parameter Name="sessionState" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="sessionState"><span data-ttu-id="d475f-121">セッション状態のバイト配列</span><span class="sxs-lookup"><span data-stu-id="d475f-121">A byte array of session state</span></span></param>
        <summary>
            <span data-ttu-id="d475f-122">使用して後で取得できるセッションでのカスタム状態を設定します。<see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></span><span class="sxs-lookup"><span data-stu-id="d475f-122">Set a custom state on the session which can be later retrieved using <see cref="M:Microsoft.Azure.ServiceBus.IMessageSession.GetStateAsync" /></span></span></summary>
        <returns>To be added.</returns>
        <remarks><span data-ttu-id="d475f-123">空の状態を設定していない場合、この状態は Service Bus に永久に格納されます。</span><span class="sxs-lookup"><span data-stu-id="d475f-123">This state is stored on Service Bus forever unless you set an empty state on it.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>