<Type Name="RetryExponential" FullName="Microsoft.Azure.ServiceBus.RetryExponential">
  <TypeSignature Language="C#" Value="public sealed class RetryExponential : Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryExponential extends Microsoft.Azure.ServiceBus.RetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.RetryExponential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryExponential&#xA;Inherits RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryExponential = class&#xA;    inherit RetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.ServiceBus.RetryPolicy</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ebafc-101">RetryPolicy 実装が再試行間の遅延が交互の指数的に拡張されます。</span><span class="sxs-lookup"><span data-stu-id="ebafc-101">RetryPolicy implementation where the delay between retries will grow in a staggered exponential manner.</span></span>
            <span data-ttu-id="ebafc-102">DeltaBackOff (MaximumBackoff - MinimumBackoff) の関数である retryFactor を使用して計算されます RetryIntervals と MaximumRetryCount</span><span class="sxs-lookup"><span data-stu-id="ebafc-102">RetryIntervals will be computed using a retryFactor which is a function of deltaBackOff (MaximumBackoff - MinimumBackoff) and MaximumRetryCount</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryExponential (TimeSpan minimumBackoff, TimeSpan maximumBackoff, int maximumRetryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan minimumBackoff, valuetype System.TimeSpan maximumBackoff, int32 maximumRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryExponential.#ctor(System.TimeSpan,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimumBackoff As TimeSpan, maximumBackoff As TimeSpan, maximumRetryCount As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.ServiceBus.RetryExponential : TimeSpan * TimeSpan * int -&gt; Microsoft.Azure.ServiceBus.RetryExponential" Usage="new Microsoft.Azure.ServiceBus.RetryExponential (minimumBackoff, maximumBackoff, maximumRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumBackoff" Type="System.TimeSpan" />
        <Parameter Name="maximumRetryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minimumBackoff"><span data-ttu-id="ebafc-103">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-103">Minimum backoff interval.</span></span></param>
        <param name="maximumBackoff"><span data-ttu-id="ebafc-104">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-104">Maximum backoff interval.</span></span></param>
        <param name="maximumRetryCount"><span data-ttu-id="ebafc-105">最大再試行回数です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-105">Maximum retry count.</span></span></param>
        <summary>
            <span data-ttu-id="ebafc-106">新しい構成された RetryExponential 再試行ポリシー オブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="ebafc-106">Returns a new RetryExponential retry policy object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ebafc-107">取得または再試行関連付けバックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="ebafc-107">Gets or sets the backoff interval associated with the retry.</span></span>
            </summary>
        <value><span data-ttu-id="ebafc-108">再試行関連付けバックオフ間隔。</span><span class="sxs-lookup"><span data-stu-id="ebafc-108">The backoff interval associated with the retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MaximumBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaximumBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaximumBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MaximumBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ebafc-109">取得または最大バックオフ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="ebafc-109">Gets or sets the maximum backoff interval.</span></span>
            </summary>
        <value><span data-ttu-id="ebafc-110">最大バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-110">The maximum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ebafc-111">取得または許可されている再試行の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="ebafc-111">Gets or sets the maximum number of allowed retries.</span></span>
            </summary>
        <value><span data-ttu-id="ebafc-112">許可されている再試行の最大数。</span><span class="sxs-lookup"><span data-stu-id="ebafc-112">The maximum number of allowed retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimalBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan MinimalBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MinimalBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimalBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MinimalBackoff : TimeSpan" Usage="Microsoft.Azure.ServiceBus.RetryExponential.MinimalBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ebafc-113">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-113">Minimum backoff interval.</span></span>
            </summary>
        <value><span data-ttu-id="ebafc-114">最小バックオフ間隔です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-114">The minimum backoff interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected override bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.RetryExponential.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="override this.OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryExponential.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
        <param name="remainingTime"><span data-ttu-id="ebafc-115">タイムアウトになるまでの残り時間です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-115">The remaining time before the timeout expires.</span></span></param>
        <param name="currentRetryCount"><span data-ttu-id="ebafc-116">処理された回数です。</span><span class="sxs-lookup"><span data-stu-id="ebafc-116">The number of attempts that have been processed.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="ebafc-117">再試行の前に遅延時間の量。</span><span class="sxs-lookup"><span data-stu-id="ebafc-117">The amount of time to delay before retry.</span></span></param>
        <summary>
            <span data-ttu-id="ebafc-118">再試行を実行するかどうかに呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="ebafc-118">Called to see if a retry should be performed.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>