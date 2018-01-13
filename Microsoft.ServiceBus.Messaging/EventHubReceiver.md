<Type Name="EventHubReceiver" FullName="Microsoft.ServiceBus.Messaging.EventHubReceiver">
  <TypeSignature Language="C#" Value="public sealed class EventHubReceiver : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubReceiver extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubReceiver" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubReceiver&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubReceiver = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>使用されるクライアント クラスには、イベント ハブ コンシューマー グループに関連する操作が表示されます。 コンシューマー グループ内の特定の Event Hub パーティションに論理受信接続を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Epoch">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Epoch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Epoch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Epoch As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Epoch : Nullable&lt;int64&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>受信操作中にパーティションの所有権を決定するために使用するエポック値を取得します。</summary>
        <value><see cref="T:System.Int64" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubPath">
      <MemberSignature Language="C#" Value="public string EventHubPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventHubPath As String" />
      <MemberSignature Language="F#" Value="member this.EventHubPath : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.EventHubPath" />
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
        <value>イベント ハブのパス。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>受信アダプターの作成時に設定されている受信者の識別子を取得します。</summary>
        <value>受信者の識別子を表す文字列。 識別子が設定されていない場合は null を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>イベント ハブの名前を取得します。</summary>
        <value>イベント ハブの名前。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OffsetInclusive">
      <MemberSignature Language="C#" Value="public bool OffsetInclusive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OffsetInclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OffsetInclusive As Boolean" />
      <MemberSignature Language="F#" Value="member this.OffsetInclusive : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.OffsetInclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>示す値を取得するかどうか<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />返される最初のイベントが開始オフセットを含むイベントであることを示して、包括的なオフセットとして扱われます。 通常、最初のイベントが返されますが、イベントの開始オフセット。</summary>
        <value><see cref="T:System.Boolean" /> を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubReceiver.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginClose (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubReceiver.OnBeginOpen (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndClose result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubReceiver.OnEndOpen result" />
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
    <Member MemberName="OnOpen">
      <MemberSignature Language="C#" Value="protected override void OnOpen (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnOpen(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubReceiver.OnOpen timeout" />
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
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public string PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub の論理パーティションのパーティション ID を取得します。</summary>
        <value>パーティションの識別子です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定操作を受け取るいずれかのイベントの数はアクティブにキャッシュします。 既定では、この値はから継承<see cref="T:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup" />です。 既定値は、300 です。</summary>
        <value>メッセージの受信者が同時に要求メッセージの数。</value>
        <remarks> この値に変更を次に、使用されますが、これには影響しません、受信側によって既にキャッシュされているイベントの数に、操作を受信します。 このプロパティを 0 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />を null にします。
            注カウントを低すぎる設定に影響すること、イベント ハブの効果的なパフォーマンスは、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">値が 10 の必要な最小値より小さい場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; PrefetchSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; PrefetchSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.PrefetchSizeInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchSizeInBytes" />
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
        <remarks>サイズの上限は、絶対的な制限ではありません。 サイズにサイズの価値を少なくとも 1 つのイベント データを使って実行されます。 この値に変更を次に、使用されますが、これには影響しません、受信側によって既にキャッシュされているイベントの数に、操作を受信します。 このプロパティを null 以外の値に設定は設定<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PrefetchCount" />をゼロにします。
            低すぎるサイズの設定に、イベント ハブの効果的なパフォーマンスは影響は、呼び出しを受信します。</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">サイズの値が 260 K バイトの必要な最小値より小さい場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive () As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : unit -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Event Hubs のイベント データを受信します。</summary>
        <returns>返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />オブジェクト、またはイベントのデータがない場合は null です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</param>
        <summary>指定された数までの Event Hubs イベント データを受信します。</summary>
        <returns>返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション。 コレクションが空の場合は、イベントが返されない、指定された時間、またはすべてのイベント内で最大<paramref name="maxCount" />が返されます。</returns>
        <remarks>サービスは待たず<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。 使用可能なイベントがあると、すぐに返します。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventData Receive (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventData Receive(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (waitTime As TimeSpan) As EventData" />
      <MemberSignature Language="F#" Value="member this.Receive : TimeSpan -&gt; Microsoft.ServiceBus.Messaging.EventData" Usage="eventHubReceiver.Receive waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventData</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime">ユーザーがイベント データの到着を待機する最大時間。</param>
        <summary>指定されたタイムアウト値を持つ Event Hubs のイベント データを受信します。</summary>
        <returns>返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション、または使用可能なイベント データがない場合は null です。</returns>
        <remarks>
          <paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Receive">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; Receive (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; Receive(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function Receive (maxCount As Integer, waitTime As TimeSpan) As IEnumerable(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.Receive : int * TimeSpan -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.Receive (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</param>
        <param name="waitTime">ユーザーがイベント データの到着を待機する最大時間。</param>
        <summary>指定されたタイムアウト値を持つ、指定された数までの Event Hubs のイベント データを受信します。</summary>
        <returns>返します、受け取った<see cref="T:Microsoft.ServiceBus.Messaging.EventData" />コレクション。 コレクションが空の場合は、イベントが返されない、指定された時間、またはすべてのイベント内で最大<paramref name="maxCount" />が返されます。</returns>
        <remarks>
          <paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。 サービスを待機しませんまた<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。 使用可能なイベントがあると、すぐに返します。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">サービスには、一時的なエラーが発生した場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">クライアント サービスへの接続の問題がある場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">現在の名前空間がシステムに過剰な負荷を配置する場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ReceiverDisconnectedException">別の場合にスローされます、高いで受信者<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.Epoch" />値が現在の受信者によって指定された同じパーティションに接続されている<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync () As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>サービスは待たず<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。 使用可能なイベントがあると、すぐに返します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync (TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; ReceiveAsync(valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (waitTime As TimeSpan) As Task(Of EventData)" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" Usage="eventHubReceiver.ReceiveAsync waitTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventData&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="waitTime">ユーザーがイベント データの到着を待機する最大時間。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.TimeSpan)" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>
          <paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync (int maxCount, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt;&gt; ReceiveAsync(int32 maxCount, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiveAsync(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReceiveAsync (maxCount As Integer, waitTime As TimeSpan) As Task(Of IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.ReceiveAsync : int * TimeSpan -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;" Usage="eventHubReceiver.ReceiveAsync (maxCount, waitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxCount">イベント データ、ユーザーの最大量は、1 回の呼び出しでを許容できます。</param>
        <param name="waitTime">ユーザーがイベント データの到着を待機する最大時間。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive(System.Int32,System.TimeSpan)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>
          <paramref name="waitTime" />保証される待機時間、API は、使用可能になるとすぐに、データは返します。 サービスを待機しませんまた<paramref name="maxCount" />ユーザーに返す前に入力するイベントです。 使用可能なイベントがあると、すぐに返します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiverRuntimeMetricEnabled">
      <MemberSignature Language="C#" Value="public bool ReceiverRuntimeMetricEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReceiverRuntimeMetricEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReceiverRuntimeMetricEnabled : bool" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.ReceiverRuntimeMetricEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 受信側のランタイム メトリックが有効になっているかどうかを示す値を取得します。 </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuntimeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo RuntimeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RuntimeInfo As ReceiverRuntimeInfo" />
      <MemberSignature Language="F#" Value="member this.RuntimeInfo : Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.RuntimeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ReceiverRuntimeInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Event Hub の論理パーティションのランタイム情報のおおよその受信者を取得します。
            設定を有効にするを参照してください<see cref="T:Microsoft.ServiceBus.Messaging.ReceiverOptions" />と<see cref="P:Microsoft.ServiceBus.Messaging.EventHubConsumerGroup.EnableReceiverRuntimeMetric" /></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingDateTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartingDateTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartingDateTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingDateTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartingDateTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この受信者を表す UTC 形式で開始の日付と時刻を取得します。 <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />メソッドは、その後、次のイベントの受信を開始<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingDateTimeUtc" />値。 Null の場合、受信側は、Event Hubs のイベント ストリームの先頭からのイベントの受信を開始します。</summary>
        <value>開始の日付と時刻 (utc)。</value>
        <remarks>サービスは、次のイベントを配信するときだけこの datetime と概算値として使用します。
            留意クロックが存在することができますクライアント時間とサービスの時間のずれを重複しているイベントの配信を処理するユーザー アプリケーションを設計するためです。</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartingOffset">
      <MemberSignature Language="C#" Value="public string StartingOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartingOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartingOffset As String" />
      <MemberSignature Language="F#" Value="member this.StartingOffset : string" Usage="Microsoft.ServiceBus.Messaging.EventHubReceiver.StartingOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この受信者の開始オフセットを取得します。 <see cref="M:Microsoft.ServiceBus.Messaging.EventHubReceiver.Receive" />メソッドは、このオフセット値後は、次のイベントの受信を開始します。 値が null の場合、受信側は、Event Hubs のイベント ストリームの先頭からのイベントの受信を開始します。</summary>
        <value>開始オフセット。</value>
        <remarks>によって表される 1 つのパーティションのみに結び付ける開始オフセットこの<see cref="P:Microsoft.ServiceBus.Messaging.EventHubReceiver.PartitionId" />です。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>