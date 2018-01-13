<Type Name="IPartitionReceiveHandler" FullName="Microsoft.Azure.EventHubs.IPartitionReceiveHandler">
  <TypeSignature Language="C#" Value="public interface IPartitionReceiveHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPartitionReceiveHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.IPartitionReceiveHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPartitionReceiveHandler" />
  <TypeSignature Language="F#" Value="type IPartitionReceiveHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7ede9-101">受信操作の場合は、ハンドラーのインターフェイス</span><span class="sxs-lookup"><span data-stu-id="7ede9-101">A handler interface for the receive operation.</span></span> <span data-ttu-id="7ede9-102">このインターフェイスの実装を使用して、使用する場合は、ユーザーの操作を指定する<see cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />です。</span><span class="sxs-lookup"><span data-stu-id="7ede9-102">Use any implementation of this interface to specify user action when using <see cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.SetReceiveHandler(Microsoft.Azure.EventHubs.IPartitionReceiveHandler)" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxBatchSize">
      <MemberSignature Language="C#" Value="public int MaxBatchSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBatchSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.MaxBatchSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxBatchSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBatchSize : int" Usage="Microsoft.Azure.EventHubs.IPartitionReceiveHandler.MaxBatchSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ede9-103">最大バッチ サイズを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ede9-103">Gets the maximum batch size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessErrorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessErrorAsync (Exception error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessErrorAsync(class System.Exception error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.ProcessErrorAsync(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessErrorAsync (error As Exception) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessErrorAsync : Exception -&gt; System.Threading.Tasks.Task" Usage="iPartitionReceiveHandler.ProcessErrorAsync error" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="error" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="error"><span data-ttu-id="7ede9-104"><see cref="T:System.Exception" />処理するには</span><span class="sxs-lookup"><span data-stu-id="7ede9-104">The <see cref="T:System.Exception" /> to be processed</span></span></param>
        <summary>
            <span data-ttu-id="7ede9-105">イベントの受信中にスローされる例外を処理するために実装します。</span><span class="sxs-lookup"><span data-stu-id="7ede9-105">Implement in order to handle exceptions that are thrown during receipt of events.</span></span>
            </summary>
        <returns><span data-ttu-id="7ede9-106">Asynchronour 操作</span><span class="sxs-lookup"><span data-stu-id="7ede9-106">An asynchronour operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessEventsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProcessEventsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt; events);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ProcessEventsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.EventHubs.EventData&gt; events) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.IPartitionReceiveHandler.ProcessEventsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.EventHubs.EventData})" />
      <MemberSignature Language="VB.NET" Value="Public Function ProcessEventsAsync (events As IEnumerable(Of EventData)) As Task" />
      <MemberSignature Language="F#" Value="abstract member ProcessEventsAsync : seq&lt;Microsoft.Azure.EventHubs.EventData&gt; -&gt; System.Threading.Tasks.Task" Usage="iPartitionReceiveHandler.ProcessEventsAsync events" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="events" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.EventHubs.EventData&gt;" />
      </Parameters>
      <Docs>
        <param name="events"><span data-ttu-id="7ede9-107">対応する PartitionReceiver からフェッチされたイベントの一覧です。</span><span class="sxs-lookup"><span data-stu-id="7ede9-107">The list of fetched events from the corresponding PartitionReceiver.</span></span></param>
        <summary>
            <span data-ttu-id="7ede9-108">ユーザーは、受信したイベント上で実行されるアクションを指定するには、このメソッドを実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="7ede9-108">Users should implement this method to specify the action to be performed on the received events.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:Microsoft.Azure.EventHubs.PartitionReceiver.ReceiveAsync(System.Int32)" />
      </Docs>
    </Member>
  </Members>
</Type>