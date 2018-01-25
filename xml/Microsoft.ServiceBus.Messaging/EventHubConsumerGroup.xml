<Type Name="EventHubConsumerGroup" FullName="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup">
  <TypeSignature Language="C#" Value="public sealed class EventHubConsumerGroup : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubConsumerGroup extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubConsumerGroup&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubConsumerGroup = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="a0c68-101">Event Hub 内のコンシューマー グループを表します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-101">Represents the consumer group within an Event Hub.</span></span> <span data-ttu-id="a0c68-102">このクラスは、Event Hub 内の特定のコンシューマー グループのレシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-102">This class creates receivers for a specific consumer group within an Event Hub.</span></span> <span data-ttu-id="a0c68-103">これには、既定のコンシューマー グループまたは別のユーザーが作成したコンシューマー グループを指定できます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-103">This can be the default consumer group or another user-created consumer group.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-104">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-104">The ID of the partition.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-105">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-105">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-106">指定したパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-106">Creates a new Event Hubs receiver in the specified partition.</span></span> <span data-ttu-id="a0c68-107">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-107">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-108">返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />特定の Event Hubs のパーティションに関連付けられているオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a0c68-108">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> object that is tied to the given Event Hubs partition.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-109">場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />がチェックポイント有効になっている、このオーバー ロードは、常に InvalidOperationException をスロー チェックポイントには、ConsumerGroup が有効になっているためにが動作するエポック必要です (エポック入力引数として指定するオーバー ロードを使用してください)。</span><span class="sxs-lookup"><span data-stu-id="a0c68-109">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, this overload will always throw InvalidOperationException because checkpoint enabled ConsumerGroup requires epoch to work (please use the overload that supply epoch as input argument).</span></span> <span data-ttu-id="a0c68-110">チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-110">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="a0c68-111">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-111">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="a0c68-112">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-112">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-113">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-113">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="a0c68-114">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</span><span class="sxs-lookup"><span data-stu-id="a0c68-114">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="a0c68-115">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-115">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, DateTime startingDateTimeUtc, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, valuetype System.DateTime startingDateTimeUtc, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * DateTime * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingDateTimeUtc, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-116">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-116">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="a0c68-117">メッセージを受信するための開始の UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="a0c68-117">The starting UTC time for receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-118">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-118">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-119">指定した日付と時刻から始まる、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-119">Creates a new Event Hubs receiver in the specified partition, starting at the specified date and time.</span></span> <span data-ttu-id="a0c68-120">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-120">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-121"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-121">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-122">サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-122">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="a0c68-123">留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-123">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="a0c68-124">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-124">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="a0c68-125">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-125">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-126">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-126">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="a0c68-127">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</span><span class="sxs-lookup"><span data-stu-id="a0c68-127">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="a0c68-128">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />で、<paramref name="startingDateTimeUtc" />指定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-128">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />, with an <paramref name="startingDateTimeUtc" /> specified.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-129">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-129">The ID of the partition.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-130">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-130">The epoch value.</span></span> <span data-ttu-id="a0c68-131">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-131">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-132">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-132">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-133">エポックの指定した値と、指定したパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-133">Creates a new Event Hubs receiver in the specified partition, and the specified epoch value.</span></span> <span data-ttu-id="a0c68-134">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-134">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-135"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-135">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-136">場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />受信側は、チェックポイントのオフセットから次のメッセージを取得し、有効な場合、チェックポイントがします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-136">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, then the receiver will get next message from the checkpoint offset.</span></span> <span data-ttu-id="a0c68-137">チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-137">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the event hub.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="a0c68-138">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-138">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="a0c68-139">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-139">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-140">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-140">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-141">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-141">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-142">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-142">The starting offset at which to start receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-143">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-143">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-144">指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-144">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="a0c68-145">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-145">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-146"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-146">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-147">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-147">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException"><span data-ttu-id="a0c68-148">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</span><span class="sxs-lookup"><span data-stu-id="a0c68-148">Thrown if the number of receivers currently connected to the partition specified by <paramref name="partitionId" /> has exceeded the maximum allowed quota set by the service.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException"><span data-ttu-id="a0c68-149">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />で、<paramref name="startingOffset" />指定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-149">Thrown if there is currently a receiver connected to the partition as specified by <paramref name="partitionId" />, with an <paramref name="startingOffset" /> specified.</span></span></exception>
        <code>
                <span data-ttu-id="a0c68-150">次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-150">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="a0c68-151">により、パーティション id の説明を入手したと仮定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-151">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="a0c68-152">EventHubDescription 説明です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-152">EventHubDescription description;</span></span>
                
                <span data-ttu-id="a0c68-153">EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.StartOfStream) です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-153">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.StartOfStream);</span></span>
                
                <span data-ttu-id="a0c68-154">var eventData 受信機を = です。Receive() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-154">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, DateTime startingDateTimeUtc, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, valuetype System.DateTime startingDateTimeUtc, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * DateTime * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingDateTimeUtc, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-155">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-155">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="a0c68-156">メッセージを受信するための開始の UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="a0c68-156">The starting UTC time for receiving messages.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-157">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-157">The epoch value.</span></span> <span data-ttu-id="a0c68-158">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-158">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-159">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-159">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-160">指定した日付と時刻から始まる、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-160">Creates a new Event Hubs receiver in the specified partition, starting at the specified date and time.</span></span> <span data-ttu-id="a0c68-161">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-161">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-162"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-162">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-163">サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-163">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="a0c68-164">留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-164">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="a0c68-165">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-165">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="a0c68-166">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-166">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-167">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-167">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, bool offsetInclusive, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, bool offsetInclusive, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * bool * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-168">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-168">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-169">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-169">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="a0c68-170">示すブール値かどうか<paramref name="startingOffset" />ことを意味する包括的なオフセットとして扱われます最初<param name="receiverOptions">イベント ハブの受信側のオプションです。</param></span><span class="sxs-lookup"><span data-stu-id="a0c68-170">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first <param name="receiverOptions">Options for a event hub receiver.</param></span></span>
            <span data-ttu-id="a0c68-171">返されるイベントは、開始オフセットを含むイベントです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-171">event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="a0c68-172">通常、最初のイベントが返されますが、イベントの開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="a0c68-172">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="receiverOptions">To be added.</param>
        <summary><span data-ttu-id="a0c68-173">指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-173">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="a0c68-174">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-174">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-175"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-175">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="a0c68-176">次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-176">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer group.</span></span> <span data-ttu-id="a0c68-177">使用して//開始することと、以前に保存されたオフセットがオフセットされ、そのイベントを返す/最初のイベントとして/</span><span class="sxs-lookup"><span data-stu-id="a0c68-177">It uses // a previously stored offset as starting offset and return that event // as the first event</span></span>
                
                <span data-ttu-id="a0c68-178">により、パーティション id の説明を入手したと仮定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-178">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="a0c68-179">ユーザーがストアド オフセット EventHubDescription 説明を取得すると想定されます。文字列の storedOffset =「2478」です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-179">// Also assume user has retrieved the stored offset EventHubDescription description; string storedOffset = "2478";</span></span>
                
                <span data-ttu-id="a0c68-180">EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、storedOffset) です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-180">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), storedOffset);</span></span>
                
                <span data-ttu-id="a0c68-181">eventData は位置のオフセットは storedOffset var eventData を = = 受信機を = です。Receive() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-181">// eventData will have offset == storedOffset var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-182">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-182">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-183">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-183">The starting offset at which to start receiving messages.</span></span> <span data-ttu-id="a0c68-184">ストリームの先頭を指定するを参照してください。<see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-184">To specify the start of the stream, see <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-185">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-185">The epoch value.</span></span> <span data-ttu-id="a0c68-186">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-186">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-187">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-187">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-188">指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-188">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span></summary>
        <returns><span data-ttu-id="a0c68-189"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-189">Returns the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException"><span data-ttu-id="a0c68-190">サービスには、一時的なエラーが発生した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-190">Thrown if the service encounters a transient error.</span></span></exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException"><span data-ttu-id="a0c68-191">クライアント サービスへの接続の問題がある場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-191">Thrown if the client has a problem connecting to the service.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-192">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-192">Thrown if <paramref name="partitionId" /> is not within the expected range, as determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" /> property.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiver">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver (string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubReceiver CreateReceiver(string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiver : string * string * bool * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; Microsoft.ServiceBus.Messaging.EventHubReceiver" Usage="eventHubConsumerGroup.CreateReceiver (partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubReceiver</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-193">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-193">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-194">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-194">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="a0c68-195">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-195">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="a0c68-196">通常、最初のイベントが返されますが、イベントの開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="a0c68-196">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-197">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-197">The epoch value.</span></span> <span data-ttu-id="a0c68-198">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-198">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-199">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-199">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-200">指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-200">Creates a new Event Hubs receiver in the specified partition, at the specified starting offset.</span></span> <span data-ttu-id="a0c68-201">作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-201">You can use the created receiver to receive events for one Event Hubs partition, specified by <paramref name="partitionId" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-202"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-202">Returns <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-203">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-203">The ID of the partition.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-204">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-204">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-205"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-205">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-206"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-206">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-207">場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />がチェックポイント有効になっている、このオーバー ロードは、常に InvalidOperationException をスロー チェックポイントには、ConsumerGroup が有効になっているためにが動作するエポック必要です (エポック入力引数として指定するオーバー ロードを使用してください)。</span><span class="sxs-lookup"><span data-stu-id="a0c68-207">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, this overload will always throw InvalidOperationException because checkpoint enabled ConsumerGroup requires epoch to work (please use the overload that supply epoch as input argument).</span></span> <span data-ttu-id="a0c68-208">チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-208">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, DateTime startingDateTimeUtc, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, valuetype System.DateTime startingDateTimeUtc, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * DateTime * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingDateTimeUtc, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-209">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-209">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="a0c68-210">メッセージを受信するための開始の UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="a0c68-210">The starting UTC time for receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-211">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-211">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-212"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-212">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-213"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-213">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-214">サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-214">Service only use this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="a0c68-215">留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-215">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-216">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-216">The ID of the partition.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-217">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-217">The epoch value.</span></span> <span data-ttu-id="a0c68-218">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-218">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-219">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-219">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-220"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-220">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-221"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-221">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-222">場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />受信側は、チェックポイントのオフセットから次のメッセージを取得し、有効な場合、チェックポイントがします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-222">If the <see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" /> has checkpoint enabled, then the receiver will get next message from the checkpoint offset.</span></span> <span data-ttu-id="a0c68-223">チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-223">If checkpoint is disabled, then receiver will get message from the start of the event stream, as determined by the message retention policy of the Event Hub.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-224">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-224">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-225">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-225">The starting offset at which to start receiving messages.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-226">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-226">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-227"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-227">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-228"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-228">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, DateTime startingDateTimeUtc, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, valuetype System.DateTime startingDateTimeUtc, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * DateTime * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingDateTimeUtc, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingDateTimeUtc" Type="System.DateTime" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-229">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-229">The ID of the partition.</span></span></param>
        <param name="startingDateTimeUtc"><span data-ttu-id="a0c68-230">メッセージを受信するための開始の UTC 時刻。</span><span class="sxs-lookup"><span data-stu-id="a0c68-230">The starting UTC time for receiving messages.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-231">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-231">The epoch value.</span></span> <span data-ttu-id="a0c68-232">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-232">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-233">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-233">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-234"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-234">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-235"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-235">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-236">サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-236">Service only uses this <paramref name="startingDateTimeUtc" /> as an approximation when determining next event to deliver.</span></span>
            
            <span data-ttu-id="a0c68-237">留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-237">Keep in mind that there can be clock skew between client time and service time, so user application should be designed to handle duplication in event delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, bool offsetInclusive, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, bool offsetInclusive, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * bool * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, offsetInclusive, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-238">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-238">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-239">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-239">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="a0c68-240">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-240">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="a0c68-241">通常、最初のイベントが返されますが、イベントの開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="a0c68-241">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-242">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-242">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-243"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-243">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-244"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-244">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="a0c68-245">次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-245">// The following code snippet creates a receiver that receive events // from the first partitions of the default consumer group.</span></span> <span data-ttu-id="a0c68-246">使用して//開始することと、以前に保存されたオフセットがオフセットされ、そのイベントを返す/最初のイベントとして/</span><span class="sxs-lookup"><span data-stu-id="a0c68-246">It uses // a previously stored offset as starting offset and return that event // as the first event</span></span>
                
                <span data-ttu-id="a0c68-247">により、パーティション id の説明を入手したと仮定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-247">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="a0c68-248">ユーザーがストアド オフセット EventHubDescription 説明を取得すると想定されます。文字列の storedOffset =「2478」です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-248">// Also assume user has retrieved the stored offset EventHubDescription description; string storedOffset = "2478";</span></span>
                
                <span data-ttu-id="a0c68-249">EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、storedOffset) です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-249">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), storedOffset);</span></span>
                
                <span data-ttu-id="a0c68-250">eventData は位置のオフセットは storedOffset var eventData を = = 受信機を = です。Receive() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-250">// eventData will have offset == storedOffset var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-251">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-251">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-252">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-252">The starting offset at which to start receiving messages.</span></span> <span data-ttu-id="a0c68-253">ストリームの先頭を指定するを参照してください。<see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-253">To specify the start of the stream, see <see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-254">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-254">The epoch value.</span></span> <span data-ttu-id="a0c68-255">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-255">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-256">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-256">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-257"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-257">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-258"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-258">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateReceiverAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync (string partitionId, string startingOffset, bool offsetInclusive, long epoch, Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubReceiver&gt; CreateReceiverAsync(string partitionId, string startingOffset, bool offsetInclusive, int64 epoch, class Microsoft.ServiceBus.Messaging.ReceiverOptions receiverOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiverAsync(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
      <MemberSignature Language="F#" Value="member this.CreateReceiverAsync : string * string * bool * int64 * Microsoft.ServiceBus.Messaging.ReceiverOptions -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;" Usage="eventHubConsumerGroup.CreateReceiverAsync (partitionId, startingOffset, offsetInclusive, epoch, receiverOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubReceiver&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
        <Parameter Name="startingOffset" Type="System.String" />
        <Parameter Name="offsetInclusive" Type="System.Boolean" />
        <Parameter Name="epoch" Type="System.Int64" />
        <Parameter Name="receiverOptions" Type="Microsoft.ServiceBus.Messaging.ReceiverOptions" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="a0c68-259">パーティションの ID。</span><span class="sxs-lookup"><span data-stu-id="a0c68-259">The ID of the partition.</span></span></param>
        <param name="startingOffset"><span data-ttu-id="a0c68-260">メッセージの受信を開始する開始オフセットです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-260">The starting offset at which to start receiving messages.</span></span></param>
        <param name="offsetInclusive"><span data-ttu-id="a0c68-261">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-261">A Boolean value that indicates whether <paramref name="startingOffset" /> is treated as an inclusive offset, meaning that the first event returned is the event that contains the starting offset.</span></span> <span data-ttu-id="a0c68-262">通常、最初のイベントが返されますが、イベントの開始オフセット。</span><span class="sxs-lookup"><span data-stu-id="a0c68-262">Normally, the first event returned is the event after the starting offset.</span></span></param>
        <param name="epoch"><span data-ttu-id="a0c68-263">エポック値です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-263">The epoch value.</span></span> <span data-ttu-id="a0c68-264">サービスでは、値を使用して、パーティション/リースの所有権を強制します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-264">The service uses this value to enforce partition/lease ownership.</span></span></param>
        <param name="receiverOptions"><span data-ttu-id="a0c68-265">イベント ハブの受信側のオプションです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-265">Options for a event hub receiver.</span></span></param>
        <summary><span data-ttu-id="a0c68-266"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-266">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-267"><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-267">Returns <see cref="T:System.Threading.Tasks.Task`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultGroupName">
      <MemberSignature Language="C#" Value="public const string DefaultGroupName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultGroupName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.DefaultGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultGroupName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultGroupName : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.DefaultGroupName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a0c68-268">既定値は EventHub を作成するときに作成済みの ConsumerGroup の名前。</span><span class="sxs-lookup"><span data-stu-id="a0c68-268">The name of the default ConsumerGroup that is pre-created when creating EventHub.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubClient.GetDefaultConsumerGroup" />
      </Docs>
    </Member>
    <Member MemberName="EnableReceiverRuntimeMetric">
      <MemberSignature Language="C#" Value="public bool EnableReceiverRuntimeMetric { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableReceiverRuntimeMetric" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableReceiverRuntimeMetric As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableReceiverRuntimeMetric : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> <span data-ttu-id="a0c68-269">取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-269">Gets or sets a value indicating whether the runtime metric of a receiver is enabled.</span></span> </summary>
        <value> <span data-ttu-id="a0c68-270">クライアントがアクセスする場合は true。<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />を使用して<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-270">true if a client wants to access <see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" /> using <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />.</span></span> </value>
        <remarks><span data-ttu-id="a0c68-271">既定値は値から派生します。<see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></span><span class="sxs-lookup"><span data-stu-id="a0c68-271">Its default value is derived from the value of <see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOfStream">
      <MemberSignature Language="C#" Value="public const string EndOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string EndOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EndOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Const EndOfStream As String " />
      <MemberSignature Language="F#" Value="val mutable EndOfStream : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EndOfStream" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a0c68-272">ストリームの末尾を示す定数です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-272">The constant that denotes the end of a stream.</span></span> <span data-ttu-id="a0c68-273">これは、/時刻のオフセット値の特定のポイントではなく、最新のイベントからの受信を開始するレシーバー作成のオフセットの引数として使用できます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-273">This can be used as an offset argument in receiver creation to start receiving from the latest event, instead of a specific point in time/offset value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                <span data-ttu-id="a0c68-274">次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-274">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="a0c68-275">により、パーティション id の説明を入手したと仮定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-275">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="a0c68-276">EventHubDescription 説明です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-276">EventHubDescription description;</span></span>
                
                <span data-ttu-id="a0c68-277">EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.EndOfStream) です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-277">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.EndOfStream);</span></span>
                
                <span data-ttu-id="a0c68-278">var eventData 受信機を = です。Receive() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-278">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventHubPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0c68-279">イベント ハブのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-279">Gets the event hub path.</span></span></summary>
        <value><span data-ttu-id="a0c68-280">イベント ハブのパス</span><span class="sxs-lookup"><span data-stu-id="a0c68-280">The event hub path</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventProcessorLifeCycleManagerFaulted">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; EventProcessorLifeCycleManagerFaulted;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; EventProcessorLifeCycleManagerFaulted" />
      <MemberSignature Language="DocId" Value="E:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EventProcessorLifeCycleManagerFaulted" />
      <MemberSignature Language="VB.NET" Value="Public Event EventProcessorLifeCycleManagerFaulted As EventHandler(Of EventProcessorFaultedEventArgs) " />
      <MemberSignature Language="F#" Value="member this.EventProcessorLifeCycleManagerFaulted : EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; " Usage="member this.EventProcessorLifeCycleManagerFaulted : System.EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.ServiceBus.Messaging.EventProcessorFaultedEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GroupName">
      <MemberSignature Language="C#" Value="public string GroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.GroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GroupName As String" />
      <MemberSignature Language="F#" Value="member this.GroupName : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.GroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0c68-281">コンシューマー グループの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-281">Gets the name of the consumer group.</span></span></summary>
        <value><span data-ttu-id="a0c68-282">コンシューマー グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0c68-282">The name of the consumer group.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubConsumerGroup.OnAbort " />
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
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginClose">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginClose (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginClose(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubConsumerGroup.OnBeginClose (timeout, callback, state)" />
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
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnBeginOpen">
      <MemberSignature Language="C#" Value="protected override IAsyncResult OnBeginOpen (TimeSpan timeout, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.IAsyncResult OnBeginOpen(valuetype System.TimeSpan timeout, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubConsumerGroup.OnBeginOpen (timeout, callback, state)" />
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
        <param name="timeout">To be added.</param>
        <param name="callback">To be added.</param>
        <param name="state">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnClose">
      <MemberSignature Language="C#" Value="protected override void OnClose (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnClose(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubConsumerGroup.OnClose timeout" />
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
        <param name="timeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndClose">
      <MemberSignature Language="C#" Value="protected override void OnEndClose (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndClose(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubConsumerGroup.OnEndClose result" />
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
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnEndOpen">
      <MemberSignature Language="C#" Value="protected override void OnEndOpen (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnEndOpen(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubConsumerGroup.OnEndOpen result" />
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
        <param name="result">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0c68-283">取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-283">Gets or sets the number of events that any receive operation will actively cache.</span></span> <span data-ttu-id="a0c68-284">既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-284">By default, this value is inherited from <see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />.</span></span> <span data-ttu-id="a0c68-285">既定値は 10,000 です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-285">The default value is 10,000.</span></span></summary>
        <value><span data-ttu-id="a0c68-286">受信側をキャッシュできるイベントの数。</span><span class="sxs-lookup"><span data-stu-id="a0c68-286">The number of events that the receiver can cache.</span></span></value>
        <remarks><span data-ttu-id="a0c68-287">どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />これから作成されたインスタンスは既定ではこの値を継承します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-287">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created from this instance will inherit this value by default.</span></span>
            <span data-ttu-id="a0c68-288">この値に変更は、作成済みの受信側に反映されるまでをされませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />変更後に作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-288">Changes to this value will not be propagate to already created receiver, but will be used by new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created after the change.</span></span> <span data-ttu-id="a0c68-289">またこのプロパティの設定 0 以外は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />を null にします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-289">Also setting this property to non-zero will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" /> to null.</span></span>
            <span data-ttu-id="a0c68-290">注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-290">Note that setting the count too low will affect the effective performance of the event hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-291">値が 10 の必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-291">Thrown if the value is less than the minimum required value of 10.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="a0c68-292">取得または設定の最大サイズ (バイト単位) のいずれかの受信操作の合計がアクティブにキャッシュされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-292">Gets or sets the maximum size (in bytes) in total that any receive operation will actively cache.</span></span> <span data-ttu-id="a0c68-293">各イベント データのサイズによって、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-293">The size of each event data is determined by the <see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" /> property.</span></span></summary>
        <value><span data-ttu-id="a0c68-294"><see cref="T:System.Int64" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-294">Returns <see cref="T:System.Int64" />.</span></span></value>
        <remarks><span data-ttu-id="a0c68-295">サイズの上限は、絶対的な制限ではありません。</span><span class="sxs-lookup"><span data-stu-id="a0c68-295">The size limit is not an absolute limit.</span></span> <span data-ttu-id="a0c68-296">サイズにサイズの価値を少なくとも 1 つのイベント データを使って実行されます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-296">the size might go over by at least one event data worth of size.</span></span> <span data-ttu-id="a0c68-297">どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />これから作成されたインスタンスは既定ではこの値を継承します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-297">Any <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created from this instance will inherit this value by default.</span></span>
            <span data-ttu-id="a0c68-298">この値に変更は、作成済みの受信側に反映されるまでをされませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />変更後に作成します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-298">Changes to this value will not be propagate to already created receiver, but will be used by new <see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> created after the change.</span></span> <span data-ttu-id="a0c68-299">また、このプロパティを null 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />をゼロにします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-299">Also, setting this property to non-null value will set <see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" /> to zero.</span></span>
            <span data-ttu-id="a0c68-300">低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-300">Note that setting the size too low will affect the effective performance of the Event Hub receive call.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="a0c68-301">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-301">Thrown when the size value is less than the minimum required value of 260K bytes.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public void RegisterProcessor&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessor&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager -&gt; unit (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessor (lease, checkpointManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a0c68-302">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-302">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="a0c68-303">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-303">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-304">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-304">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <summary><span data-ttu-id="a0c68-305">実装を登録<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />、指定された Event Hub からイベントを利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-305">Registers an implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events from Event Hubs for the specified <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="a0c68-306">このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-306">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks><span data-ttu-id="a0c68-307">高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-307">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessor&lt;T&gt;">
      <MemberSignature Language="C#" Value="public void RegisterProcessor&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessor&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; unit (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessor (lease, checkpointManager, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a0c68-308">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-308">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="a0c68-309">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-309">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-310">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-310">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="a0c68-311"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a0c68-311">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="a0c68-312">実装を登録<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />、指定された Event Hub からイベントを利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-312">Registers an implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events from Event Hubs for the specified <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" /> starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="a0c68-313">このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-313">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks><span data-ttu-id="a0c68-314">高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-314">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorAsync``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessorAsync (lease, checkpointManager)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a0c68-315">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-315">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="a0c68-316">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-316">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-317">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-317">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <summary><span data-ttu-id="a0c68-318"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-318">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-319">非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a0c68-319">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorAsync&lt;T&gt; (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) where T : Microsoft.ServiceBus.Messaging.IEventProcessor;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorAsync&lt;(class Microsoft.ServiceBus.Messaging.IEventProcessor) T&gt;(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorAsync``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task (requires 'T :&gt; Microsoft.ServiceBus.Messaging.IEventProcessor)" Usage="eventHubConsumerGroup.RegisterProcessorAsync (lease, checkpointManager, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <InterfaceName>Microsoft.ServiceBus.Messaging.IEventProcessor</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="a0c68-320">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-320">Implementation of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></typeparam>
        <param name="lease"><span data-ttu-id="a0c68-321">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-321">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-322">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-322">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="a0c68-323"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a0c68-323">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="a0c68-324"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-324">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-325"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-325">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks><span data-ttu-id="a0c68-326">高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-326">To perform more advanced <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> creation, implement an <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> class which allows you to control how event processors are created.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactory">
      <MemberSignature Language="C#" Value="public void RegisterProcessorFactory (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessorFactory(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactory : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; unit" Usage="eventHubConsumerGroup.RegisterProcessorFactory (lease, checkpointManager, eventProcessorFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-327">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-327">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-328">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-328">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="a0c68-329">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-329">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <summary><span data-ttu-id="a0c68-330">登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />オブジェクトのインスタンスを作成するために使用<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションのイベントの利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から開始、<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-330">Registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> object used to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="a0c68-331">このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-331">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="a0c68-332">TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =</span><span class="sxs-lookup"><span data-stu-id="a0c68-332">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="a0c68-333">イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-333">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="a0c68-334">subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}</span><span class="sxs-lookup"><span data-stu-id="a0c68-334">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactory">
      <MemberSignature Language="C#" Value="public void RegisterProcessorFactory (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterProcessorFactory(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactory : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; unit" Usage="eventHubConsumerGroup.RegisterProcessorFactory (lease, checkpointManager, eventProcessorFactory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-335">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-335">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-336">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-336">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="a0c68-337">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-337">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="a0c68-338"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a0c68-338">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="a0c68-339">登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />オブジェクトのインスタンスを作成するために使用<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションのイベントの利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から開始、<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-339">Registers the <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" /> object used to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> in order to start consuming events for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />, starting from <see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />.</span></span> <span data-ttu-id="a0c68-340">このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-340">Use this overload to create an event processor that checkpoints the message offset using a custom implementation of <see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />.</span></span></summary>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="a0c68-341">TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =</span><span class="sxs-lookup"><span data-stu-id="a0c68-341">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="a0c68-342">イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-342">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="a0c68-343">subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}</span><span class="sxs-lookup"><span data-stu-id="a0c68-343">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.RegisterProcessorFactoryAsync (lease, checkpointManager, eventProcessorFactory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-344">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-344">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-345">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-345">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="a0c68-346">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-346">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <summary><span data-ttu-id="a0c68-347"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-347">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-348">非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a0c68-348">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                <span data-ttu-id="a0c68-349">TestEventProcessorFactory processorFactory = 新しい TestEventProcessorFactory() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-349">TestEventProcessorFactory processorFactory = new TestEventProcessorFactory();</span></span>
            
                <span data-ttu-id="a0c68-350">イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-350">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                
                <span data-ttu-id="a0c68-351">await subscriberGroup.RegisterProcessorFactoryAsync (リース、新しい TestCheckpointManager()、processorFactory) です。}</span><span class="sxs-lookup"><span data-stu-id="a0c68-351">await subscriberGroup.RegisterProcessorFactoryAsync(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="RegisterProcessorFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterProcessorFactoryAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterProcessorFactoryAsync(class Microsoft.ServiceBus.Messaging.Lease lease, class Microsoft.ServiceBus.Messaging.ICheckpointManager checkpointManager, class Microsoft.ServiceBus.Messaging.IEventProcessorFactory eventProcessorFactory, class Microsoft.ServiceBus.Messaging.EventProcessorOptions processorOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactoryAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />
      <MemberSignature Language="F#" Value="member this.RegisterProcessorFactoryAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.ICheckpointManager * Microsoft.ServiceBus.Messaging.IEventProcessorFactory * Microsoft.ServiceBus.Messaging.EventProcessorOptions -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.RegisterProcessorFactoryAsync (lease, checkpointManager, eventProcessorFactory, processorOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="checkpointManager" Type="Microsoft.ServiceBus.Messaging.ICheckpointManager" />
        <Parameter Name="eventProcessorFactory" Type="Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />
        <Parameter Name="processorOptions" Type="Microsoft.ServiceBus.Messaging.EventProcessorOptions" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-352">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-352">Partition information.</span></span></param>
        <param name="checkpointManager"><span data-ttu-id="a0c68-353">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-353">Checkpoints the offset for the specified partition when <see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" /> is called.</span></span></param>
        <param name="eventProcessorFactory"><span data-ttu-id="a0c68-354">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-354">Factory to create an instance of <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />.</span></span></param>
        <param name="processorOptions"><span data-ttu-id="a0c68-355"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="a0c68-355">An <see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> object.</span></span></param>
        <summary><span data-ttu-id="a0c68-356"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-356">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-357"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-357">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></returns>
        <remarks>To be added.</remarks>
        <code>
                 <span data-ttu-id="a0c68-358">TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =</span><span class="sxs-lookup"><span data-stu-id="a0c68-358">// TestEventProcessorFactory implements IEventProcessorFactory var processorFactory = new TestEventProcessorFactory();</span></span>
                 
                <span data-ttu-id="a0c68-359">イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-359">// Register event processor with each shard to start consuming messages var subscriberGroup = receiveClient.GetDefaultConsumerGroup(); foreach (var partitionId in hubDescription.PartitionIds) { Lease lease = new Lease() { PartitionId = partitionId, Offset = EventHubTestUtils.DefaultStartingOffset };</span></span>
                 
                 <span data-ttu-id="a0c68-360">subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}</span><span class="sxs-lookup"><span data-stu-id="a0c68-360">subscriberGroup.RegisterProcessorFactory(lease, new TestCheckpointManager(), processorFactory); }</span></span>
                 </code>
      </Docs>
    </Member>
    <Member MemberName="StartOfStream">
      <MemberSignature Language="C#" Value="public const string StartOfStream;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string StartOfStream" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />
      <MemberSignature Language="VB.NET" Value="Public Const StartOfStream As String " />
      <MemberSignature Language="F#" Value="val mutable StartOfStream : string" Usage="Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a0c68-361">この定数は、ストリームの開始を示します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-361">The constant that denotes the start of a stream.</span></span> <span data-ttu-id="a0c68-362">これは、受信者の作成のオフセットの引数として使用できます。</span><span class="sxs-lookup"><span data-stu-id="a0c68-362">This can be used as an offset argument in receiver creation.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                <span data-ttu-id="a0c68-363">次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。</span><span class="sxs-lookup"><span data-stu-id="a0c68-363">// the following code snippet creates a receiver that receive events // from the first partitions of the default consumer gorup.</span></span>
                
                <span data-ttu-id="a0c68-364">により、パーティション id の説明を入手したと仮定します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-364">// assume we have obtained the description which will gives us the partition ids.</span></span>
                <span data-ttu-id="a0c68-365">EventHubDescription 説明です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-365">EventHubDescription description;</span></span>
                
                <span data-ttu-id="a0c68-366">EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.StartOfStream) です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-366">EventHubClient client = EventHubClient.CreateFromConnectionString(connection); var defaultGroup = client.GetDefaultConsumerGroup(); var receiver = defaultGroup.CreateReceiver( description.PartitionIds.First(), EventHubConsumerGroup.StartOfStream);</span></span>
                
                <span data-ttu-id="a0c68-367">var eventData 受信機を = です。Receive() です。</span><span class="sxs-lookup"><span data-stu-id="a0c68-367">var eventData = receiver.Receive();</span></span>
                </code>
      </Docs>
    </Member>
    <Member MemberName="UnregisterProcessor">
      <MemberSignature Language="C#" Value="public void UnregisterProcessor (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnregisterProcessor(class Microsoft.ServiceBus.Messaging.Lease lease, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="F#" Value="member this.UnregisterProcessor : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.CloseReason -&gt; unit" Usage="eventHubConsumerGroup.UnregisterProcessor (lease, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-368">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-368">Partition information.</span></span></param>
        <param name="reason"><span data-ttu-id="a0c68-369">対象の理由<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />が呼び出されました。</span><span class="sxs-lookup"><span data-stu-id="a0c68-369">Reason for which <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> was called.</span></span></param>
        <summary><span data-ttu-id="a0c68-370">登録を解除<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションの<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />します。</span><span class="sxs-lookup"><span data-stu-id="a0c68-370">Unregisters <see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" /> for the partition specified by <see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />.</span></span> <span data-ttu-id="a0c68-371">これは、結果、<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />基になるイベント プロセッサで呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="a0c68-371">This results in <see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" /> being called on the underlying event processor.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterProcessorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterProcessorAsync (Microsoft.ServiceBus.Messaging.Lease lease, Microsoft.ServiceBus.Messaging.CloseReason reason);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterProcessorAsync(class Microsoft.ServiceBus.Messaging.Lease lease, valuetype Microsoft.ServiceBus.Messaging.CloseReason reason) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />
      <MemberSignature Language="F#" Value="member this.UnregisterProcessorAsync : Microsoft.ServiceBus.Messaging.Lease * Microsoft.ServiceBus.Messaging.CloseReason -&gt; System.Threading.Tasks.Task" Usage="eventHubConsumerGroup.UnregisterProcessorAsync (lease, reason)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="reason" Type="Microsoft.ServiceBus.Messaging.CloseReason" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="a0c68-372">パーティション情報。</span><span class="sxs-lookup"><span data-stu-id="a0c68-372">Partition information.</span></span></param>
        <param name="reason"><span data-ttu-id="a0c68-373">理由を<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />が呼び出されました。</span><span class="sxs-lookup"><span data-stu-id="a0c68-373">Reason that <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> was called.</span></span></param>
        <summary><span data-ttu-id="a0c68-374"><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> の非同期バージョン。</span><span class="sxs-lookup"><span data-stu-id="a0c68-374">Asynchronous version of <see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />.</span></span></summary>
        <returns><span data-ttu-id="a0c68-375">非同期操作を表すタスク インスタンス。</span><span class="sxs-lookup"><span data-stu-id="a0c68-375">A task instance that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>