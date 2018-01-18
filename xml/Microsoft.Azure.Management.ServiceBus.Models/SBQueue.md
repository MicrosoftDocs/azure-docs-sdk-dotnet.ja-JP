<Type Name="SBQueue" FullName="Microsoft.Azure.Management.ServiceBus.Models.SBQueue">
  <TypeSignature Language="C#" Value="public class SBQueue : Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SBQueue extends Microsoft.Azure.Management.ServiceBus.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
  <TypeSignature Language="VB.NET" Value="Public Class SBQueue&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SBQueue = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceBus.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e815f-101">キュー リソースの説明です。</span><span class="sxs-lookup"><span data-stu-id="e815f-101">Description of queue Resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e815f-102">SBQueue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e815f-102">Initializes a new instance of the SBQueue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SBQueue (string id = null, string name = null, string type = null, Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails = null, Nullable&lt;DateTime&gt; createdAt = null, Nullable&lt;DateTime&gt; updatedAt = null, Nullable&lt;DateTime&gt; accessedAt = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;long&gt; messageCount = null, Nullable&lt;TimeSpan&gt; lockDuration = null, Nullable&lt;int&gt; maxSizeInMegabytes = null, Nullable&lt;bool&gt; requiresDuplicateDetection = null, Nullable&lt;bool&gt; requiresSession = null, Nullable&lt;TimeSpan&gt; defaultMessageTimeToLive = null, Nullable&lt;bool&gt; deadLetteringOnMessageExpiration = null, Nullable&lt;TimeSpan&gt; duplicateDetectionHistoryTimeWindow = null, Nullable&lt;int&gt; maxDeliveryCount = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status = null, Nullable&lt;TimeSpan&gt; autoDeleteOnIdle = null, Nullable&lt;bool&gt; enablePartitioning = null, Nullable&lt;bool&gt; enableExpress = null, string forwardTo = null, string forwardDeadLetteredMessagesTo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails countDetails, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; updatedAt, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; accessedAt, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;int64&gt; messageCount, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; lockDuration, valuetype System.Nullable`1&lt;int32&gt; maxSizeInMegabytes, valuetype System.Nullable`1&lt;bool&gt; requiresDuplicateDetection, valuetype System.Nullable`1&lt;bool&gt; requiresSession, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; defaultMessageTimeToLive, valuetype System.Nullable`1&lt;bool&gt; deadLetteringOnMessageExpiration, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duplicateDetectionHistoryTimeWindow, valuetype System.Nullable`1&lt;int32&gt; maxDeliveryCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; status, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; autoDeleteOnIdle, valuetype System.Nullable`1&lt;bool&gt; enablePartitioning, valuetype System.Nullable`1&lt;bool&gt; enableExpress, string forwardTo, string forwardDeadLetteredMessagesTo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.TimeSpan},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EntityStatus},System.Nullable{System.TimeSpan},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional countDetails As MessageCountDetails = null, Optional createdAt As Nullable(Of DateTime) = null, Optional updatedAt As Nullable(Of DateTime) = null, Optional accessedAt As Nullable(Of DateTime) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional messageCount As Nullable(Of Long) = null, Optional lockDuration As Nullable(Of TimeSpan) = null, Optional maxSizeInMegabytes As Nullable(Of Integer) = null, Optional requiresDuplicateDetection As Nullable(Of Boolean) = null, Optional requiresSession As Nullable(Of Boolean) = null, Optional defaultMessageTimeToLive As Nullable(Of TimeSpan) = null, Optional deadLetteringOnMessageExpiration As Nullable(Of Boolean) = null, Optional duplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan) = null, Optional maxDeliveryCount As Nullable(Of Integer) = null, Optional status As Nullable(Of EntityStatus) = null, Optional autoDeleteOnIdle As Nullable(Of TimeSpan) = null, Optional enablePartitioning As Nullable(Of Boolean) = null, Optional enableExpress As Nullable(Of Boolean) = null, Optional forwardTo As String = null, Optional forwardDeadLetteredMessagesTo As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue : string * string * string * Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBQueue" Usage="new Microsoft.Azure.Management.ServiceBus.Models.SBQueue (id, name, type, countDetails, createdAt, updatedAt, accessedAt, sizeInBytes, messageCount, lockDuration, maxSizeInMegabytes, requiresDuplicateDetection, requiresSession, defaultMessageTimeToLive, deadLetteringOnMessageExpiration, duplicateDetectionHistoryTimeWindow, maxDeliveryCount, status, autoDeleteOnIdle, enablePartitioning, enableExpress, forwardTo, forwardDeadLetteredMessagesTo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="countDetails" Type="Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updatedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="accessedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="messageCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="lockDuration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxSizeInMegabytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresDuplicateDetection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="requiresSession" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultMessageTimeToLive" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="deadLetteringOnMessageExpiration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="duplicateDetectionHistoryTimeWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxDeliveryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;" />
        <Parameter Name="autoDeleteOnIdle" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="enablePartitioning" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableExpress" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="forwardTo" Type="System.String" />
        <Parameter Name="forwardDeadLetteredMessagesTo" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e815f-103">リソース Id</span><span class="sxs-lookup"><span data-stu-id="e815f-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="e815f-104">リソース名</span><span class="sxs-lookup"><span data-stu-id="e815f-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="e815f-105">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="e815f-105">Resource type</span></span></param>
        <param name="countDetails"><span data-ttu-id="e815f-106">メッセージ カウントの詳細。</span><span class="sxs-lookup"><span data-stu-id="e815f-106">Message Count Details.</span></span></param>
        <param name="createdAt"><span data-ttu-id="e815f-107">メッセージが作成された正確な時刻です。</span><span class="sxs-lookup"><span data-stu-id="e815f-107">The exact time the message was created.</span></span></param>
        <param name="updatedAt"><span data-ttu-id="e815f-108">メッセージが更新された正確な時刻です。</span><span class="sxs-lookup"><span data-stu-id="e815f-108">The exact time the message was updated.</span></span></param>
        <param name="accessedAt"><span data-ttu-id="e815f-109">前回のメッセージを送信した、または最後にこのキューの受信要求が発生しました。</span><span class="sxs-lookup"><span data-stu-id="e815f-109">Last time a message was sent, or the last time there was a receive request to this queue.</span></span></param>
        <param name="sizeInBytes"><span data-ttu-id="e815f-110">(バイト単位)、キューのサイズ。</span><span class="sxs-lookup"><span data-stu-id="e815f-110">The size of the queue, in bytes.</span></span></param>
        <param name="messageCount"><span data-ttu-id="e815f-111">キュー内のメッセージの数。</span><span class="sxs-lookup"><span data-stu-id="e815f-111">The number of messages in the queue.</span></span></param>
        <param name="lockDuration"><span data-ttu-id="e815f-112">ピーク/ロック; の ISO 8601 timespan の期間他の受信者に対してメッセージがロックされている時間の量は、します。</span><span class="sxs-lookup"><span data-stu-id="e815f-112">ISO 8601 timespan duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span> <span data-ttu-id="e815f-113">LockDuration の最大値は 5 分です。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-113">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span></param>
        <param name="maxSizeInMegabytes"><span data-ttu-id="e815f-114">キューに割り当てられたメモリのサイズをメガバイト単位でキューの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="e815f-114">The maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span>
            <span data-ttu-id="e815f-115">既定値は 1024 です。</span><span class="sxs-lookup"><span data-stu-id="e815f-115">Default is 1024.</span></span></param>
        <param name="requiresDuplicateDetection"><span data-ttu-id="e815f-116">このキューに重複データ検出が必要かどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="e815f-116">A value indicating if this queue requires duplicate detection.</span></span></param>
        <param name="requiresSession"><span data-ttu-id="e815f-117">キューがセッションの概念をサポートしているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="e815f-117">A value that indicates whether the queue supports the concept of sessions.</span></span></param>
        <param name="defaultMessageTimeToLive"><span data-ttu-id="e815f-118">有効期限値には、既定メッセージ timespan を ISO 8601 形式です。</span><span class="sxs-lookup"><span data-stu-id="e815f-118">ISO 8601 default message timespan to live value.</span></span> <span data-ttu-id="e815f-119">これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。</span><span class="sxs-lookup"><span data-stu-id="e815f-119">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="e815f-120">これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。</span><span class="sxs-lookup"><span data-stu-id="e815f-120">This is the default value used when TimeToLive is not set on a message itself.</span></span></param>
        <param name="deadLetteringOnMessageExpiration"><span data-ttu-id="e815f-121">メッセージの有効期限が切れるときに、このキューに配信不能サポートを持つかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="e815f-121">A value that indicates whether this queue has dead letter support when a message expires.</span></span></param>
        <param name="duplicateDetectionHistoryTimeWindow"><span data-ttu-id="e815f-122">ISO 8601 timeSpan 構造体、重複データ検出の履歴の期間を定義します。</span><span class="sxs-lookup"><span data-stu-id="e815f-122">ISO 8601 timeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="e815f-123">既定値は、10 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-123">The default value is 10 minutes.</span></span></param>
        <param name="maxDeliveryCount"><span data-ttu-id="e815f-124">最大配信数。</span><span class="sxs-lookup"><span data-stu-id="e815f-124">The maximum delivery count.</span></span> <span data-ttu-id="e815f-125">メッセージは自動的に配信不能になりましたに配信したファイルの数です。</span><span class="sxs-lookup"><span data-stu-id="e815f-125">A message is automatically deadlettered after this number of deliveries.</span></span> <span data-ttu-id="e815f-126">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="e815f-126">default value is 10.</span></span></param>
        <param name="status"><span data-ttu-id="e815f-127">メッセージング エンティティの状態の値を列挙します。</span><span class="sxs-lookup"><span data-stu-id="e815f-127">Enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="e815f-128">使用可能な値が含まれます: 'Active'、'Disabled'、'復元中'、'SendDisabled'、'ReceiveDisabled'、'作成中'、'削除'、'名前変更'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="e815f-128">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span></param>
        <param name="autoDeleteOnIdle"><span data-ttu-id="e815f-129">ISO 8061 timeSpan アイドル間隔するまで、キューは自動的に削除します。</span><span class="sxs-lookup"><span data-stu-id="e815f-129">ISO 8061 timeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="e815f-130">最小時間は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-130">The minimum duration is 5 minutes.</span></span></param>
        <param name="enablePartitioning"><span data-ttu-id="e815f-131">キューが複数のメッセージ ブローカーにわたって分割するかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="e815f-131">A value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span></param>
        <param name="enableExpress"><span data-ttu-id="e815f-132">エクスプレス エンティティが有効になっているかどうかを示す値。</span><span class="sxs-lookup"><span data-stu-id="e815f-132">A value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="e815f-133">エクスプレス キューでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</span><span class="sxs-lookup"><span data-stu-id="e815f-133">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span></param>
        <param name="forwardTo"><span data-ttu-id="e815f-134">メッセージを転送するキュー/トピック名</span><span class="sxs-lookup"><span data-stu-id="e815f-134">Queue/Topic name to forward the messages</span></span></param>
        <param name="forwardDeadLetteredMessagesTo"><span data-ttu-id="e815f-135">配信不能メッセージを転送キューまたはトピック名</span><span class="sxs-lookup"><span data-stu-id="e815f-135">Queue/Topic name to forward the Dead Letter message</span></span></param>
        <summary>
            <span data-ttu-id="e815f-136">SBQueue クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e815f-136">Initializes a new instance of the SBQueue class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AccessedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AccessedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AccessedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AccessedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-137">メッセージの最後の時刻を取得しますが送信されるか、このキューの受信要求が最後にします。</span><span class="sxs-lookup"><span data-stu-id="e815f-137">Gets last time a message was sent, or the last time there was a receive request to this queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoDeleteOnIdle">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; AutoDeleteOnIdle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; AutoDeleteOnIdle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoDeleteOnIdle As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.AutoDeleteOnIdle : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.AutoDeleteOnIdle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoDeleteOnIdle")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-138">取得またはその後、キューは自動的に削除 ISO 8061 timeSpan アイドル間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-138">Gets or sets ISO 8061 timeSpan idle interval after which the queue is automatically deleted.</span></span> <span data-ttu-id="e815f-139">最小時間は、5 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-139">The minimum duration is 5 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails CountDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CountDetails As MessageCountDetails" />
      <MemberSignature Language="F#" Value="member this.CountDetails : Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CountDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.countDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.MessageCountDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-140">メッセージ カウントの詳細の取得。</span><span class="sxs-lookup"><span data-stu-id="e815f-140">Gets message Count Details.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-141">メッセージが作成された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e815f-141">Gets the exact time the message was created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetteringOnMessageExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeadLetteringOnMessageExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeadLetteringOnMessageExpiration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeadLetteringOnMessageExpiration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DeadLetteringOnMessageExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deadLetteringOnMessageExpiration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-142">取得またはメッセージの有効期限が切れるときに、このキューに配信不能サポートを持つかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-142">Gets or sets a value that indicates whether this queue has dead letter support when a message expires.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMessageTimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DefaultMessageTimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DefaultMessageTimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultMessageTimeToLive As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DefaultMessageTimeToLive : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DefaultMessageTimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultMessageTimeToLive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-143">取得または ISO 8601 既定メッセージ timespan 値を有効期限を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-143">Gets or sets ISO 8601 default message timespan to live value.</span></span> <span data-ttu-id="e815f-144">これは、その後、メッセージは期限切れ、メッセージが Service Bus に送信されたときから開始期間です。</span><span class="sxs-lookup"><span data-stu-id="e815f-144">This is the duration after which the message expires, starting from when the message is sent to Service Bus.</span></span> <span data-ttu-id="e815f-145">これは、TimeToLive がメッセージ自体に設定されていない場合に使用される既定値です。</span><span class="sxs-lookup"><span data-stu-id="e815f-145">This is the default value used when TimeToLive is not set on a message itself.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DuplicateDetectionHistoryTimeWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; DuplicateDetectionHistoryTimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property DuplicateDetectionHistoryTimeWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.DuplicateDetectionHistoryTimeWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.DuplicateDetectionHistoryTimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.duplicateDetectionHistoryTimeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-146">取得または重複データ検出の履歴の期間を定義する ISO 8601 timeSpan 構造体を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-146">Gets or sets ISO 8601 timeSpan structure that defines the duration of the duplicate detection history.</span></span> <span data-ttu-id="e815f-147">既定値は、10 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-147">The default value is 10 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableExpress">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableExpress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableExpress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableExpress As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableExpress : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnableExpress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableExpress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-148">取得または Express のエンティティが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-148">Gets or sets a value that indicates whether Express Entities are enabled.</span></span> <span data-ttu-id="e815f-149">エクスプレス キューでは、永続的ストレージに書き込む前に一時的にメモリにメッセージを保持します。</span><span class="sxs-lookup"><span data-stu-id="e815f-149">An express queue holds a message in memory temporarily before writing it to persistent storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnablePartitioning">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnablePartitioning { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnablePartitioning" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberSignature Language="VB.NET" Value="Public Property EnablePartitioning As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnablePartitioning : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.EnablePartitioning" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enablePartitioning")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-150">取得またはキューが複数のメッセージ ブローカーにわたって分割するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-150">Gets or sets a value that indicates whether the queue is to be partitioned across multiple message brokers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardDeadLetteredMessagesTo">
      <MemberSignature Language="C#" Value="public string ForwardDeadLetteredMessagesTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardDeadLetteredMessagesTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardDeadLetteredMessagesTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardDeadLetteredMessagesTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardDeadLetteredMessagesTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-151">キュー/トピック名配信不能メッセージの転送を取得または設定</span><span class="sxs-lookup"><span data-stu-id="e815f-151">Gets or sets queue/Topic name to forward the Dead Letter message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForwardTo">
      <MemberSignature Language="C#" Value="public string ForwardTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ForwardTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ForwardTo As String" />
      <MemberSignature Language="F#" Value="member this.ForwardTo : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.ForwardTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.forwardTo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-152">キュー/トピック名、メッセージの転送を取得または設定</span><span class="sxs-lookup"><span data-stu-id="e815f-152">Gets or sets queue/Topic name to forward the messages</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; LockDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; LockDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property LockDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.LockDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.LockDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lockDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-153">取得またはピーク ロック; の ISO 8601 timespan の期間の設定他の受信者に対してメッセージがロックされている時間の量は、します。</span><span class="sxs-lookup"><span data-stu-id="e815f-153">Gets or sets ISO 8601 timespan duration of a peek-lock; that is, the amount of time that the message is locked for other receivers.</span></span>
            <span data-ttu-id="e815f-154">LockDuration の最大値は 5 分です。既定値は、1 分です。</span><span class="sxs-lookup"><span data-stu-id="e815f-154">The maximum value for LockDuration is 5 minutes; the default value is 1 minute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDeliveryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDeliveryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDeliveryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDeliveryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxDeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDeliveryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-155">取得または最大配信数を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-155">Gets or sets the maximum delivery count.</span></span> <span data-ttu-id="e815f-156">メッセージは自動的に配信不能になりましたに配信したファイルの数です。</span><span class="sxs-lookup"><span data-stu-id="e815f-156">A message is automatically deadlettered after this number of deliveries.</span></span> <span data-ttu-id="e815f-157">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="e815f-157">default value is 10.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeInMegabytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxSizeInMegabytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxSizeInMegabytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeInMegabytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxSizeInMegabytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MaxSizeInMegabytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeInMegabytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-158">取得またはキューに割り当てられたメモリのサイズであるキューの最大サイズをメガバイト単位で設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-158">Gets or sets the maximum size of the queue in megabytes, which is the size of memory allocated for the queue.</span></span> <span data-ttu-id="e815f-159">既定値は 1024 です。</span><span class="sxs-lookup"><span data-stu-id="e815f-159">Default is 1024.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MessageCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MessageCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MessageCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MessageCount : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.MessageCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.messageCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-160">キュー内のメッセージの数を取得します。</span><span class="sxs-lookup"><span data-stu-id="e815f-160">Gets the number of messages in the queue.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresDuplicateDetection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresDuplicateDetection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresDuplicateDetection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresDuplicateDetection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresDuplicateDetection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresDuplicateDetection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresDuplicateDetection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-161">取得またはこのキューに重複データ検出が必要かどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-161">Gets or sets a value indicating if this queue requires duplicate detection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresSession">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresSession { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresSession As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresSession : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.RequiresSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requiresSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-162">取得またはキューがセッションの概念をサポートするかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="e815f-162">Gets or sets a value that indicates whether the queue supports the concept of sessions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-163">キューのサイズをバイト単位で取得します。</span><span class="sxs-lookup"><span data-stu-id="e815f-163">Gets the size of the queue, in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As Nullable(Of EntityStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EntityStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-164">取得または設定は、メッセージング エンティティの状態の値を列挙します。</span><span class="sxs-lookup"><span data-stu-id="e815f-164">Gets or sets enumerates the possible values for the status of a messaging entity.</span></span> <span data-ttu-id="e815f-165">使用可能な値が含まれます: 'Active'、'Disabled'、'復元中'、'SendDisabled'、'ReceiveDisabled'、'作成中'、'削除'、'名前変更'、'Unknown'</span><span class="sxs-lookup"><span data-stu-id="e815f-165">Possible values include: 'Active', 'Disabled', 'Restoring', 'SendDisabled', 'ReceiveDisabled', 'Creating', 'Deleting', 'Renaming', 'Unknown'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; UpdatedAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; UpdatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.UpdatedAt : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.ServiceBus.Models.SBQueue.UpdatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.updatedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e815f-166">メッセージが更新された正確な時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="e815f-166">Gets the exact time the message was updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>