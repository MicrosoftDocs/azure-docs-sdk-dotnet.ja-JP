<Type Name="IStatelessServiceInstance" FullName="System.Fabric.IStatelessServiceInstance">
  <TypeSignature Language="C#" Value="public interface IStatelessServiceInstance" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStatelessServiceInstance" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStatelessServiceInstance" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStatelessServiceInstance" />
  <TypeSignature Language="F#" Value="type IStatelessServiceInstance = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="da741-101">スタートアップ、初期化、およびシャット ダウンなどのステートレス サービス インスタンスのライフ サイクルを制御する動作を定義します。</span><span class="sxs-lookup"><span data-stu-id="da741-101">Defines behavior that governs the lifecycle of a stateless service instance, such as startup, initialization, and shutdown.</span></span> </para>
      <remarks>
            <span data-ttu-id="da741-102">ステートレス サービスの種類は、このインターフェイスを実装する必要があります。</span><span class="sxs-lookup"><span data-stu-id="da741-102">Stateless service types must implement this interface.</span></span> <span data-ttu-id="da741-103"><see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">信頼性の高いステートレス サービス</see>このインターフェイスを実装し、インスタンスのライフ サイクルを内部的に処理します。</span><span class="sxs-lookup"><span data-stu-id="da741-103">The <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statelessservice">Reliable Stateless service</see> implements this interface and handles instance lifecycle internally.</span></span>
            </remarks>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit" Usage="iStatelessServiceInstance.Abort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para> <span data-ttu-id="da741-104">このインスタンスをこの同期メソッドの呼び出しで異常終了します。</span><span class="sxs-lookup"><span data-stu-id="da741-104">Terminates this instance ungracefully with this synchronous method call.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="da741-105">異常終了の例は、その結果、Service Fabric プロセスのシャット ダウンし使用するネットワーク問題<see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" />レポートに、<see cref="F:System.Fabric.FaultType.Permanent" />フォールトします。</span><span class="sxs-lookup"><span data-stu-id="da741-105">Examples of ungraceful termination are network issues resulting in Service Fabric process shutdown and the use of <see cref="M:System.Fabric.IServicePartition.ReportFault(System.Fabric.FaultType)" /> to report a <see cref="F:System.Fabric.FaultType.Permanent" /> fault.</span></span> <span data-ttu-id="da741-106">サービス インスタンスは、このメソッドを受信すると、必要がありますすぐにリリースしのすべての参照をクリーンアップし、返します。</span><span class="sxs-lookup"><span data-stu-id="da741-106">When the service instance receives this method, it should immediately release and clean up all references and return.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStatelessServiceInstance.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para><span data-ttu-id="da741-107"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="da741-107">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="da741-108">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="da741-108">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="da741-109">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="da741-109">Note that cancellation is advisory and that the operation might still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="da741-110">サービス インスタンスがシャット ダウンすると、このサービス インスタンスを適切に閉じます。</span><span class="sxs-lookup"><span data-stu-id="da741-110">Closes this service instance gracefully when the service instance is being shut down.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="da741-111"><see cref="T:System.Threading.Tasks.Task" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="da741-111">Returns <see cref="T:System.Threading.Tasks.Task" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatelessServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatelessServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.Initialize(System.Fabric.StatelessServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatelessServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatelessServiceInitializationParameters -&gt; unit" Usage="iStatelessServiceInstance.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatelessServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para><span data-ttu-id="da741-112">このサービスの <see cref="T:System.Fabric.StatelessServiceInitializationParameters" />。</span><span class="sxs-lookup"><span data-stu-id="da741-112">The <see cref="T:System.Fabric.StatelessServiceInitializationParameters" /> for this service.</span></span></para>
        </param>
        <summary>
          <para> <span data-ttu-id="da741-113">新しく作成されたサービス インスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="da741-113">Initializes a newly created service instance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; OpenAsync (System.Fabric.IStatelessServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OpenAsync(class System.Fabric.IStatelessServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStatelessServiceInstance.OpenAsync(System.Fabric.IStatelessServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.IStatelessServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="iStatelessServiceInstance.OpenAsync (partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1006:DoNotNestGenericTypesInMemberSignatures", Justification="Approved public API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partition" Type="System.Fabric.IStatelessServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partition">
          <para>
                <span data-ttu-id="da741-114"><see cref="T:System.Fabric.IStatelessServicePartition" />このインスタンスに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="da741-114">The <see cref="T:System.Fabric.IStatelessServicePartition" /> that this instance is associated with</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="da741-115"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="da741-115">The <see cref="T:System.Threading.CancellationToken" /> object that the operation is observing.</span></span> <span data-ttu-id="da741-116">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="da741-116">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="da741-117">キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="da741-117">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="da741-118">クライアントが接続できるように、初期化されたサービス インスタンスを開きます。</span><span class="sxs-lookup"><span data-stu-id="da741-118">Opens an initialized service instance so that it can be contacted by clients.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="da741-119">返します<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:System.String" />します。</span><span class="sxs-lookup"><span data-stu-id="da741-119">Returns <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:System.String" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="da741-120">インスタンスのステートレスなサービスを開くことを示しますサービス今すぐ解決とサービス クライアントで検出することです。</span><span class="sxs-lookup"><span data-stu-id="da741-120">Opening an instance stateless service indicates that the service is now resolvable and discoverable by service clients.</span></span> <span data-ttu-id="da741-121">返される文字列は、このサービス インスタンスのアドレスです。</span><span class="sxs-lookup"><span data-stu-id="da741-121">The string that is returned is the address of this service instance.</span></span> <span data-ttu-id="da741-122">アドレスが Service Fabric が名前付けを使用して、サービス名に関連付けられているし、経由でサービスを解決するにはクライアントに返される<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />です。</span><span class="sxs-lookup"><span data-stu-id="da741-122">The address is associated with the service name via Service Fabric naming and returned to clients that resolve the service via <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>