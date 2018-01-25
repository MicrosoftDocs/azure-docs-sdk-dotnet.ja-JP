<Type Name="MessagingFactory" FullName="Microsoft.ServiceBus.Messaging.MessagingFactory">
  <TypeSignature Language="C#" Value="public abstract class MessagingFactory : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MessagingFactory extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MessagingFactory&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type MessagingFactory = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary> <span data-ttu-id="0cb35-101">MessagingFactory クラスは、送受信するようにして、キュー、トピック、またはサブスクリプションからの実行時の操作に使用するアンカー クラスです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-101">The MessagingFactory class is the anchor class used for run time operations to send and receive to and from queues, topics, or subscriptions.</span></span> </summary>
    <remarks><span data-ttu-id="0cb35-102">CreateQueueClient などの CreateXXXClient でメンバー メソッドが、名前空間に新しいエンティティを作成しないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="0cb35-102">Please note that any member method with CreateXXXClient, such as CreateQueueClient, does not create a new entity in the namespace.</span></span> <span data-ttu-id="0cb35-103">It 以前を使用して作成された既存のエンティティへのハンドルをのみを取得、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-103">It only gets handle to an existing entity created earlier using the <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</span></span> <span data-ttu-id="0cb35-104">これらのエンティティが、名前空間に存在しない場合、例外が表示されます。</span><span class="sxs-lookup"><span data-stu-id="0cb35-104">If these entities does not exist in the namespace, you will get an exception.</span></span></remarks>
    <altmember cref="T:Microsoft.ServiceBus.NamespaceManager" />
    <example>
      <code>
            <span data-ttu-id="0cb35-105">文字列のアドレス ="sb://myapp.WindowsAzure.com/"です。名前空間は、接続先のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-105">string Address = "sb://myapp.WindowsAzure.com/"; //base address of namespace you are connecting to.</span></span>
            <span data-ttu-id="0cb35-106">MessagingFactorySettings MsgFactorySettings = 新しい MessagingFactorySettings() です。操作のタイムアウトを指定 (省略可能) MessagingFactory MsgFactory = MessagingFactory.Create (アドレス、MsgFactorySettings) です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-106">MessagingFactorySettings MsgFactorySettings = new MessagingFactorySettings(); //specify operating timeout (optional) MessagingFactory MsgFactory = MessagingFactory.Create(Address, MsgFactorySettings);</span></span>
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession () As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : unit -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0cb35-107">すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションを返します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-107">Returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="0cb35-108">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-108">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSession">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSession AcceptMessageSession(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSession(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSession (serverWaitTime As TimeSpan) As MessageSession" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSession : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.AcceptMessageSession serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="0cb35-109">処理のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-109">The processing time out.</span></span></param>
        <summary><span data-ttu-id="0cb35-110">すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションを返します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-110">Returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="0cb35-111">A<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />可能にする関連メッセージのグループを単一のトランザクションで処理します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-111">A <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> that allows grouping of related messages for processing in a single transaction.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync () As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0cb35-112">すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションが非同期に返します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-112">Asynchronously returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="0cb35-113">Accept メッセージ セッションの非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-113">A task instance that represents the asynchronous operation for accept message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptMessageSessionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync (TimeSpan serverWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSession&gt; AcceptMessageSessionAsync(valuetype System.TimeSpan serverWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.AcceptMessageSessionAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcceptMessageSessionAsync (serverWaitTime As TimeSpan) As Task(Of MessageSession)" />
      <MemberSignature Language="F#" Value="member this.AcceptMessageSessionAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;" Usage="messagingFactory.AcceptMessageSessionAsync serverWaitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSession&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serverWaitTime"><span data-ttu-id="0cb35-114">処理のタイムアウトです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-114">The processing time out.</span></span></param>
        <summary><span data-ttu-id="0cb35-115">すべてのセッションが有効なサブスクリプションとサービスの名前空間のキューで利用可能なセッションが非同期に返します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-115">Asynchronously returns available sessions across all session-enabled subscriptions and queues in the service namespace.</span></span></summary>
        <returns><span data-ttu-id="0cb35-116">Accept メッセージ セッションの非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-116">A task instance that represents the asynchronous operation for accept message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0cb35-117">メッセージング ファクトリのベース アドレスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-117">Gets the base address of the messaging factory.</span></span></summary>
        <value><span data-ttu-id="0cb35-118">メッセージング ファクトリのベース アドレスを表す URI。</span><span class="sxs-lookup"><span data-stu-id="0cb35-118">A URI that represents the base address of the messaging factory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0cb35-119">新しいメッセージング ファクトリ オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-119">Creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-120">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-120">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-121">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-121">An enumeration of base addresses.</span></span></param>
        <summary><span data-ttu-id="0cb35-122">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-122">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-123">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-123">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri)) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-124">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-124">An enumeration of address.</span></span></param>
        <summary><span data-ttu-id="0cb35-125">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-125">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-126">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-126">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-127">サービスの名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-127">The base address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="0cb35-128">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-128">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-129">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-129">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-130">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-130">The namespace base address.</span></span></param>
        <summary><span data-ttu-id="0cb35-131">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-131">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-132">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-132">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-133">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-133">An enumeration of base addresses.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-134">工場出荷時設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-134">The factory settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-135">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-135">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-136">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-136">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-137">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-137">An enumeration of base addresses.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-138">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-138">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-139">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-139">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-140">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-140">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-141">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-141">An enumeration of address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-142">工場出荷時設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-142">The factory settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-143">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-143">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-144">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-144">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-145">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-145">An enumeration of address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-146">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-146">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-147">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-147">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-148">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-148">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As String, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-149">サービスの名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-149">The base address of the service namespace.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-150"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-150">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-151">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-151">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-152">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-152">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="0cb35-153">場合にスローされる<paramref name="address" />が空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-153">Thrown when <paramref name="address" /> is empty.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-154">場合にスローされる<paramref name="factorySettings" />または<paramref name="address" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-154">Thrown when <paramref name="factorySettings" /> or <paramref name="address" /> are null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-155"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0cb35-155"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-156">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-156">The base address of the namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-157">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-157">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-158">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-158">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-159">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-159">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-160"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0cb35-160"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.UriFormatException"><span data-ttu-id="0cb35-161">場合にスローされる<paramref name="address" />が空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-161">Thrown when <paramref name="address" /> is empty.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-162">場合にスローされる<paramref name="tokenProvider" />または<paramref name="address" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-162">Thrown when <paramref name="tokenProvider" /> or <paramref name="address" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (address As Uri, factorySettings As MessagingFactorySettings) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-163">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-163">The namespace base address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-164"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-164">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-165">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-165">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-166">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-166">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-167">場合にスローされる<paramref name="address" />または<paramref name="factorySettings" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-167">Thrown when <paramref name="address" /> or <paramref name="factorySettings" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-168"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0cb35-168"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory Create (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory Create(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.Create(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member Create : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.Create (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-169">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-169">The base address of the namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-170">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-170">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-171">新しい <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-171">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-172">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-172">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-173"><paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0cb35-173"><paramref name="address" /> contains a path appended to the full address of the service namespace.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-174">場合にスローされる<paramref name="tokenProvider" />または<paramref name="address" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-174">Thrown when <paramref name="tokenProvider" /> or <paramref name="address" /> are null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-175">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-175">An enumeration of base addresses.</span></span></param>
        <summary><span data-ttu-id="0cb35-176">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-176">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-177">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-177">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri)) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync addresses" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-178">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-178">An enumeration of address.</span></span></param>
        <summary><span data-ttu-id="0cb35-179">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-179">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-180">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-180">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-181">サービスの名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-181">The base address of the service namespace.</span></span></param>
        <summary><span data-ttu-id="0cb35-182">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-182">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-183">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-183">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-184">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-184">The namespace base address.</span></span></param>
        <summary><span data-ttu-id="0cb35-185">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-185">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-186">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-186">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of String), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-187">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-187">An enumeration of base addresses.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-188"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-188">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-189">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-189">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-190">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-190">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-191">ベース アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-191">An enumeration of base addresses.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-192">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-192">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-193">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-193">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-194">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-194">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (addresses As IEnumerable(Of Uri), factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-195">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-195">An enumeration of address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-196"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-196">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-197">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-197">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-198">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-198">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (addresses, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses"><span data-ttu-id="0cb35-199">アドレスの列挙です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-199">An enumeration of address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-200">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-200">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-201">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-201">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-202">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-202">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As String, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-203">サービスの名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-203">The base address of the service namespace.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-204"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-204">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-205">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-205">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-206">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-206">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : string * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-207">サービスの名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-207">The base address of the service namespace.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-208">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-208">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-209">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-209">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-210">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-210">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.Messaging.MessagingFactorySettings factorySettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.Messaging.MessagingFactorySettings)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAsync (address As Uri, factorySettings As MessagingFactorySettings) As Task(Of MessagingFactory)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.Messaging.MessagingFactorySettings -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, factorySettings)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="factorySettings" Type="Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-211">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-211">The namespace base address.</span></span></param>
        <param name="factorySettings"><span data-ttu-id="0cb35-212"><see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-212">The <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> settings.</span></span></param>
        <summary><span data-ttu-id="0cb35-213">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-213">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-214">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-214">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessagingFactory&gt; CreateAsync(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Uri * Microsoft.ServiceBus.TokenProvider -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateAsync (address, tokenProvider)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessagingFactory&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="0cb35-215">名前空間のベース アドレス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-215">The namespace base address.</span></span></param>
        <param name="tokenProvider"><span data-ttu-id="0cb35-216">トークン プロバイダー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-216">The token provider.</span></span></param>
        <summary><span data-ttu-id="0cb35-217">新しいメッセージング ファクトリ オブジェクトを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-217">Asynchronously creates a new messaging factory object.</span></span></summary>
        <returns><span data-ttu-id="0cb35-218">非同期を表すタスク インスタンスは、操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-218">A task instance that represents the asynchronous create operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubClient CreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.CreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-219">Event Hub へのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-219">The path to the Event Hub.</span></span></param>
        <summary><span data-ttu-id="0cb35-220">新たに作成<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクトの指定のパスを使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-220">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object using the specified path.</span></span></summary>
        <returns><span data-ttu-id="0cb35-221">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-221">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-222">場合にスロー<paramref name="path" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-222">Thrown if <paramref name="path" /> is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingFactory CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As MessagingFactory" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="0cb35-223">接続文字列。</span><span class="sxs-lookup"><span data-stu-id="0cb35-223">The connection string.</span></span></param>
        <summary><span data-ttu-id="0cb35-224">新たに作成<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />接続文字列からオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-224">Creates a new <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object from a connection string.</span></span></summary>
        <returns><span data-ttu-id="0cb35-225">新しく作成された<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-225">The newly created <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiver (entityPath As String) As MessageReceiver" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-226">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-226">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="0cb35-227">メッセージの受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-227">Creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="0cb35-228">新しく作成されたメッセージの受信者です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-228">The newly created message receiver.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageReceiver CreateMessageReceiver(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.CreateMessageReceiver (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-229">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-229">The path of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-230">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-230">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-231">メッセージの受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-231">Creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="0cb35-232">新しく作成されたメッセージの受信者です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-232">The newly created message receiver.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageReceiverAsync (entityPath As String) As Task(Of MessageReceiver)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-233">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-233">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="0cb35-234">非同期的にメッセージの受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-234">Asynchronously creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="0cb35-235">非同期の作成メッセージ受信側の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-235">A task instance that represents the asynchronous create message receiver operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync (string entityPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageReceiver&gt; CreateMessageReceiverAsync(string entityPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;" Usage="messagingFactory.CreateMessageReceiverAsync (entityPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-236">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-236">The path of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-237">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-237">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-238">非同期的にメッセージの受信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-238">Asynchronously creates a message receiver.</span></span></summary>
        <returns><span data-ttu-id="0cb35-239">非同期の作成メッセージ受信側の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-239">A task instance that represents the asynchronous create message receiver operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (entityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-240">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-240">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="0cb35-241">メッセージの送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-241">Creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="0cb35-242">新しく作成されたメッセージの送信者。</span><span class="sxs-lookup"><span data-stu-id="0cb35-242">The newly created message sender.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSender">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessageSender CreateMessageSender(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSender(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSender (transferDestinationEntityPath As String, viaEntityPath As String) As MessageSender" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSender : string * string -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.CreateMessageSender (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath"><span data-ttu-id="0cb35-243">転送先エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-243">The transfer destination entity path.</span></span></param>
        <param name="viaEntityPath"><span data-ttu-id="0cb35-244">エンティティを使用してパスです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-244">The via-entity path.</span></span></param>
        <summary><span data-ttu-id="0cb35-245">メッセージの送信者を作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-245">Creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="0cb35-246">作成された <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-246">The created <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (entityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath"><span data-ttu-id="0cb35-247">エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-247">The path of the entity.</span></span></param>
        <summary><span data-ttu-id="0cb35-248">メッセージの送信者を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-248">Asynchronously creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="0cb35-249">非同期の作成メッセージ送信者の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-249">A task instance that represents the asynchronous create message sender operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSenderAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync (string transferDestinationEntityPath, string viaEntityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.MessageSender&gt; CreateMessageSenderAsync(string transferDestinationEntityPath, string viaEntityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateMessageSenderAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateMessageSenderAsync (transferDestinationEntityPath As String, viaEntityPath As String) As Task(Of MessageSender)" />
      <MemberSignature Language="F#" Value="member this.CreateMessageSenderAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;" Usage="messagingFactory.CreateMessageSenderAsync (transferDestinationEntityPath, viaEntityPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.MessageSender&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityPath" Type="System.String" />
        <Parameter Name="viaEntityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityPath"><span data-ttu-id="0cb35-250">転送先エンティティのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-250">The transfer destination entity path.</span></span></param>
        <param name="viaEntityPath"><span data-ttu-id="0cb35-251">エンティティを使用してパスです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-251">The via-entity path.</span></span></param>
        <summary><span data-ttu-id="0cb35-252">メッセージの送信者を非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-252">Asynchronously creates a message sender.</span></span></summary>
        <returns><span data-ttu-id="0cb35-253">非同期の作成メッセージ送信者の操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-253">A task instance that represents the asynchronous create message sender operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueClient (path As String) As QueueClient" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-254">サービス名前空間のベース アドレスに対して、このキューのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-254">The path of the queue relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="0cb35-255">新しいキュー クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-255">Creates a new queue client.</span></span></summary>
        <returns><span data-ttu-id="0cb35-256">新しく作成されたキュー クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-256">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-257"><paramref name="path" />null または空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-257"><paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <span data-ttu-id="0cb35-258"><paramref name="path" />長さがより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-258"><paramref name="path" /> length is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="0cb35-259">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-259">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="0cb35-260">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-260">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="0cb35-261">内部エラーまたは予期しない例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-261">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="0cb35-262">ファクトリが閉じているか、中止されました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-262">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueClient CreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.CreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-263">サービス名前空間のベース アドレスに対して、このキューのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-263">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-264">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-264">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-265">新しいキュー クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-265">Creates a new queue client.</span></span></summary>
        <returns><span data-ttu-id="0cb35-266">新しく作成されたキュー クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-266">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="0cb35-267"><paramref name="path" />null または空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-267"><paramref name="path" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <span data-ttu-id="0cb35-268"><paramref name="path" />長さがより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-268"><paramref name="path" /> length is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="0cb35-269">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-269">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="0cb35-270">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-270">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="0cb35-271">内部エラーまたは予期しない例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-271">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="0cb35-272">ファクトリが閉じているか、中止されました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-272">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionClient (topicPath As String, name As String) As SubscriptionClient" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="0cb35-273">サービスの名前空間の基準としたトピック パス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-273">The topic path relative to the service namespace.</span></span></param>
        <param name="name"><span data-ttu-id="0cb35-274">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-274">The name of the subscription.</span></span></param>
        <summary><span data-ttu-id="0cb35-275">サブスクリプション クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-275">Creates a subscription client.</span></span></summary>
        <returns><span data-ttu-id="0cb35-276">新しく作成されたサブスクリプション クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-276">The newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="0cb35-277">指定された<paramref name="topicPath" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-277">The supplied <paramref name="topicPath" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="0cb35-278">長さ<paramref name="topicPath" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-278">The length of <paramref name="topicPath" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="0cb35-279">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-279">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="0cb35-280">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-280">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="0cb35-281">内部エラーまたは予期しない例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-281">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="0cb35-282">ファクトリが閉じているか、中止されました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-282">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionClient CreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.CreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="0cb35-283">サービスの名前空間の基準としたトピック パス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-283">The topic path relative to the service namespace.</span></span></param>
        <param name="name"><span data-ttu-id="0cb35-284">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-284">The name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-285">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-285">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-286">新しいサブスクリプション クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-286">Creates a new subscription client.</span></span></summary>
        <returns><span data-ttu-id="0cb35-287">新しく作成されたサブスクリプション クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-287">The newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="0cb35-288">指定された<paramref name="topicPath" />が null または空です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-288">The supplied <paramref name="topicPath" /> is null or empty.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="0cb35-289">長さ<paramref name="topicPath" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-289">The length of <paramref name="topicPath" /> is greater than <see cref="F:Microsoft.ServiceBus.Messaging.Constants.TopicNameMaximumLength" />.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="0cb35-290">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-290">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="0cb35-291">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-291">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="0cb35-292">内部エラーまたは予期しない例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-292">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="0cb35-293">ファクトリが閉じているか、中止されました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-293">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicClient">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicClient CreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.CreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="member this.CreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.CreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-294">サービス名前空間のベース アドレスの基準としたトピック パス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-294">The topic path relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="0cb35-295">新しいトピック クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-295">Creates a new topic client.</span></span></summary>
        <returns><span data-ttu-id="0cb35-296">新しく作成されたトピック クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-296">The newly created topic client.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="0cb35-297">指定された<paramref name="path" />が null です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-297">The supplied <paramref name="path" /> is null.</span></span></exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="0cb35-298">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-298">The operation times out. The timeout period is initialized through the <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" /> object.</span></span> <span data-ttu-id="0cb35-299">値を大きく必要があります<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-299">You may need to increase the value of <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> to avoid this exception if the timeout value is relatively low.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="0cb35-300">内部エラーまたは予期しない例外が発生します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-300">An internal error or unexpected exception occurs.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="0cb35-301">ファクトリが閉じているか、中止されました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-301">The factory has been closed or aborted.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.MessagingFactorySettings GetSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.GetSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSettings () As MessagingFactorySettings" />
      <MemberSignature Language="F#" Value="member this.GetSettings : unit -&gt; Microsoft.ServiceBus.Messaging.MessagingFactorySettings" Usage="messagingFactory.GetSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactorySettings</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0cb35-302">メッセージング ファクトリの設定のコピーを取得します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-302">Retrieves a copy of the settings of the messaging factory.</span></span></summary>
        <returns><span data-ttu-id="0cb35-303">メッセージングの工場出荷時設定のコピー。</span><span class="sxs-lookup"><span data-stu-id="0cb35-303">A copy of the messaging factory settings.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementConnectionResetCount">
      <MemberSignature Language="C#" Value="protected void IncrementConnectionResetCount (Uri endpoint);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void IncrementConnectionResetCount(class System.Uri endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.IncrementConnectionResetCount(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub IncrementConnectionResetCount (endpoint As Uri)" />
      <MemberSignature Language="F#" Value="member this.IncrementConnectionResetCount : Uri -&gt; unit" Usage="messagingFactory.IncrementConnectionResetCount endpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpoint" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="endpoint"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Uri&gt; NamespaceEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; NamespaceEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NamespaceEndpoints As IEnumerable(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.NamespaceEndpoints : seq&lt;Uri&gt;" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.NamespaceEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0cb35-304">名前空間のエンドポイントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-304">Gets a list of namespace endpoints.</span></span></summary>
        <value><span data-ttu-id="0cb35-305">名前空間のエンドポイントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-305">A list of namespace endpoints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="messagingFactory.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="0cb35-306">中断アクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-306">Executes the abort action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptMessageSession (receiveMode, serverWaitTime, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="0cb35-307">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-307">The message receive mode.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="0cb35-308">サーバーは、時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-308">The server wait time.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-309">操作タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-309">The operation timeout.</span></span></param>
        <summary><span data-ttu-id="0cb35-310">Accept メッセージ セッションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-310">Executes the accept message session.</span></span></summary>
        <returns><span data-ttu-id="0cb35-311">メッセージが実行されるセッションです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-311">The executed message session.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession&#xA;override this.OnAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-312">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-312">The name of the entity.</span></span></param>
        <param name="sessionId"><span data-ttu-id="0cb35-313">セッション識別子。</span><span class="sxs-lookup"><span data-stu-id="0cb35-313">The session identifier.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-314">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-314">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-315">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-315">The wait time before the operation times out.</span></span></param>
        <summary><span data-ttu-id="0cb35-316">Accept セッション受信側のアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-316">Executes the accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-317"><see cref="T:System.IAsyncResult" />非同期の参照オブジェクトがセッションの受信側のアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-317">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous accept session receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptMessageSession (Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan serverWaitTime, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptMessageSession(valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan serverWaitTime, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptMessageSession(Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptMessageSession : Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptMessageSession (receiveMode, serverWaitTime, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="serverWaitTime" Type="System.TimeSpan" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="receiveMode"><span data-ttu-id="0cb35-318">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-318">The receive mode.</span></span></param>
        <param name="serverWaitTime"><span data-ttu-id="0cb35-319">サーバーは、時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-319">The server wait time.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-320">操作タイムアウト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-320">The operation timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-321">非同期コールバック。</span><span class="sxs-lookup"><span data-stu-id="0cb35-321">The asynchronous callback.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-322">セッション状態。</span><span class="sxs-lookup"><span data-stu-id="0cb35-322">The session state.</span></span></param>
        <summary><span data-ttu-id="0cb35-323">実行開始メッセージのセッションのアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-323">Executes the begin accept message session action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-324">操作の非同期の結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-324">The asynchronous result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginAcceptSessionReceiver (string entityName, string sessionId, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginAcceptSessionReceiver(string entityName, string sessionId, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginAcceptSessionReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginAcceptSessionReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginAcceptSessionReceiver (entityName, sessionId, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="sessionId" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-325">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-325">The name of the entity.</span></span></param>
        <param name="sessionId"><span data-ttu-id="0cb35-326">セッション識別子。</span><span class="sxs-lookup"><span data-stu-id="0cb35-326">The session identifier.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-327">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-327">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-328">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-328">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-329">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="0cb35-329">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-330">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-330">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="0cb35-331">実行開始セッション受信側のアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-331">Executes the begin accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-332"><see cref="T:System.IAsyncResult" />非同期の参照オブジェクトがセッションの受信側のアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-332">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous accept session receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginClose (timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="0cb35-333">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-333">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-334">コールバック。</span><span class="sxs-lookup"><span data-stu-id="0cb35-334">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-335">状態。</span><span class="sxs-lookup"><span data-stu-id="0cb35-335">The state.</span></span></param>
        <summary><span data-ttu-id="0cb35-336">開始の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-336">Executes the begin close action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-337"><see cref="T:System.IAsyncResult" />非同期の閉じる操作を参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-337">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous close action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageReceiver (entityName, receiveMode, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-338">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-338">The name of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-339">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-339">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-340">操作の前に、待機時間がタイムアウトになりました。</span><span class="sxs-lookup"><span data-stu-id="0cb35-340">The wait time before the operation times out.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-341">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</span><span class="sxs-lookup"><span data-stu-id="0cb35-341">An <see cref="T:System.AsyncCallback" /> delegate that references the method to invoke when the operation is complete.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-342">受信操作に関する情報を格納するユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-342">A user-defined object that contains information about the receive operation.</span></span></param>
        <summary><span data-ttu-id="0cb35-343">実行開始メッセージの受信側のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-343">Executes the begin create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-344"><see cref="T:System.IAsyncResult" />非同期作成メッセージ受信側のアクションを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-344">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual IAsyncResult OnBeginCreateMessageSender (string entityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string entityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnBeginCreateMessageSender (entityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult&#xA;override this.OnBeginCreateMessageSender : string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (entityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-345">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-345">The name of the entity.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-346">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-346">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-347">コールバック。</span><span class="sxs-lookup"><span data-stu-id="0cb35-347">The callback.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-348">状態。</span><span class="sxs-lookup"><span data-stu-id="0cb35-348">The state.</span></span></param>
        <summary><span data-ttu-id="0cb35-349">実行開始メッセージの送信者のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-349">Executes the begin create message sender action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-350"><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-350">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract IAsyncResult OnBeginCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.IAsyncResult OnBeginCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnBeginCreateMessageSender(System.String,System.String,System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnBeginCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member OnBeginCreateMessageSender : string * string * TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="messagingFactory.OnBeginCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName"><span data-ttu-id="0cb35-351">転送先エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-351">The name of the transfer destination entity.</span></span></param>
        <param name="viaEntityName"><span data-ttu-id="0cb35-352">エンティティを使用して名前です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-352">The via-entity name.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-353">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-353">The timeout.</span></span></param>
        <param name="callback"><span data-ttu-id="0cb35-354">コールバック メッセージです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-354">The callback message.</span></span></param>
        <param name="state"><span data-ttu-id="0cb35-355">状態。</span><span class="sxs-lookup"><span data-stu-id="0cb35-355">The state.</span></span></param>
        <summary><span data-ttu-id="0cb35-356">実行開始メッセージの送信者のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-356">Executes the begin create message sender action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-357"><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-357">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="messagingFactory.OnClose timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="0cb35-358">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-358">The timeout.</span></span></param>
        <summary><span data-ttu-id="0cb35-359">閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-359">Executes the close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateEventHubClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.EventHubClient OnCreateEventHubClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateEventHubClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateEventHubClient (path As String) As EventHubClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient&#xA;override this.OnCreateEventHubClient : string -&gt; Microsoft.ServiceBus.Messaging.EventHubClient" Usage="messagingFactory.OnCreateEventHubClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-360">イベント ハブ クライアントのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-360">The path of the event hub client.</span></span></param>
        <summary><span data-ttu-id="0cb35-361">イベント ハブ クライアントの作成の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-361">Executes the create event hub client action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-362">作成された <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />。</span><span class="sxs-lookup"><span data-stu-id="0cb35-362">The created <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver (string entityName, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnCreateMessageReceiver(string entityName, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver&#xA;override this.OnCreateMessageReceiver : string * Microsoft.ServiceBus.Messaging.ReceiveMode * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnCreateMessageReceiver (entityName, receiveMode, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-363">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-363">The name of the entity.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-364">メッセージは受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-364">The message receive mode.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-365">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-365">The timeout.</span></span></param>
        <summary><span data-ttu-id="0cb35-366">Create メッセージ受信側のアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-366">Executes the create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-367"><see cref="T:System.IAsyncResult" />非同期作成メッセージ受信側のアクションを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-367">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message receiver action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string entityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string entityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (entityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (entityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="entityName"><span data-ttu-id="0cb35-368">エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-368">The name of the entity.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-369">タイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="0cb35-369">The timeout.</span></span></param>
        <summary><span data-ttu-id="0cb35-370">Create メッセージ送信者のアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-370">Executes the create message sender action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-371"><see cref="T:System.IAsyncResult" />非同期作成メッセージ送信者のアクションを参照するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-371">An <see cref="T:System.IAsyncResult" /> object that references the asynchronous create message sender action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateMessageSender">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender (string transferDestinationEntityName, string viaEntityName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnCreateMessageSender(string transferDestinationEntityName, string viaEntityName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateMessageSender(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateMessageSender (transferDestinationEntityName As String, viaEntityName As String, timeout As TimeSpan) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender&#xA;override this.OnCreateMessageSender : string * string * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnCreateMessageSender (transferDestinationEntityName, viaEntityName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transferDestinationEntityName" Type="System.String" />
        <Parameter Name="viaEntityName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="transferDestinationEntityName"><span data-ttu-id="0cb35-372">転送先エンティティの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-372">The name of the transfer destination entity.</span></span></param>
        <param name="viaEntityName"><span data-ttu-id="0cb35-373">エンティティを使用して名前です。</span><span class="sxs-lookup"><span data-stu-id="0cb35-373">The via-entity name.</span></span></param>
        <param name="timeout"><span data-ttu-id="0cb35-374">メッセージのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-374">The message timeout.</span></span></param>
        <summary><span data-ttu-id="0cb35-375">Create メッセージ送信者のアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-375">Executes the create message sender action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-376">実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />アクション。</span><span class="sxs-lookup"><span data-stu-id="0cb35-376">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateQueueClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient (string path, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.QueueClient OnCreateQueueClient(string path, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateQueueClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient&#xA;override this.OnCreateQueueClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.QueueClient" Usage="messagingFactory.OnCreateQueueClient (path, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-377">サービス名前空間のベース アドレスに対して、このキューのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-377">The path of the queue relative to the service namespace base address.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-378">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-378">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-379">キュー クライアントの作成の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-379">Executes the create queue client action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-380">新しく作成されたキュー クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-380">The newly created queue client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string subscriptionPath, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string subscriptionPath, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (subscriptionPath, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subscriptionPath" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="subscriptionPath"><span data-ttu-id="0cb35-381">サブスクリプションのパスです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-381">The subscription path.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-382">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-382">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-383">作成するサブスクリプション クライアントの操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-383">Executes a create subscription client action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-384">新しく作成されたサブスクリプション クライアント。</span><span class="sxs-lookup"><span data-stu-id="0cb35-384">A newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateSubscriptionClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient (string topicPath, string name, Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.SubscriptionClient OnCreateSubscriptionClient(string topicPath, string name, valuetype Microsoft.ServiceBus.Messaging.ReceiveMode receiveMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateSubscriptionClient(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiveMode)" />
      <MemberSignature Language="F#" Value="abstract member OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient&#xA;override this.OnCreateSubscriptionClient : string * string * Microsoft.ServiceBus.Messaging.ReceiveMode -&gt; Microsoft.ServiceBus.Messaging.SubscriptionClient" Usage="messagingFactory.OnCreateSubscriptionClient (topicPath, name, receiveMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="receiveMode" Type="Microsoft.ServiceBus.Messaging.ReceiveMode" />
      </Parameters>
      <Docs>
        <param name="topicPath"><span data-ttu-id="0cb35-385">サービス名前空間のベース アドレスを基準としたサブスクリプションのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-385">The path of the subscription relative to the service namespace base address.</span></span></param>
        <param name="name"><span data-ttu-id="0cb35-386">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="0cb35-386">The name of the subscription.</span></span></param>
        <param name="receiveMode"><span data-ttu-id="0cb35-387">受信モードです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-387">The receive mode.</span></span></param>
        <summary><span data-ttu-id="0cb35-388">作成するサブスクリプション クライアントの操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-388">Executes a create subscription client action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-389">新しく作成されたサブスクリプション クライアント。</span><span class="sxs-lookup"><span data-stu-id="0cb35-389">A newly created subscription client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCreateTopicClient">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient (string path);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.TopicClient OnCreateTopicClient(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnCreateTopicClient(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function OnCreateTopicClient (path As String) As TopicClient" />
      <MemberSignature Language="F#" Value="abstract member OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient&#xA;override this.OnCreateTopicClient : string -&gt; Microsoft.ServiceBus.Messaging.TopicClient" Usage="messagingFactory.OnCreateTopicClient path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="0cb35-390">サービス名前空間のベース アドレスを基準としたトピックのパス。</span><span class="sxs-lookup"><span data-stu-id="0cb35-390">The path of the topic relative to the service namespace base address.</span></span></param>
        <summary><span data-ttu-id="0cb35-391">トピック クライアントの作成の操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-391">Executes the create topic client action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-392">新しく作成されたトピック クライアントです。</span><span class="sxs-lookup"><span data-stu-id="0cb35-392">The newly created topic client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptMessageSession">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptMessageSession(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptMessageSession(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptMessageSession (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptMessageSession : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptMessageSession result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="0cb35-393">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-393">The result of the operation.</span></span></param>
        <summary><span data-ttu-id="0cb35-394">最後に実行されるメッセージのセッションのアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-394">Executes the end accept message session action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-395">実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />アクション。</span><span class="sxs-lookup"><span data-stu-id="0cb35-395">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndAcceptSessionReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSession OnEndAcceptSessionReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndAcceptSessionReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndAcceptSessionReceiver (result As IAsyncResult) As MessageSession" />
      <MemberSignature Language="F#" Value="abstract member OnEndAcceptSessionReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSession" Usage="messagingFactory.OnEndAcceptSessionReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSession</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="0cb35-396">この非同期操作のステータス情報およびユーザー定義データを格納する <see cref="T:System.IAsyncResult" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-396">An <see cref="T:System.IAsyncResult" /> object that stores state information and any user-defined data for this asynchronous operation.</span></span></param>
        <summary><span data-ttu-id="0cb35-397">最後に実行されるセッションの受信側のアクションをそのまま使用します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-397">Executes the end accept session receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-398">実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0cb35-398">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="messagingFactory.OnEndClose result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="0cb35-399">結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-399">The result.</span></span></param>
        <summary><span data-ttu-id="0cb35-400">最後の閉じる操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-400">Executes the end close action.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageReceiver">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageReceiver OnEndCreateMessageReceiver(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageReceiver(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageReceiver (result As IAsyncResult) As MessageReceiver" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageReceiver : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageReceiver" Usage="messagingFactory.OnEndCreateMessageReceiver result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="0cb35-401">結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-401">The result.</span></span></param>
        <summary><span data-ttu-id="0cb35-402">最後に実行されるメッセージの受信側のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-402">Executes the end create message receiver action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-403">実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" />アクション。</span><span class="sxs-lookup"><span data-stu-id="0cb35-403">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageReceiver" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndCreateMessageSender">
      <MemberSignature Language="C#" Value="protected abstract Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceBus.Messaging.MessageSender OnEndCreateMessageSender(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.OnEndCreateMessageSender(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnEndCreateMessageSender (result As IAsyncResult) As MessageSender" />
      <MemberSignature Language="F#" Value="abstract member OnEndCreateMessageSender : IAsyncResult -&gt; Microsoft.ServiceBus.Messaging.MessageSender" Usage="messagingFactory.OnEndCreateMessageSender result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="0cb35-404">結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-404">The result.</span></span></param>
        <summary><span data-ttu-id="0cb35-405">最後に実行されるメッセージの送信者のアクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-405">Executes the end create message sender action.</span></span></summary>
        <returns><span data-ttu-id="0cb35-406">実行された<see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" />アクション。</span><span class="sxs-lookup"><span data-stu-id="0cb35-406">The executed <see cref="T:Microsoft.ServiceBus.Messaging.MessageSender" /> action.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PairNamespaceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PairNamespaceAsync (Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PairNamespaceAsync(class Microsoft.ServiceBus.Messaging.PairedNamespaceOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.PairNamespaceAsync(Microsoft.ServiceBus.Messaging.PairedNamespaceOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function PairNamespaceAsync (options As PairedNamespaceOptions) As Task" />
      <MemberSignature Language="F#" Value="member this.PairNamespaceAsync : Microsoft.ServiceBus.Messaging.PairedNamespaceOptions -&gt; System.Threading.Tasks.Task" Usage="messagingFactory.PairNamespaceAsync options" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="0cb35-407">ペアリング オプション。</span><span class="sxs-lookup"><span data-stu-id="0cb35-407">The pairing options.</span></span></param>
        <summary><span data-ttu-id="0cb35-408">名前空間のペアを非同期的にします。</span><span class="sxs-lookup"><span data-stu-id="0cb35-408">Asynchronously pairs a namespace.</span></span></summary>
        <returns><span data-ttu-id="0cb35-409">操作の結果。</span><span class="sxs-lookup"><span data-stu-id="0cb35-409">The result of the operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public virtual int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.MessagingFactory.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="0cb35-410">取得またはメッセージの受信者が同時に要求メッセージの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="0cb35-410">Gets or sets the number of messages that the message receiver can simultaneously request.</span></span></summary>
        <value><span data-ttu-id="0cb35-411">メッセージの受信者が同時に要求メッセージの数。</span><span class="sxs-lookup"><span data-stu-id="0cb35-411">The number of messages that the message receiver can simultaneously request.</span></span></value>
        <remarks> <span data-ttu-id="0cb35-412">サーバーに次の acceptmessagesession 呼び出しで有効になります</span><span class="sxs-lookup"><span data-stu-id="0cb35-412">Takes effect on the next acceptmessagesession call to the server</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetConnection">
      <MemberSignature Language="C#" Value="public virtual void ResetConnection ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetConnection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingFactory.ResetConnection" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub ResetConnection ()" />
      <MemberSignature Language="F#" Value="abstract member ResetConnection : unit -&gt; unit&#xA;override this.ResetConnection : unit -&gt; unit" Usage="messagingFactory.ResetConnection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>