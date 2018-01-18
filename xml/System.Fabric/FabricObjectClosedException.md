<Type Name="FabricObjectClosedException" FullName="System.Fabric.FabricObjectClosedException">
  <TypeSignature Language="C#" Value="public class FabricObjectClosedException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricObjectClosedException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricObjectClosedException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricObjectClosedException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricObjectClosedException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="0a08c-101">Service Fabric オブジェクトは、次の条件のいずれかが原因の閉じられた状態で、現在場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="0a08c-101">The exception that is thrown when the Service Fabric object is currently in a closed state due to one of the following conditions:</span></span>
                1. <span data-ttu-id="0a08c-102">Service Fabric オブジェクトを削除しています。</span><span class="sxs-lookup"><span data-stu-id="0a08c-102">The Service Fabric object is being deleted.</span></span>
                2. <span data-ttu-id="0a08c-103">Service Fabric オブジェクトは、フェールオーバーにより到達可能ではありません。</span><span class="sxs-lookup"><span data-stu-id="0a08c-103">The Service Fabric object is not reachable due to a failover.</span></span>
            </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="0a08c-104">サービスが Service Fabric での操作を実行しようとしたときにこの例外を確認できるなど、または<see cref="T:System.Fabric.FabricReplicator" />オブジェクトが closed 状態のときにします。</span><span class="sxs-lookup"><span data-stu-id="0a08c-104">For example, this exception can be observed when a service attempts to perform an operation on a Service Fabric or <see cref="T:System.Fabric.FabricReplicator" /> object while it is in the closed state.</span></span> <span data-ttu-id="0a08c-105">別の例での API が呼び出されると、<see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にあるときです。</span><span class="sxs-lookup"><span data-stu-id="0a08c-105">Another example is when an API is invoked on a <see cref="T:System.Fabric.FabricClient" /> object when it is in the closed state.</span></span></para>
      <para>
            <span data-ttu-id="0a08c-106">処理<see cref="T:System.Fabric.FabricObjectClosedException" />の<see cref="T:System.Fabric.FabricClient" />呼び出し: FabricClient の呼び出しが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />を参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient の例外処理</see>FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="0a08c-106">Handling <see cref="T:System.Fabric.FabricObjectClosedException" /> for <see cref="T:System.Fabric.FabricClient" /> calls: If a FabricClient call sees <see cref="T:System.Fabric.FabricObjectClosedException" />, see <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions">FabricClient Exception Handling</see> for handling common FabricClient failures.</span></span>
                </para>
      <para>
            <span data-ttu-id="0a08c-107">処理<see cref="T:System.Fabric.FabricObjectClosedException" />の<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>:</span><span class="sxs-lookup"><span data-stu-id="0a08c-107">Handling <see cref="T:System.Fabric.FabricObjectClosedException" /> for <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see> :</span></span>
                1. <span data-ttu-id="0a08c-108">サービスが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />で<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>、例外をキャッチしから返すか<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="0a08c-108">If the service sees <see cref="T:System.Fabric.FabricObjectClosedException" /> in <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>, it should catch the exception and return from <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>.</span></span>
                    <span data-ttu-id="0a08c-109"><see cref="T:System.Threading.CancellationToken" />に渡される<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>通知されるとします。</span><span class="sxs-lookup"><span data-stu-id="0a08c-109">The <see cref="T:System.Threading.CancellationToken" /> passed to <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see> would be signalled.</span></span> <span data-ttu-id="0a08c-110">この取り消しが通知時に、すべてのバック グラウンド タスクは実行を完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="0a08c-110">All background tasks should complete execution when this cancellation is signalled.</span></span>
                    2. <span data-ttu-id="0a08c-111">サービスが表示される場合<see cref="T:System.Fabric.FabricObjectClosedException" />(など、通信リスナー) 経由でクライアント要求を処理中に、サービスは、こと、新しいプライマリを見つけるために、サービスを解決する必要があります再それをクライアントに通知をクライアントに例外をスローする必要があります。</span><span class="sxs-lookup"><span data-stu-id="0a08c-111">If the service sees <see cref="T:System.Fabric.FabricObjectClosedException" /> while processing a client request (e.g. via their communication listener), the service should throw the exception to the client to signal the client that it should re-resolve the service in order to locate the new Primary.</span></span>
                
            <span data-ttu-id="0a08c-112">[注]場合、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>で削除された<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>、このオプションを表示しようとしています。 すべての呼び出し<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>はを参照してください<see cref="T:System.Fabric.FabricObjectClosedException" />です。</span><span class="sxs-lookup"><span data-stu-id="0a08c-112">[NOTE] If an <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> was removed via <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>, any calls trying to access this <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> would see <see cref="T:System.Fabric.FabricObjectClosedException" />.</span></span> <span data-ttu-id="0a08c-113">これらの呼び出しと同期する必要があります、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see>呼び出しを知っている必要がある、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>は削除されました。</span><span class="sxs-lookup"><span data-stu-id="0a08c-113">These calls needs to be synchronized with the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestatemanager.removeasync?view=azure-dotnet#Microsoft_ServiceFabric_Data_IReliableStateManager_RemoveAsync_Microsoft_ServiceFabric_Data_ITransaction_System_Uri_System_TimeSpan_">IReliableStateManager.RemoveAsync()</see> call and should know that the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> has been removed.</span></span>
            <span data-ttu-id="0a08c-114">このケースを処理する方法は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="0a08c-114">Possible ways to handle this case are:</span></span>
            1. <span data-ttu-id="0a08c-115">再作成、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>が削除されたし、操作をやり直してください。</span><span class="sxs-lookup"><span data-stu-id="0a08c-115">Recreate the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> if it was removed and retry the operation.</span></span>
            2. <span data-ttu-id="0a08c-116">無視する、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>およびその他の処理<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>サービス。</span><span class="sxs-lookup"><span data-stu-id="0a08c-116">Ignore the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> and process other <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> in the service.</span></span>
                3. <span data-ttu-id="0a08c-117">ロックを使用すると、競合を回避できます。</span><span class="sxs-lookup"><span data-stu-id="0a08c-117">Use locks to avoid the race.</span></span> <span data-ttu-id="0a08c-118">そのためは、削除の呼び出し場合、ユーザーの処理を停止、 <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see>さらにします。</span><span class="sxs-lookup"><span data-stu-id="0a08c-118">Hence if a remove call comes in, the user can stop processing the <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.data.ireliablestate?view=azure-dotnet">IReliableState</see> further.</span></span>
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0a08c-119">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</span><span class="sxs-lookup"><span data-stu-id="0a08c-119">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException errorCode" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="errorCode">
          <para><span data-ttu-id="0a08c-120">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0a08c-120">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-121">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />クラスを指定したエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0a08c-121">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="0a08c-122">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0a08c-122">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-123">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />と指定したエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0a08c-123">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" /> and a specified error message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="0a08c-124"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="0a08c-124">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="0a08c-125">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0a08c-125">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="0a08c-126">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="0a08c-126">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-127">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />コンテキストを指定して、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="0a08c-127">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class from a serialized object data, with a specified context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="0a08c-128">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0a08c-128">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="0a08c-129">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="0a08c-129">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="0a08c-130"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="0a08c-130">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-131">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="0a08c-131">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="0a08c-132">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0a08c-132">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="0a08c-133">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0a08c-133">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-134"><see cref="T:System.Fabric.FabricObjectClosedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0a08c-134">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricObjectClosedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (info, context, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="info">
          <para><span data-ttu-id="0a08c-135"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="0a08c-135">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="0a08c-136">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="0a08c-136">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="0a08c-137">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="0a08c-137">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="0a08c-138">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0a08c-138">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="0a08c-139">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />指定のコンテキストとエラー コードを含む、シリアル化されたオブジェクトのデータからのクラスです。</span><span class="sxs-lookup"><span data-stu-id="0a08c-139">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class from a serialized object data, with specified context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricObjectClosedException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricObjectClosedException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricObjectClosedException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricObjectClosedException" Usage="new System.Fabric.FabricObjectClosedException (message, inner, errorCode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
        <Parameter Name="errorCode" Type="System.Fabric.FabricErrorCode" />
      </Parameters>
      <Docs>
        <param name="message">
          <para><span data-ttu-id="0a08c-140">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="0a08c-140">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="0a08c-141">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="0a08c-141">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="0a08c-142"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="0a08c-142">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="0a08c-143">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="0a08c-143">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="0a08c-144">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricObjectClosedException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</span><span class="sxs-lookup"><span data-stu-id="0a08c-144">Initializes a new instance of <see cref="T:System.Fabric.FabricObjectClosedException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>