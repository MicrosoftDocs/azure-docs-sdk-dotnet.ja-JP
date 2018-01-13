<Type Name="RollingUpgradeMonitoringPolicy" FullName="System.Fabric.Description.RollingUpgradeMonitoringPolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeMonitoringPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMonitoringPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="0f998-101">ポリシーの監視のローリング アップグレードをカプセル化するクラスを表します。</span><span class="sxs-lookup"><span data-stu-id="0f998-101">Represents a class to encapsulate a rolling upgrade monitoring policy.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeMonitoringPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradeMonitoringPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-102"><see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0f998-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> class.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="0f998-103">初期化のプロパティを設定する、<see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />次の既定値を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="0f998-103">The initialization sets the properties of the <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> class with the following defaults.</span></span></para>
          <para><span data-ttu-id="0f998-104">プロパティ</span><span class="sxs-lookup"><span data-stu-id="0f998-104">Property</span></span></para>
          <para><span data-ttu-id="0f998-105">既定値</span><span class="sxs-lookup"><span data-stu-id="0f998-105">Default value</span></span></para>
          <list type="table">
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />
                </para>
                <para><span data-ttu-id="0f998-106">この値を変更する必要がありますまたは<see cref="T:System.ArgumentException" />アップグレードを開始する前にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0f998-106">This value must be changed or a <see cref="T:System.ArgumentException" /> will be thrown before the upgrade begins.</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.TimeSpan.Zero" />
                </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
                </para>
              </term>
              <description>
                <para>
                  <span data-ttu-id="0f998-107"><see cref="T:System.TimeSpan" />既定値は 120 秒の値。</span><span class="sxs-lookup"><span data-stu-id="0f998-107"><see cref="T:System.TimeSpan" /> value that defaults to 120 seconds.</span></span>
                    </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="0f998-108">600 秒</span><span class="sxs-lookup"><span data-stu-id="0f998-108">600 seconds</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="0f998-109">TimeSpan.FromSeconds (uint です。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="0f998-109">TimeSpan.FromSeconds(uint.MaxValue)</span></span></para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
                </para>
              </term>
              <description>
                <para><span data-ttu-id="0f998-110">TimeSpan.FromSeconds (uint です。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="0f998-110">TimeSpan.FromSeconds(uint.MaxValue)</span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeFailureAction FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.UpgradeFailureAction FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As UpgradeFailureAction" />
      <MemberSignature Language="F#" Value="member this.FailureAction : System.Fabric.UpgradeFailureAction with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-111">取得またはアップグレードに失敗した場合に実行するアクションを設定します。</span><span class="sxs-lookup"><span data-stu-id="0f998-111">Gets or sets the action to take if an upgrade fails.</span></span> <span data-ttu-id="0f998-112">既定では、 <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />です。</span><span class="sxs-lookup"><span data-stu-id="0f998-112">The default is <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-113">アップグレードに失敗した場合に実行するアクション。</span><span class="sxs-lookup"><span data-stu-id="0f998-113">The action to take if an upgrade fails.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-114"><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />プロパティの既定値から変更する必要があります<see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />または<see cref="T:System.ArgumentException" />アップグレードを開始する前にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0f998-114">The <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> property must be changed from the default of <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> or a <see cref="T:System.ArgumentException" /> will be thrown before the upgrade begins.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="0f998-115"><see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> プロパティが <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> に設定されている。</span><span class="sxs-lookup"><span data-stu-id="0f998-115">The <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> property is set to <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-116">で指定されたアクションの正常性チェックで障害が継続的に、アップグレードが失敗した時間の長さを設定を取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</span><span class="sxs-lookup"><span data-stu-id="0f998-116">Gets or sets the length of time that health checks can fail continuously before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-117">正常性チェックを時間の長さは、継続的に失敗することができます。</span><span class="sxs-lookup"><span data-stu-id="0f998-117">The length of time that health checks can fail continuously.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-118">既定値は 600 秒です。</span><span class="sxs-lookup"><span data-stu-id="0f998-118">The default is 600 seconds.</span></span> <span data-ttu-id="0f998-119">設定<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />に<see cref="F:System.TimeSpan.Zero" />1 つの正常性チェックのみになります。</span><span class="sxs-lookup"><span data-stu-id="0f998-119">Setting <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> to <see cref="F:System.TimeSpan.Zero" /> will result in only a single health check.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-120">取得または正常性は、次のアップグレード ドメインへのアップグレードを続行する前に継続的に渡す必要がありますをチェックする時間の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="0f998-120">Gets or sets the length of time that health checks must pass continuously before the upgrade proceeds to the next upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-121">正常性チェックを時間の長さは、継続的に渡す必要があります。</span><span class="sxs-lookup"><span data-stu-id="0f998-121">The length of time that health checks must pass continuously.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-122">既定値は 120 秒です。</span><span class="sxs-lookup"><span data-stu-id="0f998-122">The default is 120 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-123">取得または正常性チェックを実行する前に、アップグレード ドメインの完了後に待機する時間の長さを設定します。</span><span class="sxs-lookup"><span data-stu-id="0f998-123">Gets or sets the length of time to wait after completing an upgrade domain before performing health checks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-124">正常性チェックを実行する前に、アップグレード ドメインの完了後に待機する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="0f998-124">The length of time to wait after completing an upgrade domain before performing health checks.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-125">既定では、 <see cref="F:System.TimeSpan.Zero" />です。</span><span class="sxs-lookup"><span data-stu-id="0f998-125">The default is <see cref="F:System.TimeSpan.Zero" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-126">どのアップグレード ドメインの処理が、アップグレードは失敗しによって指定された操作の前に実行できる時間の長さを取得または<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</span><span class="sxs-lookup"><span data-stu-id="0f998-126">Gets or sets the length of time that the processing of any upgrade domain can take before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-127">どのアップグレード ドメインのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="0f998-127">The timeout for any upgrade domain.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-128">既定値は TimeSpan.FromSeconds (uint です。MaxValue)。</span><span class="sxs-lookup"><span data-stu-id="0f998-128">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0f998-129">取得または設定した場合、アップグレードの失敗およびによって指定された操作の前に、全体的なアップグレードが実行できる時間の長さ<see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />に発生します。</span><span class="sxs-lookup"><span data-stu-id="0f998-129">Gets or sets the length of time that the overall upgrade can take before the upgrade fails and the action specified by <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> occurs.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0f998-130">アップグレードのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="0f998-130">The upgrade timeout.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="0f998-131">既定値は TimeSpan.FromSeconds (uint です。MaxValue)。</span><span class="sxs-lookup"><span data-stu-id="0f998-131">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>