<Type Name="FabricNotPrimaryException" FullName="System.Fabric.FabricNotPrimaryException">
  <TypeSignature Language="C#" Value="public class FabricNotPrimaryException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricNotPrimaryException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricNotPrimaryException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricNotPrimaryException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricNotPrimaryException = class&#xA;    inherit FabricException" />
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
      <para><span data-ttu-id="f5f50-101">呼び出し先がプライマリではない場合にスローされる例外。</span><span class="sxs-lookup"><span data-stu-id="f5f50-101">The exception that is thrown when the callee is not a primary.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="f5f50-102"><see cref="T:System.Fabric.FabricNotPrimaryException" />呼び出し先には、プライマリは現在ありませんので、操作を実行することはできませんを示します。</span><span class="sxs-lookup"><span data-stu-id="f5f50-102">The <see cref="T:System.Fabric.FabricNotPrimaryException" /> indicates that the operation cannot be performed because the callee is currently not a primary.</span></span>
            <span data-ttu-id="f5f50-103">たとえば、この例外ができるセカンダリ レプリカが使用して、操作をレプリケートしようとしたかどうかに従って<see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />です。</span><span class="sxs-lookup"><span data-stu-id="f5f50-103">For example, this exception can be observed if a secondary replica attempted to replicate an operation via <see cref="M:System.Fabric.IStateReplicator.ReplicateAsync(System.Fabric.OperationData,System.Threading.CancellationToken,System.Int64@)" />.</span></span> <span data-ttu-id="f5f50-104">通常のシナリオは、レプリカがプライマリではなくなったことです。</span><span class="sxs-lookup"><span data-stu-id="f5f50-104">A likely scenario is that the replica is no longer the primary.</span></span></para>
      <para>
            <span data-ttu-id="f5f50-105">処理<see cref="T:System.Fabric.FabricNotPrimaryException" />の<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">信頼性の高いコレクション</see>:</span><span class="sxs-lookup"><span data-stu-id="f5f50-105">Handling <see cref="T:System.Fabric.FabricNotPrimaryException" /> for <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">Reliable Collections</see> :</span></span>
                1. <span data-ttu-id="f5f50-106">サービスが表示される場合<see cref="T:System.Fabric.FabricNotPrimaryException" />で<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>、例外をキャッチする必要があります、完全なすべてのタスクから返す<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>です。</span><span class="sxs-lookup"><span data-stu-id="f5f50-106">If the service sees <see cref="T:System.Fabric.FabricNotPrimaryException" /> in <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>, it should catch the exception, complete all tasks and return from <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>.</span></span> <span data-ttu-id="f5f50-107"><see cref="T:System.Threading.CancellationToken" />に渡される<see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see>通知されるとします。</span><span class="sxs-lookup"><span data-stu-id="f5f50-107">The <see cref="T:System.Threading.CancellationToken" /> passed to <see href="https://docs.microsoft.com/dotnet/api/microsoft.servicefabric.services.runtime.statefulservicebase.runasync?viewFallbackFrom=servicefabricsvcs#Microsoft_ServiceFabric_Services_Runtime_StatefulServiceBase_RunAsync_System_Threading_CancellationToken_">RunAsync</see> would be signalled.</span></span> <span data-ttu-id="f5f50-108">この取り消しが通知時に、すべてのバック グラウンド タスクは実行を完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f5f50-108">All background tasks should complete execution when this cancellation is signalled.</span></span>
                    2. <span data-ttu-id="f5f50-109">サービスが表示される場合<see cref="T:System.Fabric.FabricNotPrimaryException" />(など、通信リスナー) 経由でクライアント要求を処理中に、サービスは、こと、新しいプライマリを見つけるために、サービスを解決する必要があります再それをクライアントに通知をクライアントに例外をスローする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f5f50-109">If the service sees <see cref="T:System.Fabric.FabricNotPrimaryException" /> while processing a client request (e.g. via their communication listener), the service should throw the exception to the client to signal the client that it should re-resolve the service in order to locate the new Primary.</span></span>
                    </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f5f50-110">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />エラー コードを持つクラス<see cref="F:System.Fabric.FabricErrorCode.Unknown" />です。</span><span class="sxs-lookup"><span data-stu-id="f5f50-110">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with error code <see cref="F:System.Fabric.FabricErrorCode.Unknown" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException (System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException errorCode" />
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
          <para><span data-ttu-id="f5f50-111">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-111">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-112">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />クラスを指定したエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-112">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with a specified error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : string -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException message" />
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
          <para><span data-ttu-id="f5f50-113">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f5f50-113">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-114">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />メッセージが指定されたクラスです。</span><span class="sxs-lookup"><span data-stu-id="f5f50-114">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with a specified message.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricNotPrimaryException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException (info, context)" />
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
          <para><span data-ttu-id="f5f50-115"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="f5f50-115">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="f5f50-116">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f5f50-116">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="f5f50-117">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="f5f50-117">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-118">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />、指定した情報を持つクラス コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="f5f50-118">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with specified info, context.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : string * Exception -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException (message, inner)" />
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
          <para><span data-ttu-id="f5f50-119">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f5f50-119">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="f5f50-120">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="f5f50-120">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="f5f50-121"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="f5f50-121">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="f5f50-122">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="f5f50-122">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException (string message, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.String,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : string * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException (message, errorCode)" />
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
          <para><span data-ttu-id="f5f50-123">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f5f50-123">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="f5f50-124">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-124">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-125">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />クラスを指定したメッセージとエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-125">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with specified message and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricNotPrimaryException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException (info, context, errorCode)" />
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
          <para><span data-ttu-id="f5f50-126"><see cref="T:System.Runtime.Serialization.SerializationInfo" />を含むオブジェクトがスローされた例外オブジェクト データをシリアル化します。</span><span class="sxs-lookup"><span data-stu-id="f5f50-126">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> object that contains serialized object data of the exception being thrown.</span></span></para>
        </param>
        <param name="context">
          <para><span data-ttu-id="f5f50-127">転送元または転送先に関するコンテキスト情報を格納する <see cref="T:System.Runtime.Serialization.StreamingContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f5f50-127">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> object that contains contextual information about the source or destination.</span></span> <span data-ttu-id="f5f50-128">Context パラメーターは将来使用するために予約されており、null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="f5f50-128">The context parameter is reserved for future use and can be null.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="f5f50-129">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-129">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-130">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />クラスを指定した情報、コンテキストおよびエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-130">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with specified info, context and error code.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricNotPrimaryException (string message, Exception inner, System.Fabric.FabricErrorCode errorCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner, valuetype System.Fabric.FabricErrorCode errorCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricNotPrimaryException.#ctor(System.String,System.Exception,System.Fabric.FabricErrorCode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception, errorCode As FabricErrorCode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricNotPrimaryException : string * Exception * System.Fabric.FabricErrorCode -&gt; System.Fabric.FabricNotPrimaryException" Usage="new System.Fabric.FabricNotPrimaryException (message, inner, errorCode)" />
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
          <para><span data-ttu-id="f5f50-131">例外の原因を説明するエラー メッセージ。</span><span class="sxs-lookup"><span data-stu-id="f5f50-131">The error message that explains the reason for the exception.</span></span></para>
        </param>
        <param name="inner">
          <para><span data-ttu-id="f5f50-132">内部例外が指定されていない場合、現在の例外の原因となった例外。</span><span class="sxs-lookup"><span data-stu-id="f5f50-132">The exception that is the cause of the current exception or null if no inner exception is specified.</span></span> <span data-ttu-id="f5f50-133"><see cref="T:System.Exception" />クラスは、内部例外についての詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="f5f50-133">The <see cref="T:System.Exception" /> class provides more details about the inner exception.</span></span></para>
        </param>
        <param name="errorCode">
          <para><span data-ttu-id="f5f50-134">例外に関連付けられているエラー コード。</span><span class="sxs-lookup"><span data-stu-id="f5f50-134">The error code associated with the exception.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5f50-135">新しいインスタンスを初期化<see cref="T:System.Fabric.FabricNotPrimaryException" />クラスを指定したエラー メッセージ、この例外と、指定されたエラー コードの原因となった内部例外への参照。</span><span class="sxs-lookup"><span data-stu-id="f5f50-135">Initializes a new instance of <see cref="T:System.Fabric.FabricNotPrimaryException" /> class with a specified error message, a reference to the inner exception that is the cause of this exception, and a specified error code.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>