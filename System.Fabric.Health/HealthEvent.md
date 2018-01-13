<Type Name="HealthEvent" FullName="System.Fabric.Health.HealthEvent">
  <TypeSignature Language="C#" Value="public sealed class HealthEvent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthEvent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthEvent" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthEvent" />
  <TypeSignature Language="F#" Value="type HealthEvent = class" />
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
      <para><span data-ttu-id="3e851-101">ヘルス マネージャーによって追加された追加のメタデータを持つクラスター、アプリケーション ノードなどの正常性エンティティで報告される正常性の情報を表します。</span><span class="sxs-lookup"><span data-stu-id="3e851-101">Represents health information reported on a health entity, such as cluster, application or node, with additional metadata added by the Health Manager.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="3e851-102">正常性イベントがなどの正常性クエリによって返される<see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-102">Health events are returned by health queries such as <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span></span>
            <span data-ttu-id="3e851-103">含まれている<see cref="T:System.Fabric.Health.HealthInformation" />で正常性マネージャーに送信される、<see cref="T:System.Fabric.Health.HealthReport" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-103">They contain <see cref="T:System.Fabric.Health.HealthInformation" /> sent to Health Manager in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthInformation">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthInformation HealthInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthInformation HealthInformation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthInformation As HealthInformation" />
      <MemberSignature Language="F#" Value="member this.HealthInformation : System.Fabric.Health.HealthInformation" Usage="System.Fabric.Health.HealthEvent.HealthInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-104">正常性ストアに送信された正常性情報の取得、<see cref="T:System.Fabric.Health.HealthReport" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-104">Gets the health information that was sent to health store in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-105">正常性ストアに送信された正常性情報を<see cref="T:System.Fabric.Health.HealthReport" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-105">The health information that was sent to health store in a <see cref="T:System.Fabric.Health.HealthReport" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsExpired">
      <MemberSignature Language="C#" Value="public bool IsExpired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.IsExpired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsExpired : bool" Usage="System.Fabric.Health.HealthEvent.IsExpired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-106">正常性イベントの有効期限が切れているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e851-106">Gets a value that indicates whether the health event has expired.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="3e851-107"><languageKeyword>true</languageKeyword>場合は、正常性イベントの有効期限が切れました。<languageKeyword>false</languageKeyword>正常性イベントが、時に期限が切れていない場合、正常性ストアがクエリを評価します。</span><span class="sxs-lookup"><span data-stu-id="3e851-107"><languageKeyword>true</languageKeyword> if the health event has expired; <languageKeyword>false</languageKeyword> if the health event was not expired at the time the health store evaluated the query.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3e851-108">イベントを期限切れにできるのは、RemoveWhenExpired が false の場合のみです。</span><span class="sxs-lookup"><span data-stu-id="3e851-108">An event can be expired only if RemoveWhenExpired is false.</span></span>
            <span data-ttu-id="3e851-109">それ以外の場合、イベントはクエリによって返されずに、ストアから削除されます。</span><span class="sxs-lookup"><span data-stu-id="3e851-109">Otherwise, the event is not returned by query and is removed from the store.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastErrorTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastErrorTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastErrorTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastErrorTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastErrorTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-110">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Error" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-110">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Error" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span> <span data-ttu-id="3e851-111">定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</span><span class="sxs-lookup"><span data-stu-id="3e851-111">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="3e851-112">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Error" />、別の状態に遷移する前にします。</span><span class="sxs-lookup"><span data-stu-id="3e851-112">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Error" />, before transitioning to a different state.</span></span> <span data-ttu-id="3e851-113">場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Error" />System.DateTime.FromFileTimeUtc(0) になります。</span><span class="sxs-lookup"><span data-stu-id="3e851-113">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Error" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-114">返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-114">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3e851-115">遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。</span><span class="sxs-lookup"><span data-stu-id="3e851-115">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="3e851-116">スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。</span><span class="sxs-lookup"><span data-stu-id="3e851-116">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="3e851-117">などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></span><span class="sxs-lookup"><span data-stu-id="3e851-117">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.LastModifiedUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-118">日付と時刻の正常性ストアによって、正常性レポートの最終変更日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e851-118">Gets the date and time when the health report was last modified by the health store.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-119">日付と時刻の正常性ストアによって、正常性レポートの最終変更日時。</span><span class="sxs-lookup"><span data-stu-id="3e851-119">The date and time when the health report was last modified by the health store.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOkTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastOkTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastOkTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOkTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastOkTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastOkTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-120">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-120">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span> <span data-ttu-id="3e851-121">定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</span><span class="sxs-lookup"><span data-stu-id="3e851-121">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="3e851-122">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Error" />または<see cref="F:System.Fabric.Health.HealthState.Warning" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Ok" />、別の状態に遷移する前にします。</span><span class="sxs-lookup"><span data-stu-id="3e851-122">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Error" /> or <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Ok" />, before transitioning to a different state.</span></span> <span data-ttu-id="3e851-123">場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Ok" />System.DateTime.FromFileTimeUtc(0) になります。</span><span class="sxs-lookup"><span data-stu-id="3e851-123">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Ok" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-124">返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Ok" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-124">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Ok" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3e851-125">遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。</span><span class="sxs-lookup"><span data-stu-id="3e851-125">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="3e851-126">スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。</span><span class="sxs-lookup"><span data-stu-id="3e851-126">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="3e851-127">などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></span><span class="sxs-lookup"><span data-stu-id="3e851-127">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastWarningTransitionAt">
      <MemberSignature Language="C#" Value="public DateTime LastWarningTransitionAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastWarningTransitionAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastWarningTransitionAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastWarningTransitionAt : DateTime" Usage="System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-128">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Warning" />で報告される正常性レポートが最初の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-128">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Warning" />, returns the time at which the health report was first reported with <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span> <span data-ttu-id="3e851-129">定期的なレポートでは、同じ状態を持つ多数のレポートが生成された可能性がします。</span><span class="sxs-lookup"><span data-stu-id="3e851-129">For periodic reporting, many reports with the same state may have been generated.</span></span></para>
          <para><span data-ttu-id="3e851-130">場合、現在<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />は<see cref="F:System.Fabric.Health.HealthState.Ok" />または<see cref="F:System.Fabric.Health.HealthState.Error" />、するヘルス状態が前回の時刻を返します<see cref="F:System.Fabric.Health.HealthState.Warning" />、別の状態に遷移する前にします。</span><span class="sxs-lookup"><span data-stu-id="3e851-130">If the current <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> is <see cref="F:System.Fabric.Health.HealthState.Ok" /> or <see cref="F:System.Fabric.Health.HealthState.Error" />, returns the time at which the health state was last in <see cref="F:System.Fabric.Health.HealthState.Warning" />, before transitioning to a different state.</span></span> <span data-ttu-id="3e851-131">場合、<see cref="P:System.Fabric.Health.HealthInformation.HealthState" />されていない<see cref="F:System.Fabric.Health.HealthState.Warning" />System.DateTime.FromFileTimeUtc(0) になります。</span><span class="sxs-lookup"><span data-stu-id="3e851-131">If the <see cref="P:System.Fabric.Health.HealthInformation.HealthState" /> has never been <see cref="F:System.Fabric.Health.HealthState.Warning" />, the value will be System.DateTime.FromFileTimeUtc(0).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-132">返します<see cref="T:System.DateTime" />関連する遷移時 (UTC) の最後を表す<see cref="F:System.Fabric.Health.HealthState.Warning" />です。</span><span class="sxs-lookup"><span data-stu-id="3e851-132">Returns <see cref="T:System.DateTime" /> representing the last transition time (UTC) involving <see cref="F:System.Fabric.Health.HealthState.Warning" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="3e851-133">遷移フィールド<see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />、 <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />、<see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" />状態遷移イベントの正常性の履歴を提供します。</span><span class="sxs-lookup"><span data-stu-id="3e851-133">The transition fields, <see cref="P:System.Fabric.Health.HealthEvent.LastOkTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastWarningTransitionAt" />, <see cref="P:System.Fabric.Health.HealthEvent.LastErrorTransitionAt" /> give the history of the health state transitions for the event.</span></span>
            <span data-ttu-id="3e851-134">スマートなアラートや「履歴」の正常性イベントに関する情報を使用できます。</span><span class="sxs-lookup"><span data-stu-id="3e851-134">They can be used for smarter alerts or "historical" health event information.</span></span> <span data-ttu-id="3e851-135">などのシナリオを有効にする: <list type="bullet"> <item><para>プロパティに警告またはエラーを X 分以上になったときにアラートを生成します。一時的な状況でアラートを回避できます。正常性状態が 5 分以上の警告された場合、アラートの変換など、(HealthState 警告および -LastWarningTransitionTime を = = &gt; 5 分).</para></item> <item><para>アラートが最後に変更する条件のみに X 分間です。レポートが既に場合に発生したエラー、指定した時間の前に、それが既にシグナル以前ために無視できます。</para> </item> <item><para>場合は、プロパティは、警告およびエラーの切り替えは、どのくらいの期間が経過している問題のある (つまり問題あり) を決定します。プロパティは、5 分以上の正常なされていない場合、アラートの変換など、(HealthState! = Ok と -LastOkTransitionTime &gt; 5 分) です。</para></item></list></span><span class="sxs-lookup"><span data-stu-id="3e851-135">They enable scenarios such as: <list type="bullet"><item><para>Alert when a property has been at warning/error for more than X minutes. This avoids alerts on temporary conditions. For example, an alert if the health state has been warning for more than five minutes can be translated into (HealthState == Warning and Now - LastWarningTransitionTime &gt; 5 minutes).</para></item><item><para>Alert only on conditions that have changed in the last X minutes. If a report was already at error before the specified time, it can be ignored because it was already signaled previously.</para></item><item><para>If a property is toggling between warning and error, determine how long it has been unhealthy (i.e. not OK). For example, an alert if the property hasn't been healthy for more than five minutes can be translated into (HealthState != Ok and Now - LastOkTransitionTime &gt; 5 minutes).</para></item></list></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceUtcTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SourceUtcTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SourceUtcTimestamp" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceUtcTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SourceUtcTimestamp : DateTime" Usage="System.Fabric.Health.HealthEvent.SourceUtcTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3e851-136">正常性レポートをソースから送信されたときの日時を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e851-136">Gets the date and time when the health report was sent by the source.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="3e851-137">日付と、正常性レポートがソースによって送信された時刻。</span><span class="sxs-lookup"><span data-stu-id="3e851-137">The date and time when the health report was sent by the source.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthEvent.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthEvent.ToString " />
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
            <span data-ttu-id="3e851-138">正常性イベントの文字列表現を取得します。</span><span class="sxs-lookup"><span data-stu-id="3e851-138">Gets a string representation of the health event.</span></span>
            </summary>
        <returns><span data-ttu-id="3e851-139">正常性イベントの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="3e851-139">A string representation of the health event.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>