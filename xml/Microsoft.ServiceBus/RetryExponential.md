<Type Name="RetryExponential" FullName="Microsoft.ServiceBus.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="215b0-101">再試行ポリシーの実装を表します。</span><span class="sxs-lookup"><span data-stu-id="215b0-101">Represents an implementation of a retry policy.</span></span> <span data-ttu-id="215b0-102">メッセージング操作を再試行する必要が毎回の再試行の間の遅延はずらして、指数的に大きくなります。</span><span class="sxs-lookup"><span data-stu-id="215b0-102">For each time the messaging operation must be retried, the delay between retries grows in a staggered, exponential manner.</span></span></summary>
    <remarks><span data-ttu-id="215b0-103">再試行ポリシーでは、次の側面を許可: <list type="bullet"><item>ポリシーが常に優先、<seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" />ため、次の再試行間隔が操作に時間を超える場合、その再試行が終了されます</item>。<item>ときに、ポリシーがだけ再試行<seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" />は true</item> 。<item>ポリシーが遅延する必要があります、追加の 10 秒例外は、する場合によって、さらに、<seealso cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /></item></list></span><span class="sxs-lookup"><span data-stu-id="215b0-103">The retry policy will honor the following aspect: <list type="bullet"><item>the policy always honor the <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> so that retry will terminate if the next retry interval will exceed the operation time.</item><item>the policy only retry when <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> is true.</item><item>the policy should delay further by an additional 10 seconds if exception is a <seealso cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException" /></item></list></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RetryExponential : TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceBus.RetryExponential" Usage="new Microsoft.ServiceBus.RetryExponential (minBackoff, maxBackoff, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff"><span data-ttu-id="215b0-104">最小値は、待機する値が無効バックアップします。</span><span class="sxs-lookup"><span data-stu-id="215b0-104">The minimum back off value to wait.</span></span> <span data-ttu-id="215b0-105">この値はより大きいか等しいを作成できません<see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />、それ以外の場合の操作できない可能性がありますを再試行します。</span><span class="sxs-lookup"><span data-stu-id="215b0-105">This value must not be greater than or equal to <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="215b0-106">元に戻し値まで待機する最大です。</span><span class="sxs-lookup"><span data-stu-id="215b0-106">The maximum back off value to wait.</span></span> <span data-ttu-id="215b0-107">この値はより大きいか等しいを作成できません、<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />値、それ以外の場合の操作できないことがありますを再試行します。</span><span class="sxs-lookup"><span data-stu-id="215b0-107">This value must not be greater than or equal to the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> value, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="215b0-108">再試行ポリシー インスタンスは、再試行の時間間隔を計算する最大回数。</span><span class="sxs-lookup"><span data-stu-id="215b0-108">The maximum number of times the retry policy instance calculates the retry time interval.</span></span> <span data-ttu-id="215b0-109">再試行の回数は、この値を超えている場合、再試行が終了によって残りの操作時間がある場合でもです。</span><span class="sxs-lookup"><span data-stu-id="215b0-109">If the number of retries exceeds this value, the retry terminates, even if there is some remaining operation time.</span></span></param>
        <summary><span data-ttu-id="215b0-110"><see cref="T:Microsoft.ServiceBus.RetryExponential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="215b0-110">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RetryExponential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff, TimeSpan terminationTimeBuffer, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff, valuetype System.TimeSpan terminationTimeBuffer, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan, terminationTimeBuffer As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.RetryExponential : TimeSpan * TimeSpan * TimeSpan * TimeSpan * int -&gt; Microsoft.ServiceBus.RetryExponential" Usage="new Microsoft.ServiceBus.RetryExponential (minBackoff, maxBackoff, deltaBackoff, terminationTimeBuffer, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This constructor is obsolete. Please use the other constructor instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="terminationTimeBuffer" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff"><span data-ttu-id="215b0-111">最小値は、待機する値が無効バックアップします。</span><span class="sxs-lookup"><span data-stu-id="215b0-111">The minimum back off value to wait.</span></span> <span data-ttu-id="215b0-112">この値はより大きいか等しいを作成できません<see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />、それ以外の場合の操作できない可能性がありますを再試行します。</span><span class="sxs-lookup"><span data-stu-id="215b0-112">This value must not be greater than or equal to <see cref="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />, otherwise operations might not be able to retry.</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="215b0-113">元に戻し値まで待機する最大です。</span><span class="sxs-lookup"><span data-stu-id="215b0-113">The maximum back off value to wait.</span></span> <span data-ttu-id="215b0-114">この値はより大きいか等しいを作成できません、<see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" />値、それ以外の場合の操作できないことがありますを再試行します。</span><span class="sxs-lookup"><span data-stu-id="215b0-114">This value must not be greater than or equal to the <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> value, otherwise operations might not be able to retry.</span></span></param>
        <param name="deltaBackoff"><span data-ttu-id="215b0-115">再試行関連付けバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="215b0-115">The backoff interval associated with the retry.</span></span></param>
        <param name="terminationTimeBuffer"><span data-ttu-id="215b0-116">再試行に関連付けられる終了時間バッファー。</span><span class="sxs-lookup"><span data-stu-id="215b0-116">The termination time buffer associated with the retry.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="215b0-117">再試行ポリシー インスタンスは、再試行の時間間隔を計算する最大回数。</span><span class="sxs-lookup"><span data-stu-id="215b0-117">The maximum number of times the retry policy instance calculates the retry time interval.</span></span> <span data-ttu-id="215b0-118">再試行の回数は、この値を超えている場合、再試行が終了によって残りの操作時間がある場合でもです。</span><span class="sxs-lookup"><span data-stu-id="215b0-118">If the number of retries exceeds this value, the retry terminates, even if there is some remaining operation time.</span></span></param>
        <summary><span data-ttu-id="215b0-119"><see cref="T:Microsoft.ServiceBus.RetryExponential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="215b0-119">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.RetryExponential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.ServiceBus.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.ServiceBus.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.ServiceBus.RetryPolicy" Usage="retryExponential.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="215b0-120">このインスタンスの新しいコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="215b0-120">Creates a new copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="215b0-121">このインスタンスの作成の新しいコピーです。</span><span class="sxs-lookup"><span data-stu-id="215b0-121">The created new copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="215b0-122">取得または再試行関連付けバックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="215b0-122">Gets or sets the backoff interval associated with the retry.</span></span></summary>
        <value><span data-ttu-id="215b0-123">再試行関連付けバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="215b0-123">The backoff interval associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected override bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsRetryableException : Exception -&gt; bool" Usage="retryExponential.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="215b0-124">取得または最大バックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="215b0-124">Gets or sets the maximum backoff interval.</span></span></summary>
        <value><span data-ttu-id="215b0-125">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="215b0-125">The maximum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="215b0-126">取得または許可されている再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="215b0-126">Gets or sets the maximum number of allowed retries.</span></span></summary>
        <value><span data-ttu-id="215b0-127">許可されている再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="215b0-127">The maximum number of allowed retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="215b0-128">取得または最小バックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="215b0-128">Gets or sets the minimum backoff interval.</span></span></summary>
        <value><span data-ttu-id="215b0-129">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="215b0-129">The minimum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime">To be added.</param>
        <param name="currentRetryCount">To be added.</param>
        <param name="retryInterval">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminationTimeBuffer">
      <MemberSignature Language="C#" Value="public TimeSpan TerminationTimeBuffer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TerminationTimeBuffer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryExponential.TerminationTimeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TerminationTimeBuffer As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TerminationTimeBuffer : TimeSpan" Usage="Microsoft.ServiceBus.RetryExponential.TerminationTimeBuffer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="215b0-130">取得または再試行に関連付けられた終了時刻のバッファーを設定します。</span><span class="sxs-lookup"><span data-stu-id="215b0-130">Gets or sets the termination time buffer associated with the retry.</span></span></summary>
        <value><span data-ttu-id="215b0-131">再試行に関連付けられる終了時間バッファー。</span><span class="sxs-lookup"><span data-stu-id="215b0-131">The termination time buffer associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>