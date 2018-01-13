<Type Name="EventHubSender" FullName="Microsoft.ServiceBus.Messaging.EventHubSender">
  <TypeSignature Language="C#" Value="public sealed class EventHubSender : Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit EventHubSender extends Microsoft.ServiceBus.Messaging.ClientEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.EventHubSender" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class EventHubSender&#xA;Inherits ClientEntity" />
  <TypeSignature Language="F#" Value="type EventHubSender = class&#xA;    inherit ClientEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.ClientEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>使用されるクライアント クラスは、Event Hub の操作を送信します。
            特定の Event Hub パーティションに論理センダ接続を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBatch">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventDataBatch CreateBatch() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateBatch" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateBatch () As EventDataBatch" />
      <MemberSignature Language="F#" Value="member this.CreateBatch : unit -&gt; Microsoft.ServiceBus.Messaging.EventDataBatch" Usage="eventHubSender.CreateBatch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventDataBatch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>SendBatch または SendBatchAsync 呼び出しの後のイベント データ オブジェクトを追加する場所のバッチを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventDataBatch" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.EventHubSender CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.EventHubSender CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As EventHubSender" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.Messaging.EventHubSender" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubSender</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">使用する接続文字列。</param>
        <summary>
            新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" />指定された接続文字列を使用します。
            SharedAcessSignature とパブリッシャーで、接続文字列を使用して送信するために使用するためのものです。
            </summary>
        <returns>作成されました。<see cref="T:Microsoft.ServiceBus.Messaging.EventHubSender" /></returns>
        <remarks>接続を取得するか、Azure ポータルから、またはから作成された、<see cref="T:Microsoft.ServiceBus.ServiceBusConnectionStringBuilder" />インスタンス。</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected override void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="override this.OnAbort : unit -&gt; unit" Usage="eventHubSender.OnAbort " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnBeginClose(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginClose (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginClose : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubSender.OnBeginClose (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnBeginOpen(System.TimeSpan,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnBeginOpen (timeout As TimeSpan, callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="override this.OnBeginOpen : TimeSpan * AsyncCallback * obj -&gt; IAsyncResult" Usage="eventHubSender.OnBeginOpen (timeout, callback, state)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnClose(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnClose (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnClose : TimeSpan -&gt; unit" Usage="eventHubSender.OnClose timeout" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnEndClose(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndClose (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndClose : IAsyncResult -&gt; unit" Usage="eventHubSender.OnEndClose result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnEndOpen(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnEndOpen (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="override this.OnEndOpen : IAsyncResult -&gt; unit" Usage="eventHubSender.OnEndOpen result" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.OnOpen(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnOpen (timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="override this.OnOpen : TimeSpan -&gt; unit" Usage="eventHubSender.OnOpen timeout" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As String" />
      <MemberSignature Language="F#" Value="member this.PartitionId : string" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />
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
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.EventHubSender.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.ServiceBus.Messaging.EventHubSender.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Event Hub のパスを取得します。</summary>
        <value>Event Hub のパスです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Send">
      <MemberSignature Language="C#" Value="public void Send (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Send(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.Send(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Send (data As EventData)" />
      <MemberSignature Language="F#" Value="member this.Send : Microsoft.ServiceBus.Messaging.EventData -&gt; unit" Usage="eventHubSender.Send data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">送信する <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />。</param>
        <summary>によって表される、論理パーティションにイベント データを送信<see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />です。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendAsync (Microsoft.ServiceBus.Messaging.EventData data);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendAsync(class Microsoft.ServiceBus.Messaging.EventData data) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendAsync(Microsoft.ServiceBus.Messaging.EventData)" />
      <MemberSignature Language="VB.NET" Value="Public Function SendAsync (data As EventData) As Task" />
      <MemberSignature Language="F#" Value="member this.SendAsync : Microsoft.ServiceBus.Messaging.EventData -&gt; System.Threading.Tasks.Task" Usage="eventHubSender.SendAsync data" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="data" Type="Microsoft.ServiceBus.Messaging.EventData" />
      </Parameters>
      <Docs>
        <param name="data">送信する <see cref="T:Microsoft.ServiceBus.Messaging.EventData" />。</param>
        <summary><see cref="M:Microsoft.ServiceBus.Messaging.EventHubSender.Send(Microsoft.ServiceBus.Messaging.EventData)" /> の非同期バージョン。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendBatch">
      <MemberSignature Language="C#" Value="public void SendBatch (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SendBatch(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendBatch(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendBatch (eventDataList As IEnumerable(Of EventData))" />
      <MemberSignature Language="F#" Value="member this.SendBatch : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; unit" Usage="eventHubSender.SendBatch eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">イベント データ インスタンスを含む IEnumerable オブジェクト。</param>
        <summary>によって表される、論理パーティションにイベント データのバッチを送信<see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />です。</summary>
        <remarks>ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</exception>
      </Docs>
    </Member>
    <Member MemberName="SendBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SendBatchAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SendBatchAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventData&gt; eventDataList) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.EventHubSender.SendBatchAsync(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function SendBatchAsync (eventDataList As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="member this.SendBatchAsync : seq&lt;Microsoft.ServiceBus.Messaging.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="eventHubSender.SendBatchAsync eventDataList" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventDataList" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="eventDataList">イベント データ インスタンスを含む IEnumerable オブジェクト。</param>
        <summary>によって表される、論理パーティションにイベント データのバッチを非同期に送信<see cref="P:Microsoft.ServiceBus.Messaging.EventHubSender.PartitionId" />です。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>ユーザーを確認してください、合計のサイズをシリアル化<paramref name="eventDataList" />は既定で 256 k の 1 つのイベントのデータ転送のサイズ制限内にする必要があります。</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageSizeExceededException">シリアル化のサイズを合計する場合にスロー <paramref name="eventDataList" /> (既定で 256 k) の 1 つのイベント転送を許可されているサイズ上限を超えています。</exception>
      </Docs>
    </Member>
  </Members>
</Type>