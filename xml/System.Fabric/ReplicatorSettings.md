<Type Name="ReplicatorSettings" FullName="System.Fabric.ReplicatorSettings">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReplicatorSettings = class" />
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
      <para><span data-ttu-id="088c0-101">により、ステートフルなレプリカを構成するのには<see cref="T:System.Fabric.FabricReplicator" />経由での作成時に<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />です。</span><span class="sxs-lookup"><span data-stu-id="088c0-101">Allows a stateful replica to configure the <see cref="T:System.Fabric.FabricReplicator" /> when creating it via <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-102"><see cref="T:System.Fabric.ReplicatorSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="088c0-102">Initializes a new instance of the <see cref="T:System.Fabric.ReplicatorSettings" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-103">取得または受信確認を送信する前に、操作を受信した後、レプリケーターが待機する時間を設定します。</span><span class="sxs-lookup"><span data-stu-id="088c0-103">Gets or sets the amount of time that the replicator waits after receiving an operation before sending back an acknowledgment.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-104">受信確認を送信する前に、操作を受信した後、レプリケーターが待機する時間にバックアップします。</span><span class="sxs-lookup"><span data-stu-id="088c0-104">The amount of time that the replicator waits after receiving an operation before sending back an acknowledgment.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-105">受信し、この期間内に受信確認は、その他の操作は、1 つのメッセージで送信、受信確認があります。</span><span class="sxs-lookup"><span data-stu-id="088c0-105">Other operations received and acknowledged during this time period will have their acknowledgments sent back in a single message.</span></span></para>
          <para><span data-ttu-id="088c0-106">増加、<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />値は、各レプリケーション操作の待機時間を減らしますが、レプリケーターのスループットが向上します。</span><span class="sxs-lookup"><span data-stu-id="088c0-106">Increasing the <see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> value decreases latency of individual replication operations but increases throughput of the replicator.</span></span></para>
          <para><span data-ttu-id="088c0-107">既定値は、0.05 秒 (50 ミリ秒)</span><span class="sxs-lookup"><span data-stu-id="088c0-107">Default value is 0.05 Seconds (50 milliseconds)</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-108">取得または設定のコピー操作キュー内の初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-108">Gets or sets the initial size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-109">内のコピー操作キューの初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-109">The initial size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-110">既定値は 64 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-110">The default value is 64.</span></span> <span data-ttu-id="088c0-111">このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="088c0-111">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-112">プライマリ レプリケーション操作キュー内の初期サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s の各単位をここでは、キューの操作の数。</span><span class="sxs-lookup"><span data-stu-id="088c0-112">Defines the initial size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.The unit here is the number of operations in the queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-113">プライマリ レプリケーション操作キュー内の初期サイズ<see cref="T:System.Fabric.FabricReplicator" /></span><span class="sxs-lookup"><span data-stu-id="088c0-113">The initial size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" /></span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-114">サービスのロールがプライマリである場合は、この設定は、複製物作成会社に固有</span><span class="sxs-lookup"><span data-stu-id="088c0-114">This setting is specific to the Replicator when the role of the service is Primary</span></span></para>
          <para><span data-ttu-id="088c0-115">既定値は 64 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-115">The default value is 64.</span></span>  <span data-ttu-id="088c0-116">このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="088c0-116">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-117">取得またはレプリケーション キューのサイズの初期サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="088c0-117">Gets or sets the initial size of the replication queue size.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-118">レプリケーション キューのサイズの初期サイズします。</span><span class="sxs-lookup"><span data-stu-id="088c0-118">The initial size of the replication queue size.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-119">セカンダリのレプリケーション操作キュー内の初期サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="088c0-119">Defines the initial size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-120">内のセカンダリのレプリケーション操作キューの初期サイズ<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-120">The initial size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span> <span data-ttu-id="088c0-121">単位をここでは、キューの操作の数</span><span class="sxs-lookup"><span data-stu-id="088c0-121">The unit here is the number of operations in the queue</span></span> </para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-122">サービスの役割がセカンダリ/アイドル状態の場合は、この設定は、複製物作成会社に固有</span><span class="sxs-lookup"><span data-stu-id="088c0-122">This setting is specific to the Replicator when the role of the service is Secondary/Idle</span></span></para>
          <para><span data-ttu-id="088c0-123">既定値は 64 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-123">The default value is 64.</span></span>  <span data-ttu-id="088c0-124">このパラメーターの値が 2 のべき乗でなければならないことに注意してください。</span><span class="sxs-lookup"><span data-stu-id="088c0-124">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicatorSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicatorSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.ReplicatorSettings" Usage="System.Fabric.ReplicatorSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para><span data-ttu-id="088c0-125">現在のコード パッケージのアクティベーション コンテキスト<see cref="T:System.Fabric.CodePackageActivationContext" /></span><span class="sxs-lookup"><span data-stu-id="088c0-125">The current code package activation context <see cref="T:System.Fabric.CodePackageActivationContext" /></span></span></para>
        </param>
        <param name="configPackageName">
          <para><span data-ttu-id="088c0-126">現在の構成パッケージ名</span><span class="sxs-lookup"><span data-stu-id="088c0-126">The current configuration package name</span></span></para>
        </param>
        <param name="sectionName">
          <para><span data-ttu-id="088c0-127">すべての複製物作成会社設定を定義する構成ファイル内のセクション</span><span class="sxs-lookup"><span data-stu-id="088c0-127">The section within the configuration file that defines all the replicator settings</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="088c0-128">読み込み、<see cref="T:System.Fabric.ReplicatorSettings" />サービス構成設定ファイルからのオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="088c0-128">Loads the <see cref="T:System.Fabric.ReplicatorSettings" /> object from the service configuration settings file.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="088c0-129">読み込まれた<see cref="T:System.Fabric.ReplicatorSettings" />サービス構成設定ファイルからオブジェクト</span><span class="sxs-lookup"><span data-stu-id="088c0-129">The loaded <see cref="T:System.Fabric.ReplicatorSettings" /> object from the service configuration settings file</span></span></para>
        </returns>
        <remarks>
          <para> <span data-ttu-id="088c0-130">サービスの構成フォルダー内の構成設定ファイル (settings.xml) には、通常を渡すために必要なすべての複製物作成会社設定が含まれています、<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクトを<see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="088c0-130">The configuration settings file (settings.xml) within the service configuration folder generally contains all the replicator settings that is needed to pass in the <see cref="T:System.Fabric.ReplicatorSettings" /> object to the <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> method.</span></span> <span data-ttu-id="088c0-131">通常、負担が settings.xml ファイルを読み取り、値を解析し、適切に構築するには、サービス作成者には、<see cref="T:System.Fabric.ReplicatorSettings" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="088c0-131">Typically, the onus is on the service author to read the settings.xml file, parse the values and appropriately construct the <see cref="T:System.Fabric.ReplicatorSettings" /> object.</span></span></para>
          <para><span data-ttu-id="088c0-132">現在のヘルパー メソッドを使用してサービスの作成者は、上記のプロセスをバイパスできます。</span><span class="sxs-lookup"><span data-stu-id="088c0-132">With the current helper method, the service author can bypass the above process.</span></span></para>
          <para><span data-ttu-id="088c0-133">サービスの構成を上記の解析中に自動的に実行する windows fabric で認識できる"settings.xml"で指定されるべきパラメーター名を次に示します。</span><span class="sxs-lookup"><span data-stu-id="088c0-133">The following are the parameter names that should be provided in the service configuration “settings.xml”, to be recognizable by windows fabric to perform the above parsing automatically:</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="088c0-134">BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />値 (秒)</span><span class="sxs-lookup"><span data-stu-id="088c0-134">BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-135">InitialCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-135">InitialCopyQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-136">MaxCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-136">MaxCopyQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-137">MaxReplicationMessageSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-137">MaxReplicationMessageSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-138">RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" />値 (秒)</span><span class="sxs-lookup"><span data-stu-id="088c0-138">RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-139">RequireServiceAck-<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></span><span class="sxs-lookup"><span data-stu-id="088c0-139">RequireServiceAck -<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-140">ReplicatorAddress または ReplicatorEndpoint – ReplicatorAddress IPort 形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="088c0-140">ReplicatorAddress or ReplicatorEndpoint – ReplicatorAddress should be of the form IPort.</span></span> <span data-ttu-id="088c0-141">サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></span><span class="sxs-lookup"><span data-stu-id="088c0-141">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-142">ReplicatorListenAddress または ReplicatorEndpoint – ReplicatorListenAddress IPort 形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="088c0-142">ReplicatorListenAddress or ReplicatorEndpoint – ReplicatorListenAddress should be of the form IPort.</span></span> <span data-ttu-id="088c0-143">サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></span><span class="sxs-lookup"><span data-stu-id="088c0-143">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-144">ReplicatorPublishAddress または ReplicatorEndpoint – ReplicatorPublishAddress IPort 形式でなければなりません。</span><span class="sxs-lookup"><span data-stu-id="088c0-144">ReplicatorPublishAddress or ReplicatorEndpoint – ReplicatorPublishAddress should be of the form IPort.</span></span> <span data-ttu-id="088c0-145">サービス マニフェストから ReplicatorEndpoint が有効なサービス エンドポイントのリソースを参照する必要があります。<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></span><span class="sxs-lookup"><span data-stu-id="088c0-145">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-146">SecondaryClearAcknowledgedOperations-<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></span><span class="sxs-lookup"><span data-stu-id="088c0-146">SecondaryClearAcknowledgedOperations -<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-147">PrimaryWaitForPendingQuorumsTimeout -<see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />値 (秒)</span><span class="sxs-lookup"><span data-stu-id="088c0-147">PrimaryWaitForPendingQuorumsTimeout - <see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-148">UseStreamFaultsAndEndOfStreamOperationAck-<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></span><span class="sxs-lookup"><span data-stu-id="088c0-148">UseStreamFaultsAndEndOfStreamOperationAck -<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-149">InitialPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-149">InitialPrimaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-150">InitialSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-150">InitialSecondaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-151">MaxPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-151">MaxPrimaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-152">MaxSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-152">MaxSecondaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-153">MaxPrimaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-153">MaxPrimaryReplicationQueueMemorySize -<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="088c0-154">MaxSecondaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></span><span class="sxs-lookup"><span data-stu-id="088c0-154">MaxSecondaryReplicationQueueMemorySize -<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-155">取得または設定、キューの最大サイズ、コピー操作の内部<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-155">Gets or sets the maximum size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-156">内のコピー操作キューの最大サイズ<see cref="T:System.Fabric.FabricReplicator" />、コピーが含まれています<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-156">The maximum size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-157">このキューのサイズに達した場合、セカンダリで、プライマリのコピーのキューに操作がバッファーされます。</span><span class="sxs-lookup"><span data-stu-id="088c0-157">If this queue size is reached at the secondary, operations will be buffered in the Primary’s copy queue.</span></span> <span data-ttu-id="088c0-158">かどうかには、そのキューを格納、し、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</span><span class="sxs-lookup"><span data-stu-id="088c0-158">If that queue also fills, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="088c0-159">既定値は 1024</span><span class="sxs-lookup"><span data-stu-id="088c0-159">The default value is 1024</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-160">内のプライマリ レプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="088c0-160">Defines the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-161">が必要です。</span><span class="sxs-lookup"><span data-stu-id="088c0-161">.</span></span> <span data-ttu-id="088c0-162">内のプライマリ レプリケーション操作キューの最大サイズを返します<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />単位をここでは、キューの仮想メモリの消費します。返します<see cref="T:System.Int64" />です。</span><span class="sxs-lookup"><span data-stu-id="088c0-162">Returns the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s The unit here is the virtual memory consumption of the queue .Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-163">この設定は、サービスのロールがプライマリにレプリケーターに固有です。</span><span class="sxs-lookup"><span data-stu-id="088c0-163">This setting is specific to the Replicator when the role of the service is Primary.</span></span> <span data-ttu-id="088c0-164">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-164">The default value is 0.</span></span> <span data-ttu-id="088c0-165">つまり、メモリの制限はありません。</span><span class="sxs-lookup"><span data-stu-id="088c0-165">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-166">内のプライマリ レプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="088c0-166">Defines the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-167">最大キューのサイズ、プライマリ レプリケーション操作の内部<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。</span><span class="sxs-lookup"><span data-stu-id="088c0-167">The maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span> <span data-ttu-id="088c0-168">単位をここでは、キュー内の操作の数です。</span><span class="sxs-lookup"><span data-stu-id="088c0-168">The unit here is the number of operations in the queue.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-169">このキューのサイズに達したかどうかは、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</span><span class="sxs-lookup"><span data-stu-id="088c0-169">If this queue size is reached, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="088c0-170">既定値は、このパラメーターの値は 1024 のメモが 2 の累乗にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="088c0-170">The default value is 1024 Note that values for this parameter must be a power of 2.</span></span></para>
          <para><span data-ttu-id="088c0-171">サービスのロールがプライマリである場合は、この設定は、複製物作成会社に固有</span><span class="sxs-lookup"><span data-stu-id="088c0-171">This setting is specific to the Replicator when the role of the service is Primary</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-172">取得またはレプリケーター経由で送信できるメッセージの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="088c0-172">Gets or sets the maximum size of a message that can be transmitted via the replicator.</span></span> <span data-ttu-id="088c0-173">メッセージをコピーして、コンテキストのメッセージをコピーするこれらレプリケーション メッセージが含まれます。</span><span class="sxs-lookup"><span data-stu-id="088c0-173">These include replication messages, copy messages and copy context messages.</span></span> <span data-ttu-id="088c0-174">表現の単位はバイトです。</span><span class="sxs-lookup"><span data-stu-id="088c0-174">The unit of representation is bytes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-175">レプリケーター経由で送信できるメッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="088c0-175">The maximum size of a message that can be transmitted via the replicator.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-176">既定値は 50 MB です。</span><span class="sxs-lookup"><span data-stu-id="088c0-176">The default value is 50MB</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-177">取得またはレプリケーション キューのメモリの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="088c0-177">Gets or sets the maximum size for the replication queue memory.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-178">レプリケーション キューのメモリの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="088c0-178">The maximum size for the replication queue memory.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-179">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-179">The default value is 0.</span></span> <span data-ttu-id="088c0-180">つまり、メモリの制限はありません。</span><span class="sxs-lookup"><span data-stu-id="088c0-180">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-181">取得またはレプリケーション キューの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="088c0-181">Gets or sets the maximum size for the replication queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-182">レプリケーション キューの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="088c0-182">the maximum size for the replication queue.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-183">内のセカンダリのレプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。</span><span class="sxs-lookup"><span data-stu-id="088c0-183">Defines the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-184">内のセカンダリのレプリケーション操作キューの最大サイズを返します<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s。</span><span class="sxs-lookup"><span data-stu-id="088c0-184">Returns the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span> <span data-ttu-id="088c0-185">単位をここでは、キューの仮想メモリの消費です。</span><span class="sxs-lookup"><span data-stu-id="088c0-185">The unit here is the virtual memory consumption of the queue.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-186">この設定は、サービスの役割がセカンダリ/アイドル状態の場合、レプリケーターに固有です。</span><span class="sxs-lookup"><span data-stu-id="088c0-186">This setting is specific to the Replicator when the role of the service is Secondary/Idle.</span></span> <span data-ttu-id="088c0-187">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-187">The default value is 0.</span></span> <span data-ttu-id="088c0-188">つまり、メモリの制限はありません。</span><span class="sxs-lookup"><span data-stu-id="088c0-188">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-189">内のセカンダリのレプリケーション操作キューの最大サイズを定義<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="088c0-189">Defines the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-190">内のセカンダリのレプリケーション操作キューの最大サイズ<see cref="T:System.Fabric.FabricReplicator" />、レプリケーションが含まれている<see cref="T:System.Fabric.IOperation" />追加されていないと、サービスによって処理されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-190">The maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span> <span data-ttu-id="088c0-191">単位をここでは、キューの操作の数</span><span class="sxs-lookup"><span data-stu-id="088c0-191">The unit here is the number of operations in the queue</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-192">このキューのサイズに達すると、プライマリのレプリケーション キューで操作がバッファーされます。</span><span class="sxs-lookup"><span data-stu-id="088c0-192">If this queue size is reached, operations will be buffered in the Primary’s replication queue.</span></span>  <span data-ttu-id="088c0-193">かどうかには、そのキューを格納、し、プライマリの表示が開始<see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" />例外。</span><span class="sxs-lookup"><span data-stu-id="088c0-193">If that queue also fills, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="088c0-194">既定値は、このパラメーターの値が 2048.Note が 2 の累乗にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="088c0-194">The default value is 2048.Note that values for this parameter must be a power of 2.</span></span></para>
          <para><span data-ttu-id="088c0-195">サービスの役割がセカンダリ/アイドル状態の場合は、この設定は、複製物作成会社に固有</span><span class="sxs-lookup"><span data-stu-id="088c0-195">This setting is specific to the Replicator when the role of the service is Secondary/Idle</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryWaitForPendingQuorumsTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryWaitForPendingQuorumsTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.PrimaryWaitForPendingQuorumsTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-196">保留中のレプリケーション操作を取り消すにつながる可能性のある再構成要求を処理する前に、保留中のレプリケーション操作の確認のクォーラムを受信するため、主にレプリケーターが待機する時間を定義します。</span><span class="sxs-lookup"><span data-stu-id="088c0-196">Defines how long the primary replicator waits for receiving a quorum of acknowledgments for any pending replication operations before processing a reconfiguration request, that could potentially result in ‘cancelling’ the pending replication operations.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-197">プライマリのレプリケーターが再構成を処理するプライマリ レプリケーターの要求がある場合に、保留中のレプリケーション操作に対して受信確認のクォーラムを受信するために待機する時間<see cref="T:System.TimeSpan" />です。</span><span class="sxs-lookup"><span data-stu-id="088c0-197">Amount of time the primary replicator waits for receiving a quorum of acknowledgments for any pending replication operations when there is a request for the primary replicator to process a reconfiguration <see cref="T:System.TimeSpan" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-198">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-198">The default value is 0.</span></span> <span data-ttu-id="088c0-199">これは、保留中のレプリケーション操作でのクォーラムを受信するために再構成いない待機したことを意味します。</span><span class="sxs-lookup"><span data-stu-id="088c0-199">This implies that reconfigurations aren’t waited upon for receiving quorum on the pending replication operations.</span></span> <span data-ttu-id="088c0-200">これは、再構成を早く完了するために役立ちます。</span><span class="sxs-lookup"><span data-stu-id="088c0-200">This helps in completing reconfigurations sooner.</span></span> <span data-ttu-id="088c0-201">フェールオーバーをプライマリに長い期間の暗黙的な低速の再構成にこのパラメーターの値が大きいが生じる可能性があることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="088c0-201">Note that larger values for this parameter could potentially result in slower reconfigurations, implying longer durations to fail-over a primary.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorAddress" />
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
          <para><span data-ttu-id="088c0-202">その他の複製物作成会社と通信するときにこの複製物作成会社が使用するアドレスを構成します。</span><span class="sxs-lookup"><span data-stu-id="088c0-202">Configures the address that this replicator will use when communicating with other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-203">その他の複製物作成会社と通信するときにこの複製物作成会社が使用するアドレス。</span><span class="sxs-lookup"><span data-stu-id="088c0-203">The address that this replicator will use when communicating with other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-204">書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。</span><span class="sxs-lookup"><span data-stu-id="088c0-204">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="088c0-205">既定値は、localhost:0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-205">The default value is localhost:0.</span></span> <span data-ttu-id="088c0-206">レプリケーターがコンテナーの内部実行されている場合は、セットアップをやり直す必要があります<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />と<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />です。</span><span class="sxs-lookup"><span data-stu-id="088c0-206">If replicator is running inside a container, you should try setting up <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /> and <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
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
          <para><span data-ttu-id="088c0-207">この複製物作成会社が他の複製物作成会社から情報を受信に使用するリッスン アドレスを構成します。</span><span class="sxs-lookup"><span data-stu-id="088c0-207">Configures the listen address that this replicator will use to receieve information from other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-208">この複製物作成会社が他の複製物作成会社から情報を受信に使用するリッスン アドレスです。</span><span class="sxs-lookup"><span data-stu-id="088c0-208">The listen address that this replicator will use to receive information from other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-209">書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。</span><span class="sxs-lookup"><span data-stu-id="088c0-209">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="088c0-210">既定値は、localhost:0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-210">The default value is localhost:0.</span></span> <span data-ttu-id="088c0-211">リッスン アドレスのホスト名から取得できます。<see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></span><span class="sxs-lookup"><span data-stu-id="088c0-211">hostname for listen address can be obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
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
          <para><span data-ttu-id="088c0-212">この複製物作成会社が他の複製物作成会社に情報を送信に使用する発行アドレスを構成します。</span><span class="sxs-lookup"><span data-stu-id="088c0-212">Configures the publish address that this replicator will use to send information to other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-213">この複製物作成会社が他の複製物作成会社に情報を送信に使用する発行アドレスです。</span><span class="sxs-lookup"><span data-stu-id="088c0-213">The publish address that this replicator will use to send information to other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-214">書式設定された文字列として"hostname:port"ホスト名が FQDN または IP アドレスを指定できます。</span><span class="sxs-lookup"><span data-stu-id="088c0-214">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="088c0-215">既定値は、localhost:0 です。</span><span class="sxs-lookup"><span data-stu-id="088c0-215">The default value is localhost:0.</span></span> <span data-ttu-id="088c0-216">発行アドレスのホスト名を取得できます。<see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></span><span class="sxs-lookup"><span data-stu-id="088c0-216">hostname for publish address can be obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireServiceAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireServiceAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireServiceAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireServiceAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireServiceAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-217">により、サービスを呼び出すオプティミスティックの受信確認要求することで非永続的なサービスの操作の<see cref="M:System.Fabric.IOperation.Acknowledge" />次の操作をポンプする前にします。</span><span class="sxs-lookup"><span data-stu-id="088c0-217">Prevents the optimistic acknowledgment of operations in non-persistent services by requiring that the service calls <see cref="M:System.Fabric.IOperation.Acknowledge" /> before it pumps the next operation.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="088c0-218"><languageKeyword>true</languageKeyword>場合、オプティミスティックの受信確認の非永続的なサービス操作のそれ以外の場合、 <languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="088c0-218"><languageKeyword>true</languageKeyword> if the optimistic acknowledgment of operations in non-persistent services;otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-219">明示的な受信確認を必要とする非永続的サービスは、レプリケーターによって操作のオプティミスティックの受信確認を防ぐために、True にこのプロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="088c0-219">Non-persistent services which require explicit acknowledgment can set this property to True in order to prevent optimistic acknowledgment of the operations by the Replicator.</span></span> <span data-ttu-id="088c0-220">この設定は、永続的なサービスの影響を与えません。</span><span class="sxs-lookup"><span data-stu-id="088c0-220">This setting has no effect for persistent services.</span></span> </para>
          <para><span data-ttu-id="088c0-221">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="088c0-221">The default value is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-222">定義しますが、どのくらいの期間<see cref="T:System.Fabric.FabricReplicator" />は、プライマリからのメッセージを受信したことを確認するセカンダリ セカンダリへのメッセージを送信後に待機します。</span><span class="sxs-lookup"><span data-stu-id="088c0-222">Defines how long the <see cref="T:System.Fabric.FabricReplicator" /> waits after it transmits a message from the primary to the secondary for the secondary to acknowledge that it has received the message.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-223">必要な時間、<see cref="T:System.Fabric.FabricReplicator" />は、プライマリからのメッセージを受信したことを確認するセカンダリ セカンダリへのメッセージを送信後に待機します。</span><span class="sxs-lookup"><span data-stu-id="088c0-223">The time needed the <see cref="T:System.Fabric.FabricReplicator" /> waits after it transmits a message from the primary to the secondary for the secondary to acknowledge that it has received the message.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-224">メッセージの受信が必ずしもメッセージが処理されたことです。</span><span class="sxs-lookup"><span data-stu-id="088c0-224">Receiving a message does not necessarily that the message has been processed.</span></span></para>
          <para><span data-ttu-id="088c0-225">このタイマーを超えた場合、メッセージが再送信されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-225">If this timer is exceeded, then the message is retransmitted.</span></span></para>
          <para><span data-ttu-id="088c0-226">既定値は、5 秒です。</span><span class="sxs-lookup"><span data-stu-id="088c0-226">The default value is 5 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-227">通常、セカンダリのレプリケーターに操作にできる catchup レプリカにプライマリに昇格の場合、キューに保持されます。</span><span class="sxs-lookup"><span data-stu-id="088c0-227">Typically, operations in the secondary replicator are kept in the queue to be able to catchup replicas if it is promoted to a primary.</span></span> <span data-ttu-id="088c0-228">このフラグを有効にすると、セカンダリに複製物作成会社は、ユーザーのサービスによって承認されるとすぐに、操作を解放します。</span><span class="sxs-lookup"><span data-stu-id="088c0-228">With this flag enabled, the secondary replicator releases the operation as soon as it is acknowledged by the user service.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="088c0-229"><languageKeyword>true</languageKeyword>場合は、それ以外のユーザーのサービスによって受信確認を送ったとすぐに、セカンダリのレプリケーター解放操作<languageKeyword>false</languageKeyword>です。</span><span class="sxs-lookup"><span data-stu-id="088c0-229"><languageKeyword>true</languageKeyword> if the secondary replicator releases the operation as soon as it is acknowledged by the user service; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="088c0-230">既定値は false</span><span class="sxs-lookup"><span data-stu-id="088c0-230">The default value is false</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="088c0-231">使用サービスが複製物作成会社間のトラフィックを保護するためのセキュリティ資格情報を定義できます。</span><span class="sxs-lookup"><span data-stu-id="088c0-231">Allows the service to define security credentials for securing the traffic between replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="088c0-232">複製物作成会社間のトラフィックを保護するためのセキュリティ資格情報を定義するサービス。</span><span class="sxs-lookup"><span data-stu-id="088c0-232">The service to define security credentials for securing the traffic between replicators.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseStreamFaultsAndEndOfStreamOperationAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="VB.NET" Value="Public Property UseStreamFaultsAndEndOfStreamOperationAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseStreamFaultsAndEndOfStreamOperationAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="088c0-233">これは、は、Service Fabric インフラストラクチャをサポートし、コードから直接使用するものではありません。</span><span class="sxs-lookup"><span data-stu-id="088c0-233">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>