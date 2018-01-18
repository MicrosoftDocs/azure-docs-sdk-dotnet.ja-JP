<Type Name="ChaosParameters" FullName="System.Fabric.Chaos.DataStructures.ChaosParameters">
  <TypeSignature Language="C#" Value="public class ChaosParameters : System.Fabric.ByteSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit ChaosParameters extends System.Fabric.ByteSerializable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ChaosParameters&#xA;Inherits ByteSerializable" />
  <TypeSignature Language="F#" Value="type ChaosParameters = class&#xA;    inherit ByteSerializable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.ByteSerializable</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5870f-101">このクラスは、ChaosTestScenario を構成するすべてのテスト パラメーターを定義します。</span><span class="sxs-lookup"><span data-stu-id="5870f-101">This class defines all the test parameters to configure the ChaosTestScenario.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="5870f-102"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-102">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="5870f-103">ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-103">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (long maxConcurrentFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 maxConcurrentFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.Int64,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxConcurrentFaults As Long, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : int64 * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxConcurrentFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxConcurrentFaults"><span data-ttu-id="5870f-104">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-104">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-105">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="5870f-105">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="5870f-106">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-106">using 2 or 3 for this is recommended.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="5870f-107">時間の合計 Chaos を実行する必要があります。最大許容値は TimeSpan.FromSeconds (uint です。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-107">Total time Chaos should run; maximum allowed value is TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <summary>
          <para><span data-ttu-id="5870f-108"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-108">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="5870f-109">ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-109">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, Nullable&lt;TimeSpan&gt; timeToRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeToRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, Optional timeToRun As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * Nullable&lt;TimeSpan&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="5870f-110">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-110">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="5870f-111">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-111">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-112">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="5870f-112">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="5870f-113">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-113">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="5870f-114">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5870f-114">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="5870f-115">時間の合計 Chaos を実行する必要があります。最大許容値は TimeSpan.FromSeconds (uint です。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-115">Total time Chaos should run; maximum allowed value is TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <summary>
          <para><span data-ttu-id="5870f-116"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-116">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="5870f-117">ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-117">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="5870f-118">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-118">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="5870f-119">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-119">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-120">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="5870f-120">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="5870f-121">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-121">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="5870f-122">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5870f-122">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="5870f-123">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-123">After running for this much time, Chaos will stop; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="context"><span data-ttu-id="5870f-124">これは、(キー、値) のバッグのペア。</span><span class="sxs-lookup"><span data-stu-id="5870f-124">This is a bag of (key, value) pairs.</span></span> <span data-ttu-id="5870f-125">なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="5870f-125">This can be used to record detailed context about why Chaos is being started for example.</span></span></param>
        <summary>
          <para><span data-ttu-id="5870f-126"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-126">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <returns><span data-ttu-id="5870f-127">ChaosScenarioParameters として型指定された Chaos シナリオのパラメーターを格納するオブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-127">The object containing the Chaos scenario parameters, typed as ChaosScenarioParameters</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (maxClusterStabilizationTimeout As TimeSpan, maxConcurrentFaults As Long, enableMoveReplicaFaults As Boolean, timeToRun As TimeSpan, context As Dictionary(Of String, String), waitTimeBetweenIterations As TimeSpan, waitTimeBetweenFaults As TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="5870f-128">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-128">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="5870f-129">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-129">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-130">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="5870f-130">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="5870f-131">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-131">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="5870f-132">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5870f-132">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="5870f-133">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-133">After running for this much time, Chaos will stop; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="context"><span data-ttu-id="5870f-134">これは、(キー、値) のバッグのペア。</span><span class="sxs-lookup"><span data-stu-id="5870f-134">This is a bag of (key, value) pairs.</span></span> <span data-ttu-id="5870f-135">なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="5870f-135">This can be used to record detailed context about why Chaos is being started for example.</span></span></param>
        <param name="waitTimeBetweenIterations"><span data-ttu-id="5870f-136">これは、エラーを発生させることの 2 つの連続したイテレーション間の一時停止の量です。</span><span class="sxs-lookup"><span data-stu-id="5870f-136">This is the amount of pause between two consecutive iterations of fault inducing.</span></span> <span data-ttu-id="5870f-137">複数の一時停止、小時間の経過とともにエラーの比率は、TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-137">The more the pause, the less is the rate of faults over time; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="waitTimeBetweenFaults"><span data-ttu-id="5870f-138">これは、詳細、一時停止、--1 つのイテレーションで 2 つの連続する障害の間の一時停止の量は低くフォールトの同時実行TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-138">This is the amount of pause between two consecutive faults in a single iteration -- the more the pause, the less the concurrency of faults; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <summary>
          <para><span data-ttu-id="5870f-139"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-139">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChaosParameters (TimeSpan maxClusterStabilizationTimeout, long maxConcurrentFaults, bool enableMoveReplicaFaults, TimeSpan timeToRun, System.Collections.Generic.Dictionary&lt;string,string&gt; context, TimeSpan waitTimeBetweenIterations, TimeSpan waitTimeBetweenFaults, System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan maxClusterStabilizationTimeout, int64 maxConcurrentFaults, bool enableMoveReplicaFaults, valuetype System.TimeSpan timeToRun, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; context, valuetype System.TimeSpan waitTimeBetweenIterations, valuetype System.TimeSpan waitTimeBetweenFaults, class System.Fabric.Health.ClusterHealthPolicy clusterHealthPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.#ctor(System.TimeSpan,System.Int64,System.Boolean,System.TimeSpan,System.Collections.Generic.Dictionary{System.String,System.String},System.TimeSpan,System.TimeSpan,System.Fabric.Health.ClusterHealthPolicy)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Chaos.DataStructures.ChaosParameters : TimeSpan * int64 * bool * TimeSpan * System.Collections.Generic.Dictionary&lt;string, string&gt; * TimeSpan * TimeSpan * System.Fabric.Health.ClusterHealthPolicy -&gt; System.Fabric.Chaos.DataStructures.ChaosParameters" Usage="new System.Fabric.Chaos.DataStructures.ChaosParameters (maxClusterStabilizationTimeout, maxConcurrentFaults, enableMoveReplicaFaults, timeToRun, context, waitTimeBetweenIterations, waitTimeBetweenFaults, clusterHealthPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxClusterStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="maxConcurrentFaults" Type="System.Int64" />
        <Parameter Name="enableMoveReplicaFaults" Type="System.Boolean" />
        <Parameter Name="timeToRun" Type="System.TimeSpan" />
        <Parameter Name="context" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="waitTimeBetweenIterations" Type="System.TimeSpan" />
        <Parameter Name="waitTimeBetweenFaults" Type="System.TimeSpan" />
        <Parameter Name="clusterHealthPolicy" Type="System.Fabric.Health.ClusterHealthPolicy" />
      </Parameters>
      <Docs>
        <param name="maxClusterStabilizationTimeout"><span data-ttu-id="5870f-140">フォールトの反復処理後に安定してクラスター全体の待機する時間の最大量TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-140">The maximum amount of time to wait for the entire cluster to stabilize after a fault iteration; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="maxConcurrentFaults"><span data-ttu-id="5870f-141">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-141">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-142">高い同時実行性、比較的余裕のないしたがってより複雑な一連のバグの発見にエラーを発生させることでフェールオーバーします。</span><span class="sxs-lookup"><span data-stu-id="5870f-142">The higher the concurrency the more aggressive the failovers thus inducing more complex series of failures to uncover bugs.</span></span> <span data-ttu-id="5870f-143">この 2 または 3 を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-143">using 2 or 3 for this is recommended.</span></span></param>
        <param name="enableMoveReplicaFaults"><span data-ttu-id="5870f-144">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5870f-144">Enables or disables the MovePrimary and MoveSecondary faults.</span></span></param>
        <param name="timeToRun"><span data-ttu-id="5870f-145">実行後にこの時間がかかり、Chaos が停止します。TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-145">After running for this much time, Chaos will stop; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="context"><span data-ttu-id="5870f-146">これは、(キー、値) のバッグのペア。</span><span class="sxs-lookup"><span data-stu-id="5870f-146">This is a bag of (key, value) pairs.</span></span> <span data-ttu-id="5870f-147">なぜ Chaos が起動されている例に関する詳細なコンテキストを記録するために使用できます。</span><span class="sxs-lookup"><span data-stu-id="5870f-147">This can be used to record detailed context about why Chaos is being started for example.</span></span></param>
        <param name="waitTimeBetweenIterations"><span data-ttu-id="5870f-148">これは、エラーを発生させることの 2 つの連続したイテレーション間の一時停止の量です。</span><span class="sxs-lookup"><span data-stu-id="5870f-148">This is the amount of pause between two consecutive iterations of fault inducing.</span></span> <span data-ttu-id="5870f-149">複数の一時停止、小時間の経過とともにエラーの比率は、TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-149">The more the pause, the less is the rate of faults over time; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="waitTimeBetweenFaults"><span data-ttu-id="5870f-150">これは、詳細、一時停止、--1 つのイテレーションで 2 つの連続する障害の間の一時停止の量は低くフォールトの同時実行TimeSpan.FromSeconds (uint を超えることはできません。MaxValue)</span><span class="sxs-lookup"><span data-stu-id="5870f-150">This is the amount of pause between two consecutive faults in a single iteration -- the more the pause, the less the concurrency of faults; cannot exceed TimeSpan.FromSeconds(uint.MaxValue)</span></span></param>
        <param name="clusterHealthPolicy"><span data-ttu-id="5870f-151">どの程度健全クラスターがあります Chaos エラーを発生させることで移動するためを決定するクラスターの正常性ポリシー。</span><span class="sxs-lookup"><span data-stu-id="5870f-151">The cluster health policy that determines how healthy a cluster must be in order for Chaos to go on inducing faults.</span></span></param>
        <summary>
          <para><span data-ttu-id="5870f-152"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5870f-152">Initializes a new instance of the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy ClusterHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterHealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.ClusterHealthPolicy : System.Fabric.Health.ClusterHealthPolicy" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.ClusterHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-153">ClusterHealthPolicy では、次のエラーのセット上に移動する前に複雑さを保証するエンティティのヘルスの状態を判断します。</span><span class="sxs-lookup"><span data-stu-id="5870f-153">ClusterHealthPolicy determines the state of the health of the entities that Chaos ensures before going onto the next set of faults.</span></span> <span data-ttu-id="5870f-154">'ConsiderWarningAsError' を false に設定とは、healthState、クラスター内のエンティティがあるときに、次のエラーのセット上に移動 Chaos、できます (ただし、Chaos はスキップされます faultable エンティティを選択するときに警告内のエンティティ)、警告を = =。</span><span class="sxs-lookup"><span data-stu-id="5870f-154">Setting 'ConsiderWarningAsError' to false would let Chaos go onto the next set of faults while there are entities in the cluster with healthState == warning (although Chaos will skip the entities in warning while choosing faultable entities.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,string&gt; Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, string&gt; Context" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As Dictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Context : System.Collections.Generic.Dictionary&lt;string, string&gt;" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-155">バッグを取得します (キー、値) のペアの複雑さの開始中に渡されました。</span><span class="sxs-lookup"><span data-stu-id="5870f-155">Gets the bag of (key, value) pairs that was passed while starting Chaos</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableMoveReplicaFaults">
      <MemberSignature Language="C#" Value="public bool EnableMoveReplicaFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableMoveReplicaFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableMoveReplicaFaults As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableMoveReplicaFaults : bool with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.EnableMoveReplicaFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-156">有効またはエラー MovePrimary と MoveSecondary を無効にします。</span><span class="sxs-lookup"><span data-stu-id="5870f-156">Enables or disables the MovePrimary and MoveSecondary faults.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxClusterStabilizationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan MaxClusterStabilizationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxClusterStabilizationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxClusterStabilizationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxClusterStabilizationTimeout : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxClusterStabilizationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-157">テストが失敗する前に、エラーの後に安定してクラスターを待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="5870f-157">The maximum amount of time to wait for the cluster to stabilize after a fault before failing the test.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5870f-158">繰り返すたびに、ChaosTestScenario 待ちます多くてこの時間に異常な状態になるクラスターの数</span><span class="sxs-lookup"><span data-stu-id="5870f-158">After each iteration, the ChaosTestScenario waits for at most this amount of time for the cluster to become healthy</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrentFaults">
      <MemberSignature Language="C#" Value="public long MaxConcurrentFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxConcurrentFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrentFaults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrentFaults : int64 with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.MaxConcurrentFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-159">最下位のイテレーションにつき誘発される同時実行エラーの最大数は、1 をされています。</span><span class="sxs-lookup"><span data-stu-id="5870f-159">Maximum number of concurrent faults induced per iteration with the lowest being 1.</span></span> <span data-ttu-id="5870f-160">高い同時実行性、比較的余裕のないフェールオーバーです。したがってより複雑な連続する 2 または 3 を使用して、この - バグの発見に障害を誘導することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="5870f-160">The higer the concurrency the more aggressive the failovers; thus, inducing more complex series of failures to uncover bugs -- using 2 or 3 for this is recommended.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public override void Read (System.IO.BinaryReader br);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Read(class System.IO.BinaryReader br) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Read (br As BinaryReader)" />
      <MemberSignature Language="F#" Value="override this.Read : System.IO.BinaryReader -&gt; unit" Usage="chaosParameters.Read br" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="br" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="br"><span data-ttu-id="5870f-161">BinaryReader オブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-161">A BinaryReader object</span></span></param>
        <summary>
            <span data-ttu-id="5870f-162">バイト配列から、このオブジェクトの状態を読み取ります。</span><span class="sxs-lookup"><span data-stu-id="5870f-162">Reads the state of this object from byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.EndOfStreamException"><span data-ttu-id="5870f-163">ストリームの末尾に到達しました。</span><span class="sxs-lookup"><span data-stu-id="5870f-163">The end of the stream is reached.</span></span> </exception>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="5870f-164">I/O エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="5870f-164">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="TimeToRun">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToRun" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToRun As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToRun : TimeSpan" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.TimeToRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-165">終了する前に、シナリオを実行する時間の合計。</span><span class="sxs-lookup"><span data-stu-id="5870f-165">Total time for which the scenario will run before ending.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5870f-166">TimeSpan としてシナリオの最大実行時間を返します</span><span class="sxs-lookup"><span data-stu-id="5870f-166">Returns the max run-time of the scenario as TimeSpan</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="chaosParameters.ToString " />
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
            <span data-ttu-id="5870f-167">クラスの文字列表現を返します</span><span class="sxs-lookup"><span data-stu-id="5870f-167">Returns a string representation of the class</span></span>
            </summary>
        <returns><span data-ttu-id="5870f-168">String オブジェクト</span><span class="sxs-lookup"><span data-stu-id="5870f-168">A string object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenFaults">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenFaults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenFaults" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenFaults As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenFaults : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenFaults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-169">待機連続する障害の間の時間の上限: 値が大きいほど、低く (エラー) の同時実行します。</span><span class="sxs-lookup"><span data-stu-id="5870f-169">The maximum wait time between consecutive faults: the larger the value, the lower the concurrency (of faults).</span></span>
            </summary>
        <value>
            <span data-ttu-id="5870f-170">TimeSpan として 2 つの連続する障害の間の最大待機時間を返します。</span><span class="sxs-lookup"><span data-stu-id="5870f-170">Returns the maximum wait time between two consecutive faults as a TimeSpan</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTimeBetweenIterations">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTimeBetweenIterations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTimeBetweenIterations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTimeBetweenIterations As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTimeBetweenIterations : TimeSpan with get, set" Usage="System.Fabric.Chaos.DataStructures.ChaosParameters.WaitTimeBetweenIterations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5870f-171">この値によってバインドされるランダムな期間の 2 つのイテレーションまでの時間を待機します。</span><span class="sxs-lookup"><span data-stu-id="5870f-171">Wait time between two iterations for a random duration bound by this value.</span></span>
            </summary>
        <value>
            <span data-ttu-id="5870f-172">ChaosTestScenario の 2 つの連続したイテレーション間の時間の分離</span><span class="sxs-lookup"><span data-stu-id="5870f-172">The time-separation between two consecutive iterations of the ChaosTestScenario</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public override void Write (System.IO.BinaryWriter bw);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Write(class System.IO.BinaryWriter bw) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Chaos.DataStructures.ChaosParameters.Write(System.IO.BinaryWriter)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Write (bw As BinaryWriter)" />
      <MemberSignature Language="F#" Value="override this.Write : System.IO.BinaryWriter -&gt; unit" Usage="chaosParameters.Write bw" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bw" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="bw"><span data-ttu-id="5870f-173">BinaryWriter オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="5870f-173">A BinaryWriter object.</span></span></param>
        <summary>
            <span data-ttu-id="5870f-174">このオブジェクトの状態をバイト配列に書き込みます。</span><span class="sxs-lookup"><span data-stu-id="5870f-174">Writes the state of this object into a byte array.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.IO.IOException"><span data-ttu-id="5870f-175">I/O エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="5870f-175">An I/O error occurs.</span></span> </exception>
      </Docs>
    </Member>
  </Members>
</Type>