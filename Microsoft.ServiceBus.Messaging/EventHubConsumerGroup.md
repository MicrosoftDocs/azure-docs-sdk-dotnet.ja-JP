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
    <summary>Event Hub 内のコンシューマー グループを表します。 このクラスは、Event Hub 内の特定のコンシューマー グループのレシーバーを作成します。 これには、既定のコンシューマー グループまたは別のユーザーが作成したコンシューマー グループを指定できます。</summary>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定したパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns>返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />特定の Event Hubs のパーティションに関連付けられているオブジェクト。</returns>
        <remarks>場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />がチェックポイント有効になっている、このオーバー ロードは、常に InvalidOperationException をスロー チェックポイントには、ConsumerGroup が有効になっているためにが動作するエポック必要です (エポック入力引数として指定するオーバー ロードを使用してください)。 チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />です。</exception>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingDateTimeUtc">メッセージを受信するための開始の UTC 時刻。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定した日付と時刻から始まる、指定されたパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。
            
            留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />で、<paramref name="startingDateTimeUtc" />指定します。</exception>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>エポックの指定した値と、指定したパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />受信側は、チェックポイントのオフセットから次のメッセージを取得し、有効な場合、チェックポイントがします。 チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">指定されたパーティションに受信者の数が現在接続されている場合にスロー<paramref name="partitionId" />サービスによって設定されたクォータの上限を超えました。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">受信者は現在がある場合にスローで指定されたパーティションに接続されている<paramref name="partitionId" />で、<paramref name="startingOffset" />指定します。</exception>
        <code>
                次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。
                
                により、パーティション id の説明を入手したと仮定します。
                EventHubDescription 説明です。
                
                EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.StartOfStream) です。
                
                var eventData 受信機を = です。Receive() です。
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingDateTimeUtc">メッセージを受信するための開始の UTC 時刻。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定した日付と時刻から始まる、指定されたパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。
            
            留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="offsetInclusive">示すブール値かどうか<paramref name="startingOffset" />ことを意味する包括的なオフセットとして扱われます最初<param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
            返されるイベントは、開始オフセットを含むイベントです。 通常、最初のイベントが返されますが、イベントの開始オフセット。</param>
        <param name="receiverOptions">To be added.</param>
        <summary>指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <code>
                次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。 使用して//開始することと、以前に保存されたオフセットがオフセットされ、そのイベントを返す/最初のイベントとして/
                
                により、パーティション id の説明を入手したと仮定します。
                ユーザーがストアド オフセット EventHubDescription 説明を取得すると想定されます。文字列の storedOffset =「2478」です。
                
                EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、storedOffset) です。
                
                eventData は位置のオフセットは storedOffset var eventData を = = 受信機を = です。Receive() です。
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。 ストリームの先頭を指定するを参照してください。<see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />です。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスロー<paramref name="partitionId" />によって決定される、必要な範囲内にないため、<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.PartitionCount" />プロパティです。</exception>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="offsetInclusive">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。 通常、最初のイベントが返されますが、イベントの開始オフセット。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary>指定したオフセットで、指定されたパーティションに新しい Event Hub レシーバーを作成します。 作成された受信機を使用するにはによって指定された 1 つのイベント ハブ パーティションのイベントを受け取る<paramref name="partitionId" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" /> を返します。</returns>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />がチェックポイント有効になっている、このオーバー ロードは、常に InvalidOperationException をスロー チェックポイントには、ConsumerGroup が有効になっているためにが動作するエポック必要です (エポック入力引数として指定するオーバー ロードを使用してください)。 チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</remarks>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingDateTimeUtc">メッセージを受信するための開始の UTC 時刻。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。
            
            留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</remarks>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>場合、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />受信側は、チェックポイントのオフセットから次のメッセージを取得し、有効な場合、チェックポイントがします。 チェックポイントを無効にした場合、受信者メッセージが表示されます、イベント ストリームの先頭から、イベント ハブのメッセージの保有期間ポリシーによって決定されます。</remarks>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingDateTimeUtc">メッセージを受信するための開始の UTC 時刻。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.DateTime,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>サービスのみ使用してこの<paramref name="startingDateTimeUtc" />として配信する次のイベントを決定する際に近似します。
            
            留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</remarks>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="offsetInclusive">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。 通常、最初のイベントが返されますが、イベントの開始オフセット。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <code>
                次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。 使用して//開始することと、以前に保存されたオフセットがオフセットされ、そのイベントを返す/最初のイベントとして/
                
                により、パーティション id の説明を入手したと仮定します。
                ユーザーがストアド オフセット EventHubDescription 説明を取得すると想定されます。文字列の storedOffset =「2478」です。
                
                EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、storedOffset) です。
                
                eventData は位置のオフセットは storedOffset var eventData を = = 受信機を = です。Receive() です。
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。 ストリームの先頭を指定するを参照してください。<see cref="F:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.StartOfStream" />です。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
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
        <param name="partitionId">パーティションの ID。</param>
        <param name="startingOffset">メッセージの受信を開始する開始オフセットです。</param>
        <param name="offsetInclusive">ブール値を示すかどうか<paramref name="startingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。 通常、最初のイベントが返されますが、イベントの開始オフセット。</param>
        <param name="epoch">エポック値です。 サービスでは、値を使用して、パーティション/リースの所有権を強制します。</param>
        <param name="receiverOptions">イベント ハブの受信側のオプションです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,System.String,System.Boolean,System.Int64,Microsoft.ServiceBus.Messaging.ReceiverOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
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
            既定値は EventHub を作成するときに作成済みの ConsumerGroup の名前。
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
        <summary> 取得または受信側のランタイム メトリックが有効になっているかどうかを示す値を設定します。 </summary>
        <value> クライアントがアクセスする場合は true。<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" />を使用して<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />です。 </value>
        <remarks>既定値は値から派生します。<see cref="P:Microsoft.ServiceBus.Messaging.Amqp.AmqpTransportSettings.EnableReceiverRuntimeMetric" /></remarks>
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
            ストリームの末尾を示す定数です。 これは、/時刻のオフセット値の特定のポイントではなく、最新のイベントからの受信を開始するレシーバー作成のオフセットの引数として使用できます。
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。
                
                により、パーティション id の説明を入手したと仮定します。
                EventHubDescription 説明です。
                
                EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.EndOfStream) です。
                
                var eventData 受信機を = です。Receive() です。
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
        <summary>イベント ハブのパスを取得します。</summary>
        <value>イベント ハブのパス</value>
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
        <summary>コンシューマー グループの名前を取得します。</summary>
        <value>コンシューマー グループの名前。</value>
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
        <summary>取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。 既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.EventHubClient" />です。 既定値は 10,000 です。</summary>
        <value>受信側をキャッシュできるイベントの数。</value>
        <remarks>どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />これから作成されたインスタンスは既定ではこの値を継承します。
            この値に変更は、作成済みの受信側に反映されるまでをされませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />変更後に作成します。 またこのプロパティの設定 0 以外は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchSizeInBytes" />を null にします。
            注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 10 の必要な最小値より小さい場合にスローされます。</exception>
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
        <summary>取得または設定の最大サイズ (バイト単位) のいずれかの受信操作の合計がアクティブにキャッシュされます。 各イベント データのサイズによって、<see cref="P:Microsoft.ServiceBus.Messaging.EventData.SerializedSizeInBytes" />プロパティです。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>サイズの上限は、絶対的な制限ではありません。 サイズにサイズの価値を少なくとも 1 つのイベント データを使って実行されます。 どの<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />これから作成されたインスタンスは既定ではこの値を継承します。
            この値に変更は、作成済みの受信側に反映されるまでをされませんで使用される新しい<see cref="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />変更後に作成します。 また、このプロパティを null 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.PrefetchCount" />をゼロにします。
            低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</exception>
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
        <typeparam name="T">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</typeparam>
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <summary>実装を登録<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />、指定された Event Hub からイベントを利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。 このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</summary>
        <remarks>高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</remarks>
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
        <typeparam name="T">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</typeparam>
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="processorOptions"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</param>
        <summary>実装を登録<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />、指定された Event Hub からイベントを利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。 このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</summary>
        <remarks>高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</remarks>
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
        <typeparam name="T">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</typeparam>
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager)" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク インスタンス。</returns>
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
        <typeparam name="T">実装<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</typeparam>
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="processorOptions"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessor``1(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>高度なを実行する<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />作成、実装、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />クラスはイベント プロセッサを作成する方法を制御することができます。</remarks>
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
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="eventProcessorFactory">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</param>
        <summary>登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />オブジェクトのインスタンスを作成するために使用<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションのイベントの利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から開始、<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。 このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</summary>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =
                 
                イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。
                 
                 subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}
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
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="eventProcessorFactory">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</param>
        <param name="processorOptions"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</param>
        <summary>登録、<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessorFactory" />オブジェクトのインスタンスを作成するために使用<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションのイベントの利用を開始するために<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />から開始、<see cref="P:Microsoft.ServiceBus.Messaging.Lease.Offset" />です。 このオーバー ロードを使用してチェックポイントを作成するイベント プロセッサそのカスタム実装を使用してメッセージ オフセット<see cref="T:Microsoft.ServiceBus.Messaging.ICheckpointManager" />です。</summary>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =
                 
                イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。
                 
                 subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}
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
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="eventProcessorFactory">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory)" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
        <code>
                TestEventProcessorFactory processorFactory = 新しい TestEventProcessorFactory() です。
            
                イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。
                
                await subscriberGroup.RegisterProcessorFactoryAsync (リース、新しい TestCheckpointManager()、processorFactory) です。}
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
        <param name="lease">パーティション情報。</param>
        <param name="checkpointManager">チェックポイントに指定されたオフセットときにパーティション分割<see cref="M:Microsoft.ServiceBus.Messaging.PartitionContext.CheckpointAsync(Microsoft.ServiceBus.Messaging.EventData)" />と呼びます。</param>
        <param name="eventProcessorFactory">インスタンスを作成するファクトリ<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />です。</param>
        <param name="processorOptions"><see cref="T:Microsoft.ServiceBus.Messaging.EventProcessorOptions" /> オブジェクト。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.RegisterProcessorFactory(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.ICheckpointManager,Microsoft.ServiceBus.Messaging.IEventProcessorFactory,Microsoft.ServiceBus.Messaging.EventProcessorOptions)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <code>
                 TestEventProcessorFactory IEventProcessorFactory var processorFactory を実装する新しい TestEventProcessorFactory(); を =
                 
                イベント プロセッサを消費するメッセージ var subscriberGroup を各シャードに登録 receiveClient.GetDefaultConsumerGroup(); を =foreach (hubDescription.PartitionIds で var partitionId) {リースのリース新しい Lease() = {PartitionId = partitionId、オフセット = EventHubTestUtils.DefaultStartingOffset} です。
                 
                 subscriberGroup.RegisterProcessorFactory (リース、新しい TestCheckpointManager()、processorFactory) です。}
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
            この定数は、ストリームの開始を示します。 これは、受信者の作成のオフセットの引数として使用できます。
            </summary>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.CreateReceiver(System.String,Microsoft.ServiceBus.Messaging.ReceiverOptions)" />
        <code>
                次のコード スニペットは、イベントを受信する受信者を作成/および既定のコンシューマー グループの最初のパーティションからです。
                
                により、パーティション id の説明を入手したと仮定します。
                EventHubDescription 説明です。
                
                EventHubClient クライアント EventHubClient.CreateFromConnectionString(connection); を =var defaultGroup クライアントを = です。GetDefaultConsumerGroup() です。var 受信者 = defaultGroup.CreateReceiver (説明します。PartitionIds.First()、EventHubConsumerGroup.StartOfStream) です。
                
                var eventData 受信機を = です。Receive() です。
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
        <param name="lease">パーティション情報。</param>
        <param name="reason">対象の理由<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />が呼び出されました。</param>
        <summary>登録を解除<see cref="T:Microsoft.ServiceBus.Messaging.IEventProcessor" />によって指定されたパーティションの<see cref="P:Microsoft.ServiceBus.Messaging.Lease.PartitionId" />します。 これは、結果、<see cref="M:Microsoft.ServiceBus.Messaging.IEventProcessor.CloseAsync(Microsoft.ServiceBus.Messaging.PartitionContext,Microsoft.ServiceBus.Messaging.CloseReason)" />基になるイベント プロセッサで呼び出されるとします。</summary>
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
        <param name="lease">パーティション情報。</param>
        <param name="reason">理由を<see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessorAsync(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" />が呼び出されました。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.UnregisterProcessor(Microsoft.ServiceBus.Messaging.Lease,Microsoft.ServiceBus.Messaging.CloseReason)" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク インスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>