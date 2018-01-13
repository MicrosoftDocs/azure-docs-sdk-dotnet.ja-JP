<Type Name="ExceptionHandlingRetryResult" FullName="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult">
  <TypeSignature Language="C#" Value="public sealed class ExceptionHandlingRetryResult : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionHandlingRetryResult extends Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionHandlingRetryResult&#xA;Inherits ExceptionHandlingResult" />
  <TypeSignature Language="F#" Value="type ExceptionHandlingRetryResult = class&#xA;    inherit ExceptionHandlingResult" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="28fd6-101">クライアントからサービスへの要求を再試行できる場合は、結果を処理する例外を示す</span><span class="sxs-lookup"><span data-stu-id="28fd6-101">Specifies the exception handling result when the request from client to service can be retried</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retrySettings, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="28fd6-102">この例外は、再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-102">The exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="28fd6-103">一時的な例外が再試行可能なことを示します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-103">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="28fd6-104">一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-104">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="28fd6-105">非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-105">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retrySettings"><span data-ttu-id="28fd6-106">再試行する前に待機する間隔を retrySettings でにわかっています。</span><span class="sxs-lookup"><span data-stu-id="28fd6-106">The retrySettings from which the interval to wait before retrying is figured out.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="28fd6-107">最大回数 exceptionId パラメーターによって識別される例外を再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-107">The maximum number of times the exception identified by the exceptionId parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="28fd6-108">指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-108">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (Exception exception, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.Exception,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : Exception * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exception, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="28fd6-109">この例外は、再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-109">The exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="28fd6-110">一時的な例外が再試行可能なことを示します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-110">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="28fd6-111">一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-111">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="28fd6-112">非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-112">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retryDelay"><span data-ttu-id="28fd6-113">再試行する前に待機する間隔</span><span class="sxs-lookup"><span data-stu-id="28fd6-113">The interval to wait before retrying</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="28fd6-114">例外パラメーターで指定された例外を再試行する必要がありますの最大回数。</span><span class="sxs-lookup"><span data-stu-id="28fd6-114">The maximum number of times the exception given in the exception parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="28fd6-115">指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-115">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionHandlingRetryResult (string exceptionId, bool isTransient, TimeSpan retryDelay, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exceptionId, bool isTransient, valuetype System.TimeSpan retryDelay, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.#ctor(System.String,System.Boolean,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exceptionId As String, isTransient As Boolean, retryDelay As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult : string * bool * TimeSpan * int -&gt; Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" Usage="new Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult (exceptionId, isTransient, retryDelay, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exceptionId" Type="System.String" />
        <Parameter Name="isTransient" Type="System.Boolean" />
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="exceptionId"><span data-ttu-id="28fd6-116">再試行する必要がある例外の識別子です。</span><span class="sxs-lookup"><span data-stu-id="28fd6-116">An identifier for the exception that needs to be retried.</span></span></param>
        <param name="isTransient">
            <span data-ttu-id="28fd6-117">一時的な例外が再試行可能なことを示します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-117">Indicates if this is a transient retriable exception.</span></span>
            <span data-ttu-id="28fd6-118">一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-118">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="28fd6-119">非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-119">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </param>
        <param name="retryDelay"><span data-ttu-id="28fd6-120">再試行する前に待機する間隔</span><span class="sxs-lookup"><span data-stu-id="28fd6-120">The interval to wait before retrying</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="28fd6-121">最大回数 exceptionId パラメーターによって識別される例外を再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-121">The maximum number of times the exception identified by the exceptionId parameter needs to be retried for.</span></span></param>
        <summary>
            <span data-ttu-id="28fd6-122">指定した引数を使用して ExceptionHandlingRetryResult をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-122">Instantiates the ExceptionHandlingRetryResult using the given arguments.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28fd6-123">例外の種類を一意に識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="28fd6-123">String that uniquely identifies the exception type.</span></span>
            </summary>
        <value>
            <span data-ttu-id="28fd6-124">この例外の一意の id。</span><span class="sxs-lookup"><span data-stu-id="28fd6-124">Unique id for this exception.</span></span> <span data-ttu-id="28fd6-125">この id は、この例外は、再試行回数の追跡に使用します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-125">This id is used to keep track of the number of times this exception is retried</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28fd6-126">一時的な再試行可能な例外はクライアントからサービスへの通信チャネルがまだ存在します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-126">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="28fd6-127">非一時的な再試行可能な例外が、もう一度は再試行する前に、サービス エンドポイントを解決する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-127">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </summary>
        <value>
            <span data-ttu-id="28fd6-128">true は、一時的な例外が再試行可能であることを示します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-128">true indicates that this is a transient retriable exception.</span></span>
            <span data-ttu-id="28fd6-129">false は、非一時的な例外が再試行可能であることを示します。</span><span class="sxs-lookup"><span data-stu-id="28fd6-129">false indicates that this is a non transient retriable exception.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28fd6-130">最大回数だけこの種類の例外与える前に再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-130">Maximum number of times this exception type needs to be retried before giving up.</span></span>
            <span data-ttu-id="28fd6-131">既定値は整数です。MaxValue</span><span class="sxs-lookup"><span data-stu-id="28fd6-131">The default value is int.MaxValue</span></span>
            </summary>
        <value><span data-ttu-id="28fd6-132">最大再試行回数</span><span class="sxs-lookup"><span data-stu-id="28fd6-132">Max retry count</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="28fd6-133">操作は、この遅延後に再試行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="28fd6-133">The operation should be retried after this delay.</span></span>
            </summary>
        <value><span data-ttu-id="28fd6-134">操作の再試行するまでの遅延時間</span><span class="sxs-lookup"><span data-stu-id="28fd6-134">Time delay after which the operation should be retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>