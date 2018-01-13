<Type Name="CloudQueue" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueue">
  <TypeSignature Language="C#" Value="public class CloudQueue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudQueue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudQueue" />
  <TypeSignature Language="F#" Value="type CloudQueue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7835-101">このクラスは、Microsoft Azure Queue サービスのキューを表します。</span><span class="sxs-lookup"><span data-stu-id="f7835-101">This class represents a queue in the Microsoft Azure Queue service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Uri queueAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri queueAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Uri -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue queueAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="f7835-102">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-103"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7835-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Microsoft.WindowsAzure.Storage.StorageUri queueAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri queueAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue (queueAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="f7835-104">A<see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />プライマリとセカンダリの両方の場所のキューへの絶対 URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="f7835-104">A <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> containing the absolute URI to the queue at both the primary and secondary locations.</span></span></param>
        <param name="credentials"><span data-ttu-id="f7835-105"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-105">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-106"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7835-106">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-107"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-107">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueue (Uri queueAddress, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri queueAddress, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (queueAddress As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueue (queueAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="queueAddress" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="queueAddress"><span data-ttu-id="f7835-108">A<see cref="T:System.Uri" />キューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-108">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue.</span></span></param>
        <param name="credentials"><span data-ttu-id="f7835-109"><see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-109">A <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-110"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f7835-110">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessage">
      <MemberSignature Language="C#" Value="public virtual void AddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive = null, Nullable&lt;TimeSpan&gt; initialVisibilityDelay = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.AddMessage (message, timeToLive, initialVisibilityDelay, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-111"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-111">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="f7835-112">A <see cref="T:System.TimeSpan" /> 、キュー内にあるメッセージを許可する最大時間を指定するか、 <c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-112">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="f7835-113">A<see cref="T:System.TimeSpan" />今すぐによってメッセージが表示されなくなりますからの時間間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-113">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="f7835-114">場合<c>null</c>メッセージが表示されますすぐに、します。</span><span class="sxs-lookup"><span data-stu-id="f7835-114">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-115">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-115">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-116">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-116">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-117"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-117">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-118">キューにメッセージを追加します。</span><span class="sxs-lookup"><span data-stu-id="f7835-118">Adds a message to the queue.</span></span>
            </summary>
        <remarks><span data-ttu-id="f7835-119"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-119">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AddMessageAsync (message As CloudQueueMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-120"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-120">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-121">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-121">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-122">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-122">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-123"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-123">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-124"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-124">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-125">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-125">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-126">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-126">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-127">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-127">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-128"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-128">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, timeToLive, initialVisibilityDelay, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-129"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-129">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="f7835-130">A <see cref="T:System.TimeSpan" /> 、キュー内にあるメッセージを許可する最大時間を指定するか、 <c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-130">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="f7835-131">A<see cref="T:System.TimeSpan" />今すぐによってメッセージが表示されなくなりますからの時間間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-131">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="f7835-132">場合<c>null</c>メッセージが表示されますすぐに、します。</span><span class="sxs-lookup"><span data-stu-id="f7835-132">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-133">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-133">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-134"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-134">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-135">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-135">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-136">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-136">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-137"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-137">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="AddMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AddMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AddMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.AddMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AddMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.AddMessageAsync (message, timeToLive, initialVisibilityDelay, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-138"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-138">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="f7835-139">A <see cref="T:System.TimeSpan" /> 、キュー内にあるメッセージを許可する最大時間を指定するか、 <c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-139">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="f7835-140">A<see cref="T:System.TimeSpan" />今すぐによってメッセージが表示されなくなりますからの時間間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-140">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="f7835-141">場合<c>null</c>メッセージが表示されますすぐに、します。</span><span class="sxs-lookup"><span data-stu-id="f7835-141">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-142">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-142">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-143"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-144">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-144">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-145">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-145">Initiates an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-146">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-146">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-147"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-147">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ApproximateMessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ApproximateMessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ApproximateMessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ApproximateMessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApproximateMessageCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ApproximateMessageCount : Nullable&lt;int&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ApproximateMessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-148">キューのおおよそのメッセージ数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-148">Gets the approximate message count for the queue.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-149">おおよそのメッセージ数。</span><span class="sxs-lookup"><span data-stu-id="f7835-149">The approximate message count.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAddMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginAddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAddMessage (message As CloudQueueMessage, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginAddMessage (message, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-150"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-150">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-151"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-151">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-152">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-152">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-153">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-153">Begins an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-154"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-154">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAddMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Nullable&lt;TimeSpan&gt; timeToLive, Nullable&lt;TimeSpan&gt; initialVisibilityDelay, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAddMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToLive, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; initialVisibilityDelay, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginAddMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAddMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginAddMessage (message, timeToLive, initialVisibilityDelay, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="timeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="initialVisibilityDelay" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-155"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-155">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="timeToLive"><span data-ttu-id="f7835-156">A <see cref="T:System.TimeSpan" /> 、キュー内にあるメッセージを許可する最大時間を指定するか、 <c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-156">A <see cref="T:System.TimeSpan" /> specifying the maximum time to allow the message to be in the queue, or <c>null</c>.</span></span></param>
        <param name="initialVisibilityDelay"><span data-ttu-id="f7835-157">A<see cref="T:System.TimeSpan" />今すぐによってメッセージが表示されなくなりますからの時間間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-157">A <see cref="T:System.TimeSpan" /> specifying the interval of time from now during which the message will be invisible.</span></span>
            <span data-ttu-id="f7835-158">場合<c>null</c>メッセージが表示されますすぐに、します。</span><span class="sxs-lookup"><span data-stu-id="f7835-158">If <c>null</c> then the message will be visible immediately.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-159">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-159">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-160"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-160">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-161"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-161">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-162">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-162">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-163">キューにメッセージを追加する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-163">Begins an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-164"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-164">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClear">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginClear(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginClear (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginClear : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClear : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginClear (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-165"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-165">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-166">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-166">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-167">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-167">Begins an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-168"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-168">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginClear">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginClear(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginClear(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginClear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginClear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginClear (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-169">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-169">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-170"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-170">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-171"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-171">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-172">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-172">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-173">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-173">Begins an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-174"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-174">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreate (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-175"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-175">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-176">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-176">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-177">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-177">Begins an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-178"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-178">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreate(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreate (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-179">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-179">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-180"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-180">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-181"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-181">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-182">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-182">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-183">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-183">Begins an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-184"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-184">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreateIfNotExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-185"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-185">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-186">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-186">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-187">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-187">Begins an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-188"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-188">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-189">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-189">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginCreateIfNotExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginCreateIfNotExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-190">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-190">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-191"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-191">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-192"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-192">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-193">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-193">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-194">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-194">Begins an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-195"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-195">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-196">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-196">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDelete (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-197"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-197">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-198">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-198">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-199">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-199">Begins an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-200"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-200">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDelete(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDelete (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-201">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-201">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-202"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-202">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-203"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-203">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-204">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-204">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-205">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-205">Begins an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-206"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-206">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteIfExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-207"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-207">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-208">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-208">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-209">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-209">Begins an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-210"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-210">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteIfExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-211">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-211">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-212"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-212">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-213"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-213">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-214">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-214">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-215">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-215">Begins an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-216"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-216">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteMessage (message As CloudQueueMessage, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (message, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-217"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-217">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-218"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-218">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-219">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-219">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-220">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-220">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-221"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-221">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (string messageId, string popReceipt, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(string messageId, string popReceipt, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(System.String,System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteMessage (messageId As String, popReceipt As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : string * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : string * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (messageId, popReceipt, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-222">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-222">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-223">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-223">A string specifying the pop receipt value.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-224"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-225">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-226">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-226">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-227"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-227">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (message, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-228"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-228">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-229">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-229">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-230"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-230">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-231"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-231">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-232">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-232">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-233">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-233">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-234"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-234">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteMessage(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginDeleteMessage(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginDeleteMessage (messageId, popReceipt, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-235">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-235">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-236">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-236">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-237">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-237">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-238"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-238">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-239"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-239">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-240">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-240">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-241">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-241">Begins an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-242"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-242">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-243"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-243">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-244">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-244">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-245">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-245">Begins an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-246"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-246">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-247">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-247">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-248"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-248">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-249"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-249">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-250">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-250">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-251">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-251">Begins an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-252"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-252">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginFetchAttributes (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-253"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-253">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-254">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-254">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-255">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-255">Begins an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-256"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-256">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginFetchAttributes (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-257">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-257">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-258"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-258">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-259"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-259">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-260">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-260">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-261">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-261">Begins an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-262"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-262">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessage(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetMessage (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessage (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-263"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-263">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-264">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-264">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-265">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-265">Begins an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-266"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-266">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessage(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessage(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessage (visibilityTimeout, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-267">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-267">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-268">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-268">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-269"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-269">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-270"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-270">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-271">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-271">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-272">キューから 1 つのメッセージを取得する非同期操作を開始し、可視性、および削除のために使用可能なになるまでに、メッセージに予約する期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-272">Begins an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-273"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-273">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages (int messageCount, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages(int32 messageCount, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessages(System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetMessages (messageCount As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessages (messageCount, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-274">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-274">The number of messages to retrieve.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-275"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-275">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-276">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-276">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-277">キューからメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-277">Begins an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-278"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-278">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetMessages(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetMessages(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetMessages (messageCount, visibilityTimeout, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-279">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-279">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-280">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-280">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-281">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-281">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-282"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-282">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-283"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-283">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-284">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-284">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-285">指定された要求のオプションとその操作コンテキストを使用してキューからメッセージの指定した数を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-285">Begins an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="f7835-286">この操作は、既定の可視性のタイムアウト期間のキューで非表示として取得されたメッセージをマークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-286">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-287"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-287">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetPermissions (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-288"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-288">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-289">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-289">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-290">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-290">Begins an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-291"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-291">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginGetPermissions(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginGetPermissions (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-292">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-292">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-293"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-293">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-294"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-294">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-295">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-295">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-296">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-296">Begins an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-297"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-297">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessage(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPeekMessage (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessage : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessage (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-298"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-298">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-299">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-299">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-300">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-300">Begins an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-301"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-301">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessage(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessage(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessage (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-302">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-302">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-303"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-303">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-304"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-304">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-305">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-305">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-306">キューから 1 つのメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-306">Begins an asynchronous operation to peek a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-307"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-307">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages (int messageCount, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages(int32 messageCount, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessages(System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginPeekMessages (messageCount As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessages : int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessages (messageCount, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-308">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-308">The number of messages to peek.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-309"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-309">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-310">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-310">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-311">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-311">Begins an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-312"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-312">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPeekMessages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginPeekMessages(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginPeekMessages(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginPeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginPeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginPeekMessages (messageCount, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-313">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-313">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-314">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-314">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-315"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-315">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-316"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-316">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-317">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-317">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-318">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-318">Begins an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-319"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-319">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetMetadata (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback"><span data-ttu-id="f7835-320"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-320">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-321">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-321">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-322">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-322">Begins an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-323"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-323">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetMetadata(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetMetadata (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-324">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-324">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-325"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-325">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-326"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-326">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-327">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-327">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-328">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-328">Begins an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-329"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-329">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As QueuePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetPermissions (permissions, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-330"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-330">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-331"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-331">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-332">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-332">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-333">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-333">Begins an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-334"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-334">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginSetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginSetPermissions (permissions, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-335"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-335">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-336">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-336">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-337"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-337">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-338"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-338">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-339">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-339">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-340">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-340">Begins an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-341"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-341">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginUpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginUpdateMessage (message As CloudQueueMessage, visibilityTimeout As TimeSpan, updateFields As MessageUpdateFields, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginUpdateMessage (message, visibilityTimeout, updateFields, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-342"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-342">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-343">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-343">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-344">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-344">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-345"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-345">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-346">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-346">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-347">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-347">Begins an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-348"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-348">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginUpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.BeginUpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginUpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueue.BeginUpdateMessage (message, visibilityTimeout, updateFields, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-349"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-349">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-350">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-350">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-351">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-351">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-352">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-352">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-353"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-353">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="f7835-354"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="f7835-354">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="f7835-355">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-355">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-356">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-356">Begins an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-357"><see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-357">An <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public virtual void Clear (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Clear(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Clear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Clear : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Clear (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-358">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-358">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-359">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-359">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-360"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-360">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-361">キューからメッセージをすべてをクリアします。</span><span class="sxs-lookup"><span data-stu-id="f7835-361">Clears all messages from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ClearAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-362">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-362">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-363">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-363">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-364">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-364">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-365">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-365">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-366">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-366">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-367">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-367">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-368"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-368">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-369">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-369">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-370">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-370">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ClearAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ClearAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ClearAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ClearAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.ClearAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-371">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-371">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-372"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-372">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-373">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-373">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-374">キューからすべてのメッセージを消去する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-374">Initiates an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-375">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-375">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Create(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Create : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Create (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-376">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-376">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-377">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-377">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-378"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-378">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-379">キューを作成します。</span><span class="sxs-lookup"><span data-stu-id="f7835-379">Creates the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-380">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-380">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-381">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-381">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-382">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-382">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-383">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-383">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-384">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-384">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-385">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-385">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-386"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-386">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-387">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-387">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-388">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-388">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.CreateAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-389">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-389">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-390"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-390">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-391">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-391">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-392">キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-392">Initiates an asynchronous operation to create a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-393">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-393">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.CreateIfNotExists (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-394">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-394">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-395">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-395">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-396"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-396">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-397">既に存在しない場合は、キューを作成します。</span><span class="sxs-lookup"><span data-stu-id="f7835-397">Creates the queue if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-398"><c>true</c>いて、キューがまだ存在せず作成されたそれ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-398"><c>true</c> if the queue did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="f7835-399">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-399">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-400">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-400">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-401">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-401">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-402">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-402">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-403">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-403">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-404">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-404">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-405">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-405">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-406">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-406">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-407">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-407">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-408"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-408">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-409">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-409">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-410">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-410">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-411">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-411">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.CreateIfNotExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.CreateIfNotExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-412">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-412">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-413"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-413">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-414">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-414">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-415">既に存在しない場合は、キューを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-415">Initiates an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-416">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-416">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="f7835-417">この API は、作成または書き込みアクセス許可が必要です。</span><span class="sxs-lookup"><span data-stu-id="f7835-417">This API requires Create or Write permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Delete(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.Delete (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-418">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-418">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-419">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-419">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-420"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-420">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-421">キューを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7835-421">Deletes the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-422">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-422">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-423">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-423">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-424">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-424">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-425">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-425">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-426">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-426">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-427">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-427">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-428"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-428">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-429">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-429">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-430">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-430">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-431">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-431">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-432"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-432">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-433">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-433">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-434">キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-434">Initiates an asynchronous operation to delete a queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-435">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-435">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.DeleteIfExists (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-436">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-436">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-437">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-437">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-438"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-438">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-439">既に存在する場合は、キューを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7835-439">Deletes the queue if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-440"><c>true</c>いて、キューがまだ存在せず作成されたそれ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-440"><c>true</c> if the queue did not already exist and was created; otherwise <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-441">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-441">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-442">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-442">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-443">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-443">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-444">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-444">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-445">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-445">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-446">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-446">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-447"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-447">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-448">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-448">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-449">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-449">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.DeleteIfExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-450">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-450">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-451"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-451">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-452">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-452">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-453">既に存在する場合は、キューを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-453">Initiates an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-454">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-454">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void DeleteMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DeleteMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.DeleteMessage (message, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-455"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-455">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-456">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-456">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-457">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-457">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-458"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-458">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-459">メッセージを削除します。</span><span class="sxs-lookup"><span data-stu-id="f7835-459">Deletes a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void DeleteMessage (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteMessage(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessage(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DeleteMessage : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.DeleteMessage (messageId, popReceipt, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-460">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-460">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-461">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-461">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-462">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-462">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-463">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-463">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-464"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-464">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-465">指定したメッセージをキューから削除します。</span><span class="sxs-lookup"><span data-stu-id="f7835-465">Deletes the specified message from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteMessageAsync (message As CloudQueueMessage) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-466"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-466">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-467">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-467">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-468">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-468">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-469"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-469">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-470">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-470">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-471">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-471">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-472">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-472">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteMessageAsync (messageId As String, popReceipt As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-473">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-473">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-474">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-474">A string specifying the pop receipt value.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-475">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-475">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-476">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-476">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-477"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-477">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-478">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-478">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-479"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-479">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-480">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-480">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-481">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-481">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-482">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-482">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-483">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-483">A string specifying the pop receipt value.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-484">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-484">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-485">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-485">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-486">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-486">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (message, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-487"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-487">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-488">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-488">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-489"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-489">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-490">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-490">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-491">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-491">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-492">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-492">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-493">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-493">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-494">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-494">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-495">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-495">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-496"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-496">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-497">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-497">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-498">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-498">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteMessageAsync (string messageId, string popReceipt, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteMessageAsync(string messageId, string popReceipt, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.DeleteMessageAsync(System.String,System.String,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteMessageAsync : string * string * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.DeleteMessageAsync (messageId, popReceipt, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageId" Type="System.String" />
        <Parameter Name="popReceipt" Type="System.String" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageId"><span data-ttu-id="f7835-499">メッセージ ID を指定する文字列</span><span class="sxs-lookup"><span data-stu-id="f7835-499">A string specifying the message ID.</span></span></param>
        <param name="popReceipt"><span data-ttu-id="f7835-500">Popreceipt 値を指定する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-500">A string specifying the pop receipt value.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-501">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-501">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-502"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-502">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-503">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-503">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-504">メッセージを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-504">Initiates an asynchronous operation to delete a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-505">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-505">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodeMessage">
      <MemberSignature Language="C#" Value="public bool EncodeMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EncodeMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EncodeMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodeMessage As Boolean" />
      <MemberSignature Language="F#" Value="member this.EncodeMessage : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EncodeMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-506">取得または追加するか、メッセージを取得するときに base64 エンコードを適用するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-506">Gets or sets a value indicating whether to apply base64 encoding when adding or retrieving messages.</span></span>
            </summary>
        <value>
          <span data-ttu-id="f7835-507"><c>true</c>メッセージをエンコードするそれ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-507"><c>true</c> to encode messages; otherwise, <c>false</c>.</span></span> <span data-ttu-id="f7835-508">既定値は <c>true</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-508">The default value is <c>true</c>.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAddMessage">
      <MemberSignature Language="C#" Value="public virtual void EndAddMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAddMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndAddMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAddMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAddMessage : IAsyncResult -&gt; unit&#xA;override this.EndAddMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndAddMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-509"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-509">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-510">キューにメッセージを追加する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-510">Ends an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <remarks><span data-ttu-id="f7835-511"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />で渡されたメッセージは、popreceipt、メッセージ ID、および挿入/有効期限が表示されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-511">The <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> message passed in will be populated with the pop receipt, message ID, and the insertion/expiration time.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EndClear">
      <MemberSignature Language="C#" Value="public virtual void EndClear (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndClear(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndClear(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndClear (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndClear : IAsyncResult -&gt; unit&#xA;override this.EndClear : IAsyncResult -&gt; unit" Usage="cloudQueue.EndClear asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-512"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-512">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-513">キューからすべてのメッセージを消去する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-513">Ends an asynchronous operation to clear all messages from the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudQueue.EndCreate asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-514"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-514">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-515">キューを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-515">Ends an asynchronous operation to create a queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-516"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-516">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-517">既に存在しない場合、キューを作成する非同期操作の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-517">Returns the result of an asynchronous operation to create the queue if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-518"><c>true</c>場合、キューがまだ存在せず作成された、それ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-518"><c>true</c> if the queue did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudQueue.EndDelete asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-519"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-519">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-520">キューを削除する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-520">Ends an asynchronous operation to delete a queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-521"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-521">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-522">既に存在する場合は、キューを削除する非同期操作の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-522">Returns the result of an asynchronous operation to delete the queue if it already exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-523"><c>true</c>場合、キューがまだ存在せず作成された、それ以外の<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="f7835-523"><c>true</c> if the queue did not already exist and was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteMessage">
      <MemberSignature Language="C#" Value="public virtual void EndDeleteMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDeleteMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndDeleteMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDeleteMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteMessage : IAsyncResult -&gt; unit&#xA;override this.EndDeleteMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndDeleteMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-524"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-524">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-525">メッセージを削除する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-525">Ends an asynchronous operation to delete a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudQueue.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-526"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-526">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-527">キューの存在を確認する要求の非同期の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-527">Returns the asynchronous result of the request to check the existence of the queue.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-528"><c>true</c>キューが存在する場合。</span><span class="sxs-lookup"><span data-stu-id="f7835-528"><c>true</c> if the queue exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudQueue.EndFetchAttributes asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-529"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-529">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-530">キューの属性を取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-530">Ends an asynchronous operation to fetch a queue's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndGetMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndGetMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetMessage (asyncResult As IAsyncResult) As CloudQueueMessage" />
      <MemberSignature Language="F#" Value="abstract member EndGetMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.EndGetMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.EndGetMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-531"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-531">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-532">キューから 1 つのメッセージを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-532">Ends an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-533"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-533">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndGetMessages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndGetMessages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetMessages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetMessages (asyncResult As IAsyncResult) As IEnumerable(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member EndGetMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.EndGetMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.EndGetMessages asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-534"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-534">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-535">キューからメッセージを取得する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-535">Ends an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-536">メッセージの列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="f7835-536">An enumerable collection of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As QueuePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" Usage="cloudQueue.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-537"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-537">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-538">キューのアクセス許可の設定を取得する要求の非同期の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-538">Returns the asynchronous result of the request to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-539"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-539">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndPeekMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage EndPeekMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndPeekMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndPeekMessage (asyncResult As IAsyncResult) As CloudQueueMessage" />
      <MemberSignature Language="F#" Value="abstract member EndPeekMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.EndPeekMessage : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.EndPeekMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-540"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-540">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-541">キューから 1 つのメッセージをピークする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-541">Ends an asynchronous operation to peek a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-542"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-542">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPeekMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndPeekMessages (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; EndPeekMessages(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndPeekMessages(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndPeekMessages (asyncResult As IAsyncResult) As IEnumerable(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member EndPeekMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.EndPeekMessages : IAsyncResult -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.EndPeekMessages asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-543"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-543">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-544">キューからメッセージをピークする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-544">Ends an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-545">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-545">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudQueue.EndSetMetadata asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-546"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-546">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-547">ユーザー定義メタデータをキューに設定する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-547">Ends an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudQueue.EndSetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-548"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-548">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-549">キューのアクセス許可を設定する非同期操作の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-549">Returns the result of an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndUpdateMessage">
      <MemberSignature Language="C#" Value="public virtual void EndUpdateMessage (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndUpdateMessage(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.EndUpdateMessage(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndUpdateMessage (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndUpdateMessage : IAsyncResult -&gt; unit&#xA;override this.EndUpdateMessage : IAsyncResult -&gt; unit" Usage="cloudQueue.EndUpdateMessage asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="f7835-550"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="f7835-550">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-551">キューにメッセージを追加する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="f7835-551">Ends an asynchronous operation to add a message to the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Exists(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudQueue.Exists (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-552">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-552">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-553">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-553">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-554"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-554">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-555">キューの存在を確認します。</span><span class="sxs-lookup"><span data-stu-id="f7835-555">Checks existence of the queue.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f7835-556"><c>true</c>キューが存在する場合。</span><span class="sxs-lookup"><span data-stu-id="f7835-556"><c>true</c> if the queue exists.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-557">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-557">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-558">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-558">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-559">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-559">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-560">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-560">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-561">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-561">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-562">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-562">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-563"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-563">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-564">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-564">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-565">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-565">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ExistsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudQueue.ExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-566">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-566">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-567"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-567">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-568">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-568">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-569">キューの存在を確認する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-569">Initiates an asynchronous operation to check the existence of the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-570">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-570">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributes(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.FetchAttributes (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-571">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-571">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-572">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-572">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-573"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-573">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-574">キューの属性をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="f7835-574">Fetches the queue's attributes.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-575">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-575">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-576">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-576">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-577">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-577">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-578">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-578">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-579">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-579">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-580">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-580">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-581"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-581">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-582">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-582">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-583">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-583">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.FetchAttributesAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-584">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-584">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-585"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-585">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-586">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-586">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-587">キューの属性を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-587">Initiates an asynchronous operation to fetch the queue's attributes.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-588">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-588">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage GetMessage (Nullable&lt;TimeSpan&gt; visibilityTimeout = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage GetMessage(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessage(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.GetMessage : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.GetMessage (visibilityTimeout, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-589">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-589">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-590">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-590">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-591">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-591">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-592"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-592">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-593">既定の要求オプションを使用してキューからメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-593">Gets a message from the queue using the default request options.</span></span> <span data-ttu-id="f7835-594">この操作は、既定の可視性のタイムアウト期間のキューで非表示として取得したメッセージをマークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-594">This operation marks the retrieved message as invisible in the queue for the default visibility timeout period.</span></span> 
            </summary>
        <returns><span data-ttu-id="f7835-595"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-595">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetMessageAsync () As Task(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-596">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-596">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-597">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-597">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-598">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-598">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-599">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-599">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-600">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-600">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync (visibilityTimeout, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-601">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-601">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-602">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-602">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-603"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-603">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-604">キューから 1 つのメッセージを取得する非同期操作を開始し、可視性、および削除のために使用可能なになるまでに、メッセージに予約する期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-604">Initiates an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-605">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-605">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync (Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessageAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessageAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessageAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessageAsync (visibilityTimeout, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-606">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-606">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-607">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-607">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-608"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-608">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-609">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-609">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-610">キューから 1 つのメッセージを取得する非同期操作を開始し、可視性、および削除のために使用可能なになるまでに、メッセージに予約する期間を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-610">Initiates an asynchronous operation to get a single message from the queue, and specifies how long the message should be reserved before it becomes visible, and therefore available for deletion.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-611">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-611">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessages (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout = null, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; GetMessages(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessages(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.GetMessages : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.GetMessages (messageCount, visibilityTimeout, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-612">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-612">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-613">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-613">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-614">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-614">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-615">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-615">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-616"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-616">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-617">指定された要求のオプションとその操作コンテキストを使用してキューからメッセージの指定した数を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-617">Gets the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="f7835-618">この操作は、既定の可視性のタイムアウト期間のキューで非表示として取得されたメッセージをマークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-618">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span> 
            </summary>
        <returns><span data-ttu-id="f7835-619">メッセージの列挙可能なコレクション。</span><span class="sxs-lookup"><span data-stu-id="f7835-619">An enumerable collection of messages.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetMessagesAsync (messageCount As Integer) As Task(Of IEnumerable(Of CloudQueueMessage))" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync messageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-620">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-620">The number of messages to retrieve.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-621">キューからメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-621">Initiates an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-622">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-622">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-623">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-623">The number of messages to retrieve.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-624">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-624">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-625">キューからメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-625">Initiates an asynchronous operation to get messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-626">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-626">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, visibilityTimeout, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-627">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-627">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-628">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-628">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-629">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-629">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-630"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-630">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-631">指定された要求のオプションとその操作コンテキストを使用してキューからメッセージの指定した数を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-631">Initiates an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="f7835-632">この操作は、既定の可視性のタイムアウト期間のキューで非表示として取得されたメッセージをマークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-632">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-633">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-633">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync (int messageCount, Nullable&lt;TimeSpan&gt; visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; GetMessagesAsync(int32 messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; visibilityTimeout, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetMessagesAsync(System.Int32,System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.GetMessagesAsync : int * Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.GetMessagesAsync (messageCount, visibilityTimeout, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="visibilityTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-634">取得するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-634">The number of messages to retrieve.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-635">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-635">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-636">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-636">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-637"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-637">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-638">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-638">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-639">指定された要求のオプションとその操作コンテキストを使用してキューからメッセージの指定した数を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-639">Initiates an asynchronous operation to get the specified number of messages from the queue using the specified request options and operation context.</span></span> <span data-ttu-id="f7835-640">この操作は、既定の可視性のタイムアウト期間のキューで非表示として取得されたメッセージをマークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-640">This operation marks the retrieved messages as invisible in the queue for the default visibility timeout period.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-641">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-641">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions GetPermissions (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions GetPermissions(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissions(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&#xA;override this.GetPermissions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" Usage="cloudQueue.GetPermissions (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-642">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-642">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-643">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-643">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-644"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-644">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-645">キューのアクセス許可の設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-645">Gets the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-646"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-646">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of QueuePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-647">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-647">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-648">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-648">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-649">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-649">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-650">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-650">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-651">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-651">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-652">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-652">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-653"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-653">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-654">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-654">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-655">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-655">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt; GetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;" Usage="cloudQueue.GetPermissionsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-656">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-656">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-657"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-657">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-658">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-658">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-659">キューのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-659">Initiates an asynchronous operation to get the permissions settings for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-660">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-660">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessQueuePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy -&gt; string" Usage="cloudQueue.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="f7835-661">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-661">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-662">キューの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-662">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-663">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="f7835-663">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="f7835-664">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f7835-664">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessQueuePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy * string -&gt; string" Usage="cloudQueue.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="f7835-665">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-665">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="f7835-666">保存されているアクセス ポリシーを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-666">A string identifying a stored access policy.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-667">キューの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-667">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-668">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="f7835-668">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="f7835-669">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f7835-669">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy policy, string accessPolicyIdentifier, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudQueue.GetSharedAccessSignature (policy, accessPolicyIdentifier, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="f7835-670">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-670">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.SharedAccessQueuePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="f7835-671">保存されているアクセス ポリシーを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-671">A string identifying a stored access policy.</span></span></param>
        <param name="protocols"><span data-ttu-id="f7835-672">許可されているプロトコル (https のみ、または http と https)。</span><span class="sxs-lookup"><span data-stu-id="f7835-672">The allowed protocols (https only, or http and https).</span></span> <span data-ttu-id="f7835-673">プロトコルを制限したくない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="f7835-673">Null if you don't want to restrict protocol.</span></span></param>
        <param name="ipAddressOrRange"><span data-ttu-id="f7835-674">許可されている IP アドレスまたは IP アドレスの範囲を実行します。</span><span class="sxs-lookup"><span data-stu-id="f7835-674">The allowed IP address or IP address range.</span></span> <span data-ttu-id="f7835-675">Null を制限したくない場合は、IP アドレスに基づいています。</span><span class="sxs-lookup"><span data-stu-id="f7835-675">Null if you don't want to restrict based on IP address.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-676">キューの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="f7835-676">Returns a shared access signature for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-677">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="f7835-677">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="f7835-678">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f7835-678">The query string returned includes the leading question mark.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-679">キューのメタデータを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-679">Gets the queue's metadata.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-680"><see cref="T:System.Collections.Generic.IDictionary`2" />キューのメタデータを含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-680">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object containing the queue's metadata.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-681">キューの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-681">Gets the name of the queue.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-682">キューの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="f7835-682">A string containing the name of the queue.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessage">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage PeekMessage (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage PeekMessage(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessage(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&#xA;override this.PeekMessage : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" Usage="cloudQueue.PeekMessage (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-683">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-683">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-684">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-684">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-685"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-685">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-686">キューから 1 つのメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-686">Peeks a single message from the queue.</span></span> <span data-ttu-id="f7835-687">ピーク要求は、その可視性を変更することがなく、キューからメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-687">A peek request retrieves a message from the queue without changing its visibility.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-688"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-688">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PeekMessageAsync () As Task(Of CloudQueueMessage)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-689">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-689">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-690">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-690">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-691">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-691">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-692">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-692">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-693">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-693">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-694">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-694">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-695"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-695">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-696">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-696">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-697">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-697">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessageAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessageAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessageAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-698">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-698">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-699"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-699">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-700">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-700">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-701">キューから 1 つのメッセージを取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-701">Initiates an asynchronous operation to get a single message from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-702">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessages">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessages (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt; PeekMessages(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessages(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&#xA;override this.PeekMessages : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;" Usage="cloudQueue.PeekMessages (messageCount, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-703">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-703">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-704">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-704">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-705">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-705">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-706"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-706">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-707">指定された要求のオプションと操作のコンテキストを使用して、キューからメッセージをピークします。</span><span class="sxs-lookup"><span data-stu-id="f7835-707">Peeks a message from the queue, using the specified request options and operation context.</span></span> <span data-ttu-id="f7835-708">ピーク要求は、その可視性を変更することがなく、キューからメッセージを取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-708">A peek request retrieves a message from the queue without changing its visibility.</span></span> 
            </summary>
        <returns><span data-ttu-id="f7835-709">列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-709">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PeekMessagesAsync (messageCount As Integer) As Task(Of IEnumerable(Of CloudQueueMessage))" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync messageCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-710">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-710">The number of messages to peek.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-711">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-711">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-712">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-712">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-713">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-713">The number of messages to peek.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-714">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-714">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-715">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-715">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-716">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-716">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-717">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-717">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-718">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-718">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-719"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-719">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-720">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-720">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-721">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-721">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeekMessagesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync (int messageCount, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt; PeekMessagesAsync(int32 messageCount, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.PeekMessagesAsync(System.Int32,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;&#xA;override this.PeekMessagesAsync : int * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;" Usage="cloudQueue.PeekMessagesAsync (messageCount, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageCount" Type="System.Int32" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="messageCount"><span data-ttu-id="f7835-722">ここに表示するメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="f7835-722">The number of messages to peek.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-723">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-723">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-724"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-724">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-725">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-725">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-726">キューからメッセージをピークする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-726">Initiates an asynchronous operation to peek messages from the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-727">A<see cref="T:System.Threading.Tasks.Task`1" />型の列挙可能なコレクションであるオブジェクトを<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="f7835-727">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is an enumerable collection of type <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudQueueClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-728">取得、<see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />キュー サービスを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-728">Gets the <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> object that represents the Queue service.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-729"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-729">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadata(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.SetMetadata (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-730">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-730">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-731">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-731">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-732"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-732">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-733">キューのユーザー定義メタデータを設定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-733">Sets the queue's user-defined metadata.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f7835-734">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-734">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-735">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-735">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f7835-736">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-736">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-737">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-737">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-738">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-738">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-739">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-739">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-740"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-740">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-741">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-741">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-742">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-742">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetMetadataAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetMetadataAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options"><span data-ttu-id="f7835-743">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-743">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-744"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-744">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-745">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-745">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-746">ユーザー定義メタデータをキューに設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-746">Initiates an asynchronous operation to set user-defined metadata on the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-747">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-747">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissions(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.SetPermissions (permissions, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-748"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-748">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-749">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-749">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-750">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-750">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-751"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-751">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-752">キューのアクセス許可を設定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-752">Sets permissions for the queue.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As QueuePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-753"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-753">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-754">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-754">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-755">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-755">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-756"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-756">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-757">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-757">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-758">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-758">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-759">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-759">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-760"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-760">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-761">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-761">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-762"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-762">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-763">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-763">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-764">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-764">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions permissions, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.SetPermissionsAsync(Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.SetPermissionsAsync (permissions, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="f7835-765"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-765">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueuePermissions" /> object.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-766">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-766">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-767"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-767">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-768">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-768">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-769">キューのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-769">Initiates an asynchronous operation to set permissions for the queue.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-770">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-770">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-771">プライマリとセカンダリの両方の場所のキューの Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-771">Gets the queue URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-772">型のオブジェクト<see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" />キューの Uri は、プライマリとセカンダリの両方の場所を格納します。</span><span class="sxs-lookup"><span data-stu-id="f7835-772">An object of type <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.StorageUri" /> containing the queue's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessage">
      <MemberSignature Language="C#" Value="public virtual void UpdateMessage (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void UpdateMessage(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessage(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.UpdateMessage : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueue.UpdateMessage (message, visibilityTimeout, updateFields, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-773"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-773">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-774">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-774">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-775">フラグ<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-775">Flags of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specifies which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-776">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-776">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span> <span data-ttu-id="f7835-777">場合<c>null</c>既定のオプションは、要求に適用されます。</span><span class="sxs-lookup"><span data-stu-id="f7835-777">If <c>null</c>, default options are applied to the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-778"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-778">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-779">表示タイムアウトと、必要に応じて、メッセージの内容を更新します。</span><span class="sxs-lookup"><span data-stu-id="f7835-779">Updates the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function UpdateMessageAsync (message As CloudQueueMessage, visibilityTimeout As TimeSpan, updateFields As MessageUpdateFields) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-780"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-780">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-781">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-781">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-782">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-782">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-783">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-783">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-784">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-784">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-785"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-785">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-786">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-786">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-787">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-787">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-788">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-788">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-789">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-789">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-790">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-790">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-791"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-791">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-792">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-792">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-793">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-793">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-794">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-794">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-795"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-795">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-796">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-796">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-797">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-797">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMessageAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task UpdateMessageAsync (Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, TimeSpan visibilityTimeout, Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateMessageAsync(class Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage message, valuetype System.TimeSpan visibilityTimeout, valuetype Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields updateFields, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.UpdateMessageAsync(Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage,System.TimeSpan,Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.UpdateMessageAsync : Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage * TimeSpan * Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueue.UpdateMessageAsync (message, visibilityTimeout, updateFields, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" />
        <Parameter Name="visibilityTimeout" Type="System.TimeSpan" />
        <Parameter Name="updateFields" Type="Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="f7835-798"><see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-798">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueMessage" /> object.</span></span></param>
        <param name="visibilityTimeout"><span data-ttu-id="f7835-799">A<see cref="T:System.TimeSpan" />表示タイムアウトの間隔を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-799">A <see cref="T:System.TimeSpan" /> specifying the visibility timeout interval.</span></span></param>
        <param name="updateFields"><span data-ttu-id="f7835-800">一連の<see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" />メッセージのどの部分を更新するかを指定する値。</span><span class="sxs-lookup"><span data-stu-id="f7835-800">A set of <see cref="T:Microsoft.WindowsAzure.Storage.Queue.MessageUpdateFields" /> values that specify which parts of the message are to be updated.</span></span></param>
        <param name="options"><span data-ttu-id="f7835-801">A<see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-801">A <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="f7835-802"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-802">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f7835-803">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="f7835-803">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="f7835-804">表示タイムアウトと、必要に応じて、メッセージの内容を更新する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="f7835-804">Initiates an asynchronous operation to update the visibility timeout and optionally the content of a message.</span></span>
            </summary>
        <returns><span data-ttu-id="f7835-805">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f7835-805">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueue.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f7835-806">プライマリの場所のキューの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="f7835-806">Gets the queue URI for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="f7835-807">A<see cref="T:System.Uri" />プライマリの場所のキューへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="f7835-807">A <see cref="T:System.Uri" /> specifying the absolute URI to the queue at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>