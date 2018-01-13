<Type Name="ApplicationUpgradeProgress" FullName="System.Fabric.ApplicationUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ApplicationUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeProgress" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeProgress = class" />
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
      <para>
            <span data-ttu-id="5556f-101">アプリケーション インスタンスのアップグレード状態を表します。</span><span class="sxs-lookup"><span data-stu-id="5556f-101">Represents the upgrade status of the application instance.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-102">アップグレード対象としてアプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-102">Gets the name of the application to be upgraded.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-103">アップグレード対象としてアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="5556f-103">The name of the application to be upgraded.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-104">アップグレード対象として、アプリケーションの型名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-104">Gets the type name of the application to be upgraded.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-105">アップグレード対象として、アプリケーションの型名。</span><span class="sxs-lookup"><span data-stu-id="5556f-105">The type name of the application to be upgraded.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
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
          <para><span data-ttu-id="5556f-106">予測の所要時間は、現在のアップグレード ドメインの処理に費やされたを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-106">Gets the estimated elapsed time spent processing the current Upgrade Domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-107">推定経過時間では、現在のアップグレード ドメインの処理に費やされました。</span><span class="sxs-lookup"><span data-stu-id="5556f-107">The estimated elapsed time spent processing the current Upgrade Domain.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainProgress">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-108">現在のアップグレード ドメイン内のノードの詳細なアップグレードの進行状況を示します。</span><span class="sxs-lookup"><span data-stu-id="5556f-108">Gives the detailed upgrade progress for nodes in the current upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-109"><see cref="T:System.Fabric.UpgradeDomainProgress" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="5556f-109">Returns <see cref="T:System.Fabric.UpgradeDomainProgress" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureReason&gt; FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureReason&gt; FailureReason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="5556f-110">アップグレードが失敗した場合は、アップグレードの失敗のカテゴリを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-110">Gets the category of upgrade failure if the upgrade failed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-111">アップグレードの失敗のカテゴリ。</span><span class="sxs-lookup"><span data-stu-id="5556f-111">The category of upgrade failure.</span></span> <span data-ttu-id="5556f-112"><see cref="T:System.Fabric.UpgradeFailureReason" /></span><span class="sxs-lookup"><span data-stu-id="5556f-112"><see cref="T:System.Fabric.UpgradeFailureReason" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FailureTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FailureTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="5556f-113">アップグレードが失敗した時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-113">Gets the time at which the upgrade failed.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-114">時刻 (utc) のアップグレードが失敗しました。</span><span class="sxs-lookup"><span data-stu-id="5556f-114">The time at which the upgrade failed in UTC.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChangedUpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains (System.Fabric.ApplicationUpgradeProgress previousProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains(class System.Fabric.ApplicationUpgradeProgress previousProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChangedUpgradeDomains (previousProgress As ApplicationUpgradeProgress) As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.GetChangedUpgradeDomains : System.Fabric.ApplicationUpgradeProgress -&gt; System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="applicationUpgradeProgress.GetChangedUpgradeDomains previousProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="previousProgress">
          <para><span data-ttu-id="5556f-115">前の<see cref="T:System.Fabric.ApplicationUpgradeProgress" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="5556f-115">The previous <see cref="T:System.Fabric.ApplicationUpgradeProgress" /> object.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5556f-116">変更されたアップグレード ドメインのコレクションを返すヘルパー メソッドを指定します、<see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" />状態または<see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" />以降状態、<see cref="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" />メソッドが呼び出されました。</span><span class="sxs-lookup"><span data-stu-id="5556f-116">Specifies a helper method that returns a collection of upgrade domains that have changed to the <see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" /> state or the <see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" /> state since the <see cref="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" /> method was called.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5556f-117">アップグレード ドメインのコレクションを返すヘルパー メソッド。</span><span class="sxs-lookup"><span data-stu-id="5556f-117">A helper method that returns a collection of upgrade domains.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="5556f-118">アプリケーション名またはアプリケーションの種類の<paramref name="previousProgress" />パラメーターは、アプリケーションの名前またはこのオブジェクトのアプリケーションの種類と一致します。</span><span class="sxs-lookup"><span data-stu-id="5556f-118">The application name or the application type of the <paramref name="previousProgress" /> parameter does not match the application name or application type of this object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-119">このアップグレードの進行状況の次のアップグレード ドメインを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-119">Gets the next upgrade domain for this upgrade progress.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-120">このアップグレードの進行状況の次のアップグレード ドメイン。</span><span class="sxs-lookup"><span data-stu-id="5556f-120">The next upgrade domain for this upgrade progress.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollingUpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode RollingUpgradeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode RollingUpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RollingUpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradeMode : System.Fabric.RollingUpgradeMode" Usage="System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-121">このアップグレードの進行状況のローリング アップグレードのモードを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-121">Gets the rolling upgrade mode for this upgrade progress.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-122">このアップグレードの進行状況のローリング アップグレード モードです。</span><span class="sxs-lookup"><span data-stu-id="5556f-122">The rolling upgrade mode for this upgrade progress.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="5556f-123">アップグレードが開始された時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-123">Gets the time at which the upgrade started.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-124">Utc 形式でアップグレードが開始された時刻。</span><span class="sxs-lookup"><span data-stu-id="5556f-124">The time at which the upgrade started in UTC.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string TargetApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string" Usage="System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-125">アップグレード中、アプリケーションの種類のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-125">Gets the version of the application type being upgraded.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-126">アップグレード中、アプリケーションの種類のバージョン。</span><span class="sxs-lookup"><span data-stu-id="5556f-126">The version of the application type being upgraded.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationUpgradeProgress.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5556f-127">アプリケーション アップグレードの進行状況の文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-127">Gets a string representation of the application upgrade progress.</span></span>
            </summary>
        <returns><span data-ttu-id="5556f-128"><see cref="T:System.Fabric.ApplicationUpgradeProgress" /> の文字列形式。</span><span class="sxs-lookup"><span data-stu-id="5556f-128">A string representation of the <see cref="T:System.Fabric.ApplicationUpgradeProgress" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-129">データとアプリケーションの正常性を評価する正常性マネージャーによって使用されるアルゴリズムを記述する評価を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-129">Gets the evaluations which describe the data and the algorithm used by health manager to evaluate the application health.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-130">データとアプリケーションの正常性を評価する正常性マネージャーによって使用されるアルゴリズムを記述する評価します。</span><span class="sxs-lookup"><span data-stu-id="5556f-130">The evaluations which describe the data and the algorithm used by health manager to evaluate the application health.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDescription As ApplicationUpgradeDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : System.Fabric.Description.ApplicationUpgradeDescription" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationUpgradeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-131">現在のアップグレードの動作を記述するパラメーターを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-131">Gets the parameters that describe the behavior of the current upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-132">現在のアップグレードの動作を記述するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5556f-132">The parameters that describe the behavior of the current upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="5556f-133">アップグレードに失敗した時点で、システムがどのようなアクションを実行しているがの構造化された情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-133">Gets structured information about what actions were being performed by the system at the moment of upgrade failure.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-134">アップグレード ドメインの進行状況の詳細</span><span class="sxs-lookup"><span data-stu-id="5556f-134">The upgrade domain progress details.</span></span> <span data-ttu-id="5556f-135"><see cref="T:System.Fabric.UpgradeDomainProgress" /></span><span class="sxs-lookup"><span data-stu-id="5556f-135"><see cref="T:System.Fabric.UpgradeDomainProgress" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-136">このアプリケーションのアップグレードのアップグレード ドメインとアップグレードの状態のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-136">Gets the collection of upgrade domains and their upgrade status for this application upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-137">アップグレード ドメインと、このアプリケーションのアップグレードのアップグレードの状態のコレクション。</span><span class="sxs-lookup"><span data-stu-id="5556f-137">The collection of upgrade domains and their upgrade status for this application upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
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
          <para><span data-ttu-id="5556f-138">取得される予測所要時間は、現在の全体的な処理に費やされたをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="5556f-138">Gets the estimated elapsed time spent processing the current overall upgrade.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-139">推定経過時間では、現在の全体的なアップグレードの処理に費やされました。</span><span class="sxs-lookup"><span data-stu-id="5556f-139">The estimated elapsed time spent processing the current overall upgrade.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.ApplicationUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ApplicationUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As ApplicationUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.ApplicationUpgradeState" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-140">アプリケーションのアップグレード プロセスの全体的な状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-140">Gets the overall state of the application upgrade process.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-141">アプリケーションの全体的な状態では、プロセスをアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="5556f-141">The overall state of the application upgrade process.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeStatusDetails">
      <MemberSignature Language="C#" Value="public string UpgradeStatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeStatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeStatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeStatusDetails : string" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5556f-142">エラー メッセージを含むアップグレードの詳細なステータスを取得します。</span><span class="sxs-lookup"><span data-stu-id="5556f-142">Gets the status details of upgrade including failure message.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="5556f-143">エラー メッセージを含むアップグレードの詳細なステータス。</span><span class="sxs-lookup"><span data-stu-id="5556f-143">The status details of upgrade including failure message.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>