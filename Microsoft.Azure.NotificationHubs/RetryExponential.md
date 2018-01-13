<Type Name="RetryExponential" FullName="Microsoft.Azure.NotificationHubs.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.Azure.NotificationHubs.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="d13f1-101">指定された回数の再試行、ランダムな指数バックオフ方式を使用して、再試行の間隔を決定するを実行する再試行ポリシーを表します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-101">Represents a retry policy that performs a specified number of retries, using a randomized exponential backoff scheme to determine the interval between retries.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minBackoff, TimeSpan maxBackoff, TimeSpan deltaBackoff, TimeSpan terminationTimeBuffer, int maxRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minBackoff, valuetype System.TimeSpan maxBackoff, valuetype System.TimeSpan deltaBackoff, valuetype System.TimeSpan terminationTimeBuffer, int32 maxRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minBackoff As TimeSpan, maxBackoff As TimeSpan, deltaBackoff As TimeSpan, terminationTimeBuffer As TimeSpan, maxRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.RetryExponential : TimeSpan * TimeSpan * TimeSpan * TimeSpan * int -&gt; Microsoft.Azure.NotificationHubs.RetryExponential" Usage="new Microsoft.Azure.NotificationHubs.RetryExponential (minBackoff, maxBackoff, deltaBackoff, terminationTimeBuffer, maxRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxBackoff" Type="System.TimeSpan" />
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="terminationTimeBuffer" Type="System.TimeSpan" />
        <Parameter Name="maxRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minBackoff"><span data-ttu-id="d13f1-102">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="d13f1-102">The minimum backoff interval.</span></span></param>
        <param name="maxBackoff"><span data-ttu-id="d13f1-103">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="d13f1-103">The maximum backoff interval.</span></span></param>
        <param name="deltaBackoff"><span data-ttu-id="d13f1-104">再試行関連付けバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="d13f1-104">The backoff interval associated with the retry.</span></span></param>
        <param name="terminationTimeBuffer"><span data-ttu-id="d13f1-105">再試行に関連付けられる終了時間バッファー。</span><span class="sxs-lookup"><span data-stu-id="d13f1-105">The termination time buffer associated with the retry.</span></span></param>
        <param name="maxRetryCount"><span data-ttu-id="d13f1-106">許可されている再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="d13f1-106">The maximum number of allowed retry.</span></span></param>
        <summary><span data-ttu-id="d13f1-107"><see cref="T:Microsoft.Azure.NotificationHubs.RetryExponential" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.RetryExponential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.NotificationHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.NotificationHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; Microsoft.Azure.NotificationHubs.RetryPolicy" Usage="retryExponential.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="d13f1-108">このインスタンスの新しいコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-108">Creates a new copy of this instance.</span></span></summary>
        <returns><span data-ttu-id="d13f1-109">このインスタンスの作成の新しいコピーです。</span><span class="sxs-lookup"><span data-stu-id="d13f1-109">The created new copy of this instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d13f1-110">取得または再試行関連付けバックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-110">Gets or sets the backoff interval associated with the retry.</span></span></summary>
        <value><span data-ttu-id="d13f1-111">再試行関連付けバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="d13f1-111">The backoff interval associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected override bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsRetryableException : Exception -&gt; bool" Usage="retryExponential.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException"></param>
        <summary>
            <span data-ttu-id="d13f1-112">例外が [ok] を再試行するかどうかの判断します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-112">Determine if the exception is ok to retry</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d13f1-113">これには、false が返されます場合の再試行は行われません。</span><span class="sxs-lookup"><span data-stu-id="d13f1-113">if this return false, no retry will take place.</span></span>
            <span data-ttu-id="d13f1-114">それ以外の場合、OnShouldRetry() を再試行する場合の判別に使用します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-114">Otherwise we will use the OnShouldRetry() to determine when to retry.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d13f1-115">取得または最大バックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-115">Gets or sets the maximum backoff interval.</span></span></summary>
        <value><span data-ttu-id="d13f1-116">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="d13f1-116">The maximum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d13f1-117">取得または許可されている再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-117">Gets or sets the maximum number of allowed retry.</span></span></summary>
        <value><span data-ttu-id="d13f1-118">許可されている再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="d13f1-118">The maximum number of allowed retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d13f1-119">取得または最小バックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-119">Gets or sets the minimum backoff interval.</span></span></summary>
        <value><span data-ttu-id="d13f1-120">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="d13f1-120">The minimum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
        <param name="remainingTime"></param>
        <param name="currentRetryCount"></param>
        <param name="retryInterval"></param>
        <summary>
            <span data-ttu-id="d13f1-121">再試行ポリシーの再試行間隔を計算します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-121">Calculate the retry interval for the retry policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d13f1-122">このメソッドを返す場合は true、再試行は行わ retryInteval 時間アイドル状態のスレッドの後。</span><span class="sxs-lookup"><span data-stu-id="d13f1-122">If this method return true, retry will take place after thread idle for retryInteval amount of time.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminationTimeBuffer">
      <MemberSignature Language="C#" Value="public TimeSpan TerminationTimeBuffer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TerminationTimeBuffer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RetryExponential.TerminationTimeBuffer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TerminationTimeBuffer As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TerminationTimeBuffer : TimeSpan" Usage="Microsoft.Azure.NotificationHubs.RetryExponential.TerminationTimeBuffer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="d13f1-123">取得または再試行に関連付けられた終了時刻のバッファーを設定します。</span><span class="sxs-lookup"><span data-stu-id="d13f1-123">Gets or sets the termination time buffer associated with the retry.</span></span></summary>
        <value><span data-ttu-id="d13f1-124">再試行に関連付けられる終了時間バッファー。</span><span class="sxs-lookup"><span data-stu-id="d13f1-124">The termination time buffer associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>