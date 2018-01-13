<Type Name="HealthInformation" FullName="System.Fabric.Health.HealthInformation">
  <TypeSignature Language="C#" Value="public sealed class HealthInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HealthInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.HealthInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HealthInformation" />
  <TypeSignature Language="F#" Value="type HealthInformation = class" />
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
      <para><span data-ttu-id="8840a-101">一般的な正常性レポートの情報を表します。</span><span class="sxs-lookup"><span data-stu-id="8840a-101">Represents common health report information.</span></span>
            <span data-ttu-id="8840a-102">正常性クエリによって返されるすべての正常性イベントと、正常性ストアに送信されるすべての正常性レポートで含まれます。</span><span class="sxs-lookup"><span data-stu-id="8840a-102">It is included in all health reports sent to the health store and in all health events returned by health queries.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HealthInformation (string sourceId, string property, System.Fabric.Health.HealthState healthState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sourceId, string property, valuetype System.Fabric.Health.HealthState healthState) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.#ctor(System.String,System.String,System.Fabric.Health.HealthState)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.HealthInformation : string * string * System.Fabric.Health.HealthState -&gt; System.Fabric.Health.HealthInformation" Usage="new System.Fabric.Health.HealthInformation (sourceId, property, healthState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="property" Type="System.String" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
      </Parameters>
      <Docs>
        <param name="sourceId">
          <para><span data-ttu-id="8840a-103">レポートのソース。</span><span class="sxs-lookup"><span data-stu-id="8840a-103">The source of the report.</span></span> <span data-ttu-id="8840a-104">できません<languageKeyword>null</languageKeyword>または空です。</span><span class="sxs-lookup"><span data-stu-id="8840a-104">It cannot be <languageKeyword>null</languageKeyword> or empty.</span></span>
            <span data-ttu-id="8840a-105">これは、「システム」、レポート作成システム コンポーネントの予約されたキーワードであるで開始できません。</span><span class="sxs-lookup"><span data-stu-id="8840a-105">It can't start with "System.", which is reserved keyword for system components reporting.</span></span></para>
        </param>
        <param name="property">
          <para><span data-ttu-id="8840a-106">レポートのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8840a-106">The property of the report.</span></span> <span data-ttu-id="8840a-107">できません<languageKeyword>null</languageKeyword>または空です。</span><span class="sxs-lookup"><span data-stu-id="8840a-107">It cannot be <languageKeyword>null</languageKeyword> or empty.</span></span></para>
        </param>
        <param name="healthState">
          <para><span data-ttu-id="8840a-108">レポートの正常性状態。</span><span class="sxs-lookup"><span data-stu-id="8840a-108">The health state of the report.</span></span> <span data-ttu-id="8840a-109">指定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8840a-109">Must be specified.</span></span>
            <span data-ttu-id="8840a-110">いずれかを指定する必要があります、 <see cref="F:System.Fabric.Health.HealthState.Error" />、<see cref="F:System.Fabric.Health.HealthState.Warning" />または<see cref="F:System.Fabric.Health.HealthState.Ok" />値。</span><span class="sxs-lookup"><span data-stu-id="8840a-110">Must be one of the <see cref="F:System.Fabric.Health.HealthState.Error" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> or <see cref="F:System.Fabric.Health.HealthState.Ok" /> values.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="8840a-111"><see cref="T:System.Fabric.Health.HealthInformation" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8840a-111">Initializes a new instance of the <see cref="T:System.Fabric.Health.HealthInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>
            <span data-ttu-id="8840a-112"><paramref name="property" />ことはできません<languageKeyword>null</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="8840a-112"><paramref name="property" /> cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="8840a-113">指定された<paramref name="healthState" />はサポートされていません。</span><span class="sxs-lookup"><span data-stu-id="8840a-113">Specified <paramref name="healthState" /> is not supported.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="AutoSequenceNumber">
      <MemberSignature Language="C#" Value="public const long AutoSequenceNumber = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 AutoSequenceNumber = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const AutoSequenceNumber As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable AutoSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.AutoSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="8840a-114">正常性のクライアントで有効なシーケンス番号に置き換え、自動シーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8840a-114">Auto sequence number, replaced with a valid sequence number by the health client.</span></span>
            </summary>
        <remarks><span data-ttu-id="8840a-115">正常性のクライアントは、自動のシーケンス番号を持つレポートを受信すると、有効なシーケンス番号を自動シーケンス番号に置き換えます。</span><span class="sxs-lookup"><span data-stu-id="8840a-115">When a health client receives a report with Auto sequence number, it replaces the auto sequence number with a valid sequence number.</span></span>
            <span data-ttu-id="8840a-116">同じプロセスで増加するシーケンス番号が保証されます。</span><span class="sxs-lookup"><span data-stu-id="8840a-116">The sequence number is guaranteed to increase in the same process.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="System.Fabric.Health.HealthInformation.Description" />
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
          <para><span data-ttu-id="8840a-117">取得またはヘルス情報の説明を設定します。</span><span class="sxs-lookup"><span data-stu-id="8840a-117">Gets or sets the description of the health information.</span></span> <span data-ttu-id="8840a-118">監視対象の条件に関する情報を追加するために使用フリー テキストを表します。</span><span class="sxs-lookup"><span data-stu-id="8840a-118">It represents free text used to add human readable information about the monitored condition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-119">A<see cref="T:System.String" />人間の判読できる形式で、ヘルス情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="8840a-119">A <see cref="T:System.String" /> which describes the health information in human readable form.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8840a-120">説明の文字列の最大文字数は 4096 文字です。</span><span class="sxs-lookup"><span data-stu-id="8840a-120">The maximum string length for the description is 4096 characters.</span></span>
            <span data-ttu-id="8840a-121">指定された文字列が長い場合は、これは自動的に切り捨てられます。</span><span class="sxs-lookup"><span data-stu-id="8840a-121">If the provided string is longer, it will be automatically truncated.</span></span>
            <span data-ttu-id="8840a-122">説明の最後の文字にマーカー「[ブラウズ]」が含まれて、切り捨てられた場合、文字列の合計サイズは 4096 文字です。</span><span class="sxs-lookup"><span data-stu-id="8840a-122">When truncated, the last characters of the description contain a marker "[Truncated]", and total string size is 4096 characters.</span></span>
            <span data-ttu-id="8840a-123">マーカーの存在でユーザーにその切り捨てことを示しますが発生しました。</span><span class="sxs-lookup"><span data-stu-id="8840a-123">The presence of the marker indicates to users that truncation occurred.</span></span>
            <span data-ttu-id="8840a-124">切り捨てられた場合、説明が元の文字列からより小さい 4096 文字に注意してください。</span><span class="sxs-lookup"><span data-stu-id="8840a-124">Note that when truncated, the description has less than 4096 characters from the original string.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Health.HealthInformation.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8840a-125">レポートに使用される監視対象の条件の重大度を示す正常性の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="8840a-125">Gets the health state that describes the severity of the monitored condition used for reporting.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-126">レポートに使用される監視対象の条件の重大度を示す正常性状態。</span><span class="sxs-lookup"><span data-stu-id="8840a-126">The health state that describes the severity of the monitored condition used for reporting.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="8840a-127">許容されるヘルス状態は<see cref="F:System.Fabric.Health.HealthState.Ok" />、<see cref="F:System.Fabric.Health.HealthState.Warning" />と<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="8840a-127">The accepted health states are <see cref="F:System.Fabric.Health.HealthState.Ok" />, <see cref="F:System.Fabric.Health.HealthState.Warning" /> and <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Property">
      <MemberSignature Language="C#" Value="public string Property { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Property" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.Property" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Property As String" />
      <MemberSignature Language="F#" Value="member this.Property : string" Usage="System.Fabric.Health.HealthInformation.Property" />
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
          <para><span data-ttu-id="8840a-128">正常性レポートのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="8840a-128">Gets the property of the health report.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-129">正常性レポートのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="8840a-129">The property of the health report.</span></span> <span data-ttu-id="8840a-130">と共に、 <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />、正常性に関する情報を一意に識別します。</span><span class="sxs-lookup"><span data-stu-id="8840a-130">Together with the <see cref="P:System.Fabric.Health.HealthInformation.SourceId" />, it uniquely identifies the health information.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="8840a-131">プロパティは、<see cref="T:System.String" />とレポーター柔軟にレポートをトリガーする状態条件を分類できるようにする固定列挙ではありません。</span><span class="sxs-lookup"><span data-stu-id="8840a-131">The property is a <see cref="T:System.String" /> and not a fixed enumeration to allow the reporter flexibility to categorize the state condition that triggers the report.</span></span>
            <span data-ttu-id="8840a-132">レポート機能など、 <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "AvailableDisk"プロパティをそのノードに報告できるように、"A"は、ノードで使用可能なディスクの状態を監視できます。</span><span class="sxs-lookup"><span data-stu-id="8840a-132">For example, a reporter with <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "A" can monitor the state of the available disk on a node, so it can report "AvailableDisk" property on that node.</span></span>
            <span data-ttu-id="8840a-133">レポート機能<see cref="P:System.Fabric.Health.HealthInformation.SourceId" />"B"は同じノードでプロパティ「接続」を報告できるようにノードの接続を監視できます。</span><span class="sxs-lookup"><span data-stu-id="8840a-133">A reporter with <see cref="P:System.Fabric.Health.HealthInformation.SourceId" /> "B" can monitor the node connectivity, so it can report a property "Connectivity" on the same node.</span></span>
            <span data-ttu-id="8840a-134">Health store にこれらのレポートは、指定したノードに対して個別の正常性イベントとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="8840a-134">In the health store, these reports are treated as separate health events for the specified node.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveWhenExpired">
      <MemberSignature Language="C#" Value="public bool RemoveWhenExpired { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoveWhenExpired" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveWhenExpired As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoveWhenExpired : bool with get, set" Usage="System.Fabric.Health.HealthInformation.RemoveWhenExpired" />
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
          <para><span data-ttu-id="8840a-135">取得または有効期限が切れるときに、レポートが health store から削除されたかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8840a-135">Gets or sets a value that indicates whether the report is removed from health store when it expires.</span></span> <span data-ttu-id="8840a-136">場合設定<languageKeyword>false</languageKeyword>レポートが経過したときにエラーとして扱われます。</span><span class="sxs-lookup"><span data-stu-id="8840a-136">If set to <languageKeyword>false</languageKeyword>, the report is treated as an error when expired.</span></span> <span data-ttu-id="8840a-137"><languageKeyword>false</languageKeyword>既定です。</span><span class="sxs-lookup"><span data-stu-id="8840a-137"><languageKeyword>false</languageKeyword> by default.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="8840a-138"><languageKeyword>true</languageKeyword>場合は、レポートは、それ以外の有効期限が切れたときに、正常性ストアから削除するか<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="8840a-138"><languageKeyword>true</languageKeyword> if the report should be removed from health store when expired; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8840a-139">クライアントを定期的にレポートをする必要があります設定が<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> <languageKeyword>false</languageKeyword> (既定値)。</span><span class="sxs-lookup"><span data-stu-id="8840a-139">When clients report periodically, they should set <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /><languageKeyword>false</languageKeyword> (default).</span></span>
            <span data-ttu-id="8840a-140">この方法は、レポート機能に問題があります。</span><span class="sxs-lookup"><span data-stu-id="8840a-140">This way, is the reporter has issues (eg.</span></span> <span data-ttu-id="8840a-141">デッドロック) および正常性レポートの有効期限し、エンティティとしてこのフラグが設定されるときに、エンティティがエラーで評価された、レポートできない<see cref="F:System.Fabric.Health.HealthState.Error" />です。</span><span class="sxs-lookup"><span data-stu-id="8840a-141">deadlock) and can't report, the entity is evaluated at error when the health report expires, and this will flag the entity as <see cref="F:System.Fabric.Health.HealthState.Error" />.</span></span>
            <span data-ttu-id="8840a-142">定期的なヘルスのクライアントは、正常性のクライアントがバッチ処理による遅延のために有効期限より高い頻度でレポートを送信する必要があります、ワイヤと正常性トランスポート遅延をメッセージが処理を格納します。</span><span class="sxs-lookup"><span data-stu-id="8840a-142">Periodic health clients should send reports with higher frequency than time to live to account for delays due to health client batching, message transport delays over the wire and health store processing.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64 with get, set" Usage="System.Fabric.Health.HealthInformation.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8840a-143">取得または正常性については、使用して、正常性ストアで陳腐化検出に関連付けられているシーケンス番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="8840a-143">Gets or sets the sequence number associated with the health information, used by the health store for staleness detection.</span></span>
            <span data-ttu-id="8840a-144"><see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" /> よりも大きい必要があります。</span><span class="sxs-lookup"><span data-stu-id="8840a-144">Must be greater than <see cref="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-145">正常性に関する情報に関連付けられているレポートのシーケンス番号。</span><span class="sxs-lookup"><span data-stu-id="8840a-145">The report sequence number associated with the health information.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8840a-146">正常性ストアは、レポートのシーケンス番号を使用して、古いレポートを検出できます。</span><span class="sxs-lookup"><span data-stu-id="8840a-146">The report sequence number is used by health store to detect stale reports.</span></span>
            </para>
          <para><span data-ttu-id="8840a-147">多くの場合のレポート機能は、シーケンス番号を指定する必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8840a-147">Most of the times, the reporter doesn't need to specify the sequence number.</span></span> <span data-ttu-id="8840a-148">既定値<see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" />代わりに使用されることができます。</span><span class="sxs-lookup"><span data-stu-id="8840a-148">The default value <see cref="F:System.Fabric.Health.HealthInformation.AutoSequenceNumber" /> can be used instead.</span></span> <span data-ttu-id="8840a-149">正常性のクライアントは、自動のシーケンス番号を持つレポートを受信すると、同じプロセスで増加することが保証される有効なシーケンス番号を生成します。</span><span class="sxs-lookup"><span data-stu-id="8840a-149">When a health client receives a report with Auto sequence number, it generates a valid sequence number, which is guaranteed to increase in the same process.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="System.Fabric.Health.HealthInformation.SourceId" />
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
          <para><span data-ttu-id="8840a-150">正常性に関する情報を生成したウォッチドッグ/システム コンポーネントを識別するソース名を取得します。</span><span class="sxs-lookup"><span data-stu-id="8840a-150">Gets the source name which identifies the watchdog/system component which generated the health information.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-151">レポートを作成するウォッチドッグ/システム コンポーネントを識別して、正常性レポートのソース。</span><span class="sxs-lookup"><span data-stu-id="8840a-151">The source of the health report, which identifies the watchdog/system component that creates the report.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.HealthInformation.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="System.Fabric.Health.HealthInformation.TimeToLive" />
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
          <para><span data-ttu-id="8840a-152">取得または正常性レポートが有効ではどのくらいの期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="8840a-152">Gets or sets how long the health report is valid.</span></span> <span data-ttu-id="8840a-153">TimeSpan.Zero より大きくなければなりません。</span><span class="sxs-lookup"><span data-stu-id="8840a-153">Must be larger than TimeSpan.Zero.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8840a-154">A<see cref="T:System.TimeSpan" />正常性レポートの有効期限の時刻を表すです。</span><span class="sxs-lookup"><span data-stu-id="8840a-154">A <see cref="T:System.TimeSpan" /> representing the time to live of the health report.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="8840a-155">クライアントは定期的に報告、ときに有効期限よりも頻度が高くなるとレポートを送信する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8840a-155">When clients report periodically, they should send reports with higher frequency than time to live.</span></span>
            <span data-ttu-id="8840a-156">クライアントは、遷移の報告場合、time to live を無限に設定できます。</span><span class="sxs-lookup"><span data-stu-id="8840a-156">If clients report on transition, they can set the time to live to infinite.</span></span></para>
          <para><span data-ttu-id="8840a-157">場合、ヘルス情報を含む正常性イベントが health store から削除するか、有効期限が経過すると、<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />は<languageKeyword>true</languageKeyword>場合に発生したエラー、評価または<see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" />は<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="8840a-157">When time to live expires, the health event that contains the health information is either removed from health store, if <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> is <languageKeyword>true</languageKeyword> or evaluated at error, if <see cref="P:System.Fabric.Health.HealthInformation.RemoveWhenExpired" /> is <languageKeyword>false</languageKeyword>.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="8840a-158">指定した値が無効でした。</span><span class="sxs-lookup"><span data-stu-id="8840a-158">The specified value was invalid.</span></span> <span data-ttu-id="8840a-159">0 より大きい、継続時間を指定してください。</span><span class="sxs-lookup"><span data-stu-id="8840a-159">Please provide a duration that is larger than 0.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.HealthInformation.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="healthInformation.ToString " />
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
            <span data-ttu-id="8840a-160">正常性に関する情報について説明する文字列を作成します。</span><span class="sxs-lookup"><span data-stu-id="8840a-160">Creates a string description of the health information.</span></span>
            </summary>
        <returns><span data-ttu-id="8840a-161">正常性についての説明の文字列を指定します。</span><span class="sxs-lookup"><span data-stu-id="8840a-161">String description of the health information.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownSequenceNumber">
      <MemberSignature Language="C#" Value="public const long UnknownSequenceNumber = -1;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 UnknownSequenceNumber = (-1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Const UnknownSequenceNumber As Long  = -1" />
      <MemberSignature Language="F#" Value="val mutable UnknownSequenceNumber : int64" Usage="System.Fabric.Health.HealthInformation.UnknownSequenceNumber" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>-1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="8840a-162">不明なシーケンス番号には、正常性ストアによっては許容されませんいる無効なシーケンス番号です。</span><span class="sxs-lookup"><span data-stu-id="8840a-162">Unknown sequence number, which is an invalid sequence number that is not accepted by the health store.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>