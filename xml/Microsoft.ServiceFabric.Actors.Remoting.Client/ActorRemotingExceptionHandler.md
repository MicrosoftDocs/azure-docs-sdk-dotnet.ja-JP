<Type Name="ActorRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ActorRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ActorRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="8ea70-101">このクラスは、リモート アクター インターフェイス経由での service fabric アクターと通信中に発生した例外の処理を提供します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-101">This class provide handling of exceptions encountered in communicating with service fabric actors over remoted actor interfaces.</span></span>
            </summary>
    <remarks>
      <para>
                <span data-ttu-id="8ea70-102">この例外ハンドラーは、次のシナリオに関連する例外を処理します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-102">This exception handler handles exceptions related to the following scenarios.</span></span>
            </para>
      <list type="list">
        <item>
          <term>
                <span data-ttu-id="8ea70-103">重複するメッセージ。</span><span class="sxs-lookup"><span data-stu-id="8ea70-103">Duplicate Messages:</span></span>
            </term>
          <description>
            <para>
                <span data-ttu-id="8ea70-104">例外処理のロジックに基づくクライアントからアクターに対して実行される操作が再試行されます。</span><span class="sxs-lookup"><span data-stu-id="8ea70-104">Operations performed on the actor are retried from the client based on the exception handling logic.</span></span> <span data-ttu-id="8ea70-105">これらの例外は、サービスのフェールオーバーを含むさまざまなエラー状態を表します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-105">These exceptions represent various error condition including service failover.</span></span> <span data-ttu-id="8ea70-106">したがって、アクターが重複するメッセージを受信することです。</span><span class="sxs-lookup"><span data-stu-id="8ea70-106">Therefore it is possible for the actors to receive duplicate messages.</span></span> <span data-ttu-id="8ea70-107">アクターによって前のメッセージの処理中に重複するメッセージを受信する場合、ランタイムは、クライアントに内部例外を返します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-107">If a duplicate message is received while previous message is being processed by the actor, runtime return an internal exception to the client.</span></span> <span data-ttu-id="8ea70-108">クライアントは、アクターから結果を戻すために、操作を再試行します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-108">The client then retries the operation to get the result back from the actor.</span></span> <span data-ttu-id="8ea70-109">クライアントがアクターの観点から重複する操作が実行され、操作は既に処理されて、し、重複するメッセージが到着した場合と同様の方法で処理が必要です。</span><span class="sxs-lookup"><span data-stu-id="8ea70-109">From the actor's perspective duplicate operation will be performed by the clients and it should handle it in the similar manner as if the operation was already processed and then a duplicate message arrived.</span></span> 
                </para>
            <para>
                <span data-ttu-id="8ea70-110">返すことによって処理されている重複した操作に関連する例外が処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="8ea70-110">Exception related to duplicate operation being processed is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method.</span></span>
                <span data-ttu-id="8ea70-111"><see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。</span><span class="sxs-lookup"><span data-stu-id="8ea70-111">The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to true, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />.</span></span>
                </para>
          </description>
        </item>
        <item>
          <term>
            <span data-ttu-id="8ea70-112"><see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:</span><span class="sxs-lookup"><span data-stu-id="8ea70-112"><see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:</span></span>
            </term>
          <description>
            <para>
                <span data-ttu-id="8ea70-113">アクターの操作は、基にする同時実行のロックを使用して実行されます (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />) 論理呼び出しコンテキスト ベースの再入をサポートします。</span><span class="sxs-lookup"><span data-stu-id="8ea70-113">Operations on the actors are performed using a turn based concurrency lock (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />) that supports logical call context based reentrancy.</span></span> <span data-ttu-id="8ea70-114">実行時間の長いアクター操作した場合は、このロックはタイムアウトが発生するの買収可能性があります。ロックの取得こともできます (アクター A および B が互いを同時にほぼ呼び出してアクター) に、デッドロックが発生した場合はタイムアウトが発生します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-114">In case of the long running actor operations it is possible for acquisition of this lock to time out. The acquisition of the lock can also time out in case of the deadlock situations (actor A and actor B calling each other almost at the same time).</span></span> 
                </para>
            <para>
                <span data-ttu-id="8ea70-115">同時実行のロックのタイムアウトに関連する例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッド操作を実行するクライアントが別のアクターにない場合。</span><span class="sxs-lookup"><span data-stu-id="8ea70-115">The exception related to concurrency lock timeout is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method if the client performing the operation is not another actor.</span></span>
                <span data-ttu-id="8ea70-116"><see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />のプロパティ、<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />設定を true に、<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />プロパティは、ランダムな値にするように設定<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" />と<see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />プロパティに設定されている<see cref="F:System.Int32.MaxValue" />です。</span><span class="sxs-lookup"><span data-stu-id="8ea70-116">The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to true, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />.</span></span>
                </para>
            <para>
                <span data-ttu-id="8ea70-117">同時実行のロックのタイムアウトに関連する例外を返すことによって処理される<see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" />から、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />メソッド、操作を実行するクライアントが別のアクターの場合。</span><span class="sxs-lookup"><span data-stu-id="8ea70-117">The exception related to concurrency lock timeout is handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method, if the client performing the operation is another actor.</span></span> <span data-ttu-id="8ea70-118">これにより、呼び出しチェーンまでアンワインドするデッドロック状態では、元のクライアントにバックアップし、そこから、操作が再試行します。</span><span class="sxs-lookup"><span data-stu-id="8ea70-118">In the deadlock situations this allows the call chain to unwind all the way back to the original client and the operation is then retried from there.</span></span>
                </para>
          </description>
        </item>
      </list>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                <span data-ttu-id="8ea70-119">新しいインスタンスを作成<see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />リモート アクター インターフェイス経由での service fabric アクターと通信中に発生した例外の処理に使用できます。</span><span class="sxs-lookup"><span data-stu-id="8ea70-119">Instantiates a new <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" /> which can be used to handle exceptions encountered in communicating with service fabric actors over remoted actor interfaces.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="result" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="exceptionInformation"><span data-ttu-id="8ea70-120">例外に関する情報</span><span class="sxs-lookup"><span data-stu-id="8ea70-120">Information about the exception</span></span></param>
        <param name="retrySettings"><span data-ttu-id="8ea70-121">操作の再試行の設定。</span><span class="sxs-lookup"><span data-stu-id="8ea70-121">The operation retry preferences.</span></span></param>
        <param name="result"><span data-ttu-id="8ea70-122">例外処理の結果</span><span class="sxs-lookup"><span data-stu-id="8ea70-122">Result of the exception handling</span></span></param>
        <summary>
            <span data-ttu-id="8ea70-123">例外を調査し、その例外を処理する方法を判断するメソッドです。</span><span class="sxs-lookup"><span data-stu-id="8ea70-123">Method that examines the exception and determines how that exception can be handled.</span></span> 
            </summary>
        <returns><span data-ttu-id="8ea70-124">true の場合は、例外処理、それ以外の場合</span><span class="sxs-lookup"><span data-stu-id="8ea70-124">true if the exception is handled, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>