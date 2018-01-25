<Type Name="ICommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener">
  <TypeSignature Language="C#" Value="public interface ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICommunicationListener" />
  <TypeSignature Language="F#" Value="type ICommunicationListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
                <span data-ttu-id="43722-101">基底インターフェイスおよび状態のマシン コントラクト Service Fabric サービスの通信リスナーを定義します。</span><span class="sxs-lookup"><span data-stu-id="43722-101">Defines the base interface and the state machine contract for the communication listener for a Service Fabric Service.</span></span>
                </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iCommunicationListener.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43722-102">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="43722-102">This method causes the communication listener to close.</span></span> <span data-ttu-id="43722-103">閉じる終了の状態は、このメソッドは、異常終了への移行。</span><span class="sxs-lookup"><span data-stu-id="43722-103">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="43722-104">このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。</span><span class="sxs-lookup"><span data-stu-id="43722-104">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCommunicationListener.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="43722-105">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43722-105">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="43722-106">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="43722-106">This method causes the communication listener to close.</span></span> <span data-ttu-id="43722-107">終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。</span><span class="sxs-lookup"><span data-stu-id="43722-107">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="43722-108">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="43722-108">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iCommunicationListener.OpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
                <span data-ttu-id="43722-109">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="43722-109">Cancellation token</span></span>
            </param>
        <summary>
                <span data-ttu-id="43722-110">このメソッドによって、通信リスナーを開くことができません。</span><span class="sxs-lookup"><span data-stu-id="43722-110">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="43722-111">Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="43722-111">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
                </summary>
        <returns>
            <span data-ttu-id="43722-112">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="43722-112">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="43722-113">タスクの結果は、エンドポイントの文字列です。</span><span class="sxs-lookup"><span data-stu-id="43722-113">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>