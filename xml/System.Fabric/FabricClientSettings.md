<Type Name="FabricClientSettings" FullName="System.Fabric.FabricClientSettings">
  <TypeSignature Language="C#" Value="public sealed class FabricClientSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClientSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClientSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClientSettings" />
  <TypeSignature Language="F#" Value="type FabricClientSettings = class" />
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
      <para><span data-ttu-id="d8920-101">構成設定を表す、<see cref="T:System.Fabric.FabricClient" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="d8920-101">Represents the configuration settings for the <see cref="T:System.Fabric.FabricClient" /> class.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClientSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClientSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="d8920-102"><see cref="T:System.Fabric.FabricClientSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="d8920-102">Initializes a new instance of the <see cref="T:System.Fabric.FabricClientSettings" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenBufferSize">
      <MemberSignature Language="C#" Value="public long AuthTokenBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 AuthTokenBufferSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenBufferSize As Long" />
      <MemberSignature Language="F#" Value="member this.AuthTokenBufferSize : int64 with get, set" Usage="System.Fabric.FabricClientSettings.AuthTokenBufferSize" />
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
            <span data-ttu-id="d8920-103">取得または Azure Active Directory から認証トークンを取得するときに使用するバッファー サイズを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-103">Gets or sets a value indicating the buffer size to use when retrieving an authentication token from Azure Active Directory.</span></span>
            </summary>
        <value>
            <span data-ttu-id="d8920-104">バッファー サイズをバイト単位で返します。</span><span class="sxs-lookup"><span data-stu-id="d8920-104">Returns the buffer size in bytes.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientFriendlyName">
      <MemberSignature Language="C#" Value="public string ClientFriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientFriendlyName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ClientFriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientFriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.ClientFriendlyName : string with get, set" Usage="System.Fabric.FabricClientSettings.ClientFriendlyName" />
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
          <para><span data-ttu-id="d8920-105">取得またはデバッグするための Service Fabric トレースに表示されるクライアントのフレンドリ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-105">Gets or sets the client friendly name that will appear in Service Fabric traces for debugging.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-106">Service Fabric のデバッグ トレースに表示されるクライアント フレンドリ名。</span><span class="sxs-lookup"><span data-stu-id="d8920-106">The client friendly name that will appear in Service Fabric traces for debugging.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-107">既定値は null と、クライアントのフレンドリ名が自動的に生成されますを GUID として内部的にします。</span><span class="sxs-lookup"><span data-stu-id="d8920-107">The default value is null and the client friendly name will automatically be generated as a GUID internally.</span></span></para>
          <para><span data-ttu-id="d8920-108">複数のクライアントは、同じプロセスから、または同じノードに作成でき場合、は、名前に一意の識別子を追加することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="d8920-108">If multiple clients can be created from the same process or on the same node, it is recommended to append a unique identifier to the name.</span></span>
            <span data-ttu-id="d8920-109">たとえば、MyProcessIdentifier - {guid} です。</span><span class="sxs-lookup"><span data-stu-id="d8920-109">For example, MyProcessIdentifier-{guid}.</span></span>
            <span data-ttu-id="d8920-110">これにより、トレースが生成するクライアントにさまざまな操作を追跡できます。</span><span class="sxs-lookup"><span data-stu-id="d8920-110">This ensures that traces can track different actions to the clients that generated them.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionIdleTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionIdleTimeout" />
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
            <span data-ttu-id="d8920-111">このパラメーターは廃止されました。</span><span class="sxs-lookup"><span data-stu-id="d8920-111">This parameter has been deprecated.</span></span> <span data-ttu-id="d8920-112">これは、次のリリースで削除されます。</span><span class="sxs-lookup"><span data-stu-id="d8920-112">This will be removed in our next release.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ConnectionInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ConnectionInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ConnectionInitializationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />
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
          <para><span data-ttu-id="d8920-113">取得または設定が、タイムアウトするまで、現在のゲートウェイ アドレスが有効な接続に応答しない場合他のさまざまなアドレスがランダムに選択からゲートウェイ アドレスのコレクション。</span><span class="sxs-lookup"><span data-stu-id="d8920-113">Gets or sets the timeout after which, if the current gateway address does not respond with a valid connection, another different address is randomly selected from the gateway addresses collection.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-114">現在のゲートウェイ アドレスが有効な接続に応答しない後にタイムアウトします。</span><span class="sxs-lookup"><span data-stu-id="d8920-114">The timeout after the current gateway address does not respond with a valid connection.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-115">既定値、<see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />プロパティは 2 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-115">The default value of the <see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" /> property is 2 seconds.</span></span></para>
          <para><span data-ttu-id="d8920-116"><see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" />プロパティには、値より小さくする必要があります、<see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="d8920-116">The <see cref="P:System.Fabric.FabricClientSettings.ConnectionInitializationTimeout" /> property must be less than the value of the <see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" /> property.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthOperationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthOperationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthOperationTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthOperationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthOperationTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthOperationTimeout" />
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
          <para><span data-ttu-id="d8920-117">取得または設定タイムアウト正常性状態操作要求、クライアントからゲートウェイにします。</span><span class="sxs-lookup"><span data-stu-id="d8920-117">Gets or sets the timeout on health operation requests from the client to the gateway.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-118">正常操作の要求をクライアントからゲートウェイにタイムアウトしました。</span><span class="sxs-lookup"><span data-stu-id="d8920-118">The timeout on health operation requests from the client to the gateway.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-119">既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" />プロパティは、120 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-119">The default value of the <see cref="P:System.Fabric.FabricClientSettings.HealthOperationTimeout" /> property is 120 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportRetrySendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportRetrySendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportRetrySendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportRetrySendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportRetrySendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />
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
          <para><span data-ttu-id="d8920-120">取得またはどの正常性で正常性マネージャーによってがまだ確認されていないレポートが再送信の再試行間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-120">Gets or sets the retry interval at which health reports that have not yet been acknowledged by the Health Manager are resent.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-121">再試行間隔は、どの正常性で正常性マネージャーによってがまだ確認されていないレポートが再送信します。</span><span class="sxs-lookup"><span data-stu-id="d8920-121">The retry interval at which health reports that have not yet been acknowledged by the Health Manager are resent.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-122">既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" />プロパティは 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-122">The default value of the <see cref="P:System.Fabric.FabricClientSettings.HealthReportRetrySendInterval" /> property is 30 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthReportSendInterval">
      <MemberSignature Language="C#" Value="public TimeSpan HealthReportSendInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthReportSendInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthReportSendInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthReportSendInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.HealthReportSendInterval" />
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
          <para><span data-ttu-id="d8920-123">取得またはに正常性レポートは正常性マネージャーに送信される間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-123">Gets or sets the interval at which health reports are sent to Health Manager.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-124">どの正常性レポートが送信される正常性マネージャーへの間隔。</span><span class="sxs-lookup"><span data-stu-id="d8920-124">The interval at which health reports are sent to Health Manager.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-125">既定値、<see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" />プロパティは 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-125">The default value of the <see cref="P:System.Fabric.FabricClientSettings.HealthReportSendInterval" /> property is 30 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveInterval">
      <MemberSignature Language="C#" Value="public TimeSpan KeepAliveInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KeepAliveInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.KeepAliveInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KeepAliveInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.KeepAliveInterval" />
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
          <para><span data-ttu-id="d8920-126">間隔を取得、<see cref="T:System.Fabric.FabricClient" />接続されているエンドポイントは ping を実行します。</span><span class="sxs-lookup"><span data-stu-id="d8920-126">Gets the interval at which the <see cref="T:System.Fabric.FabricClient" /> will ping the connected endpoint.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-127">間隔、<see cref="T:System.Fabric.FabricClient" />接続されているエンドポイントは ping を実行します。</span><span class="sxs-lookup"><span data-stu-id="d8920-127">The interval at which the <see cref="T:System.Fabric.FabricClient" /> will ping the connected endpoint.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-128">既定値、<see cref="P:System.Fabric.FabricClientSettings.KeepAliveInterval" />プロパティは 0 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-128">The default value of the <see cref="P:System.Fabric.FabricClientSettings.KeepAliveInterval" /> property is 0 seconds.</span></span></para>
          <para><span data-ttu-id="d8920-129">後にこのプロパティを更新することはできません、<see cref="T:System.Fabric.FabricClient" />が開かれています。</span><span class="sxs-lookup"><span data-stu-id="d8920-129">This property can't be updated after the <see cref="T:System.Fabric.FabricClient" /> is opened.</span></span>
            <span data-ttu-id="d8920-130">このプロパティはスロー設定、<see cref="T:System.ArgumentException" />例外。</span><span class="sxs-lookup"><span data-stu-id="d8920-130">Setting this property will throw a <see cref="T:System.ArgumentException" /> exception.</span></span></para>
          <para>
            <span data-ttu-id="d8920-131"><see cref="T:System.Fabric.FabricClient" />保留中の操作がある限り、ping を実行し続けます。</span><span class="sxs-lookup"><span data-stu-id="d8920-131"><see cref="T:System.Fabric.FabricClient" /> will continue pinging as long as it has pending operations.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationCacheUpdateTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationCacheUpdateTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationCacheUpdateTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationCacheUpdateTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationCacheUpdateTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationCacheUpdateTimeout" />
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
          <para><span data-ttu-id="d8920-132">取得またはサービスの通知への応答でローカル キャッシュを更新するためのタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-132">Gets or sets the timeout for updating the local cache in response to service notifications.</span></span> <span data-ttu-id="d8920-133">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-133">The default value is 30 seconds.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-134">サービスの通知への応答でローカル キャッシュの更新のタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="d8920-134">The timeout for updating the local cache in response to service notifications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationGatewayConnectionTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan NotificationGatewayConnectionTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property NotificationGatewayConnectionTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NotificationGatewayConnectionTimeout : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.NotificationGatewayConnectionTimeout" />
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
          <para><span data-ttu-id="d8920-135">取得またはクライアントがサービスの通知に登録されている場合は、再接続プロトコルを実行するためのタイムアウトを設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-135">Gets or sets the timeout for running a re-connection protocol if the client has registered for service notifications.</span></span> <span data-ttu-id="d8920-136">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-136">The default value is 30 seconds.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-137">クライアントがサービスの通知に登録されている場合は、再接続プロトコルを実行するためのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="d8920-137">The timeout for running a re-connection protocol if the client has registered for service notifications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheBucketCount">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheBucketCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheBucketCount" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheBucketCount As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheBucketCount : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheBucketCount" />
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
          <para><span data-ttu-id="d8920-138">取得またはクライアントのサービスの解像度のキャッシュで使用される、バケット数を設定します。</span><span class="sxs-lookup"><span data-stu-id="d8920-138">Gets or sets the bucket count used by the client’s service resolution cache.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-139">クライアントのサービスの解像度のキャッシュで使用されるバケットの数。</span><span class="sxs-lookup"><span data-stu-id="d8920-139">The bucket count used by the client’s service resolution cache.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-140">既定値は 1024 です。</span><span class="sxs-lookup"><span data-stu-id="d8920-140">The default value is 1024.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionLocationCacheLimit">
      <MemberSignature Language="C#" Value="public long PartitionLocationCacheLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PartitionLocationCacheLimit" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionLocationCacheLimit As Long" />
      <MemberSignature Language="F#" Value="member this.PartitionLocationCacheLimit : int64 with get, set" Usage="System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />
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
          <para><span data-ttu-id="d8920-141">クライアントのキャッシュの場所エントリの最大数を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8920-141">Gets the maximum number of cached location entries on the client.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-142">クライアントのキャッシュの場所エントリの最大数。</span><span class="sxs-lookup"><span data-stu-id="d8920-142">The maximum number of cached location entries on the client.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-143">既定値、<see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />プロパティは 1000 です。</span><span class="sxs-lookup"><span data-stu-id="d8920-143">The default value of the <see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" /> property is 1000.</span></span></para>
          <para><span data-ttu-id="d8920-144"><see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" />プロパティは更新できません。</span><span class="sxs-lookup"><span data-stu-id="d8920-144">The <see cref="P:System.Fabric.FabricClientSettings.PartitionLocationCacheLimit" /> property is not updatable.</span></span> <span data-ttu-id="d8920-145">このプロパティはスロー設定、<see cref="T:System.ArgumentException" />例外。</span><span class="sxs-lookup"><span data-stu-id="d8920-145">Setting this property will throw a <see cref="T:System.ArgumentException" /> exception.</span></span></para>
          <para><span data-ttu-id="d8920-146">キャッシュ制限に達したときに、最も古いエントリが最初に破棄されます。</span><span class="sxs-lookup"><span data-stu-id="d8920-146">When the cache limit is reached the oldest entries are discarded first.</span></span> <span data-ttu-id="d8920-147">既定値は 100 です。</span><span class="sxs-lookup"><span data-stu-id="d8920-147">The default value is 100.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceChangePollInterval">
      <MemberSignature Language="C#" Value="public TimeSpan ServiceChangePollInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ServiceChangePollInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceChangePollInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ServiceChangePollInterval : TimeSpan with get, set" Usage="System.Fabric.FabricClientSettings.ServiceChangePollInterval" />
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
          <para><span data-ttu-id="d8920-148">取得または設定タイムアウト サービスの変更通知要求、クライアントからすべての登録されたコールバックのゲートウェイにします。</span><span class="sxs-lookup"><span data-stu-id="d8920-148">Gets or sets the timeout on service change notification requests from the client to the gateway for all registered callbacks.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="d8920-149">サービスのタイムアウトは、すべての登録されたコールバックのゲートウェイに、クライアントからの通知要求を変更します。</span><span class="sxs-lookup"><span data-stu-id="d8920-149">The timeout on service change notification requests from the client to the gateway for all registered callbacks.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="d8920-150">既定値、<see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" />プロパティは、120 秒です。</span><span class="sxs-lookup"><span data-stu-id="d8920-150">The default value of the <see cref="P:System.Fabric.FabricClientSettings.ServiceChangePollInterval" /> property is 120 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>