<Type Name="FabricClient" FullName="System.Fabric.FabricClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1204:StaticElementsMustAppearBeforeInstanceElements", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1202:ElementsMustBeOrderedByAccess", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="b984c-101">作成し、Service Fabric サービスとその他のエンティティを管理します。</span><span class="sxs-lookup"><span data-stu-id="b984c-101">Creates and manages Service Fabric services and other entities.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="b984c-102">可能な限り FabricClients を共有することを強くお勧めします。</span><span class="sxs-lookup"><span data-stu-id="b984c-102">It is highly recommended that you share FabricClients as much as possible.</span></span>
                <span data-ttu-id="b984c-103">これは、FabricClient にキャッシュし、それ以外の場合を十分に活用することはできません、バッチ処理などの複数の最適化があるためです。</span><span class="sxs-lookup"><span data-stu-id="b984c-103">This is because the FabricClient has multiple optimizations such as caching and batching that you would not be able to fully utilize otherwise.</span></span>
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-104"><see cref="T:System.Fabric.FabricClient" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b984c-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class.</span></span> <span data-ttu-id="b984c-105">このコンス トラクターは、クラスター内で実行されているコードで使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b984c-105">This constructor should be used by code that is running inside the cluster.</span></span> <span data-ttu-id="b984c-106">これにより、<see cref="T:System.Fabric.FabricClient" />インスタンスと同じノードで実行されているローカル ゲートウェイ サービスを経由してクラスターに接続します。</span><span class="sxs-lookup"><span data-stu-id="b984c-106">It allows the <see cref="T:System.Fabric.FabricClient" /> instance to connect to the cluster via the local Gateway service running on the same node.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="b984c-107">このコンス トラクターは、th クラスターへの接続に同じノードで実行されているローカル ゲートウェイ サービスを使用するため、クライアントは、追加のネットワーク ホップをバイパスできます。</span><span class="sxs-lookup"><span data-stu-id="b984c-107">Since this constructor uses the local Gateway service running on the same node to connect to th cluster, your client can bypass an extra network hop.</span></span> <span data-ttu-id="b984c-108">クラスター外で実行されているコードから、クラスターに接続するには、接続パラメーターを明示的に指定できる別のコンス トラクターを使用します。</span><span class="sxs-lookup"><span data-stu-id="b984c-108">To connect to a cluster from code running outside the cluster, use a different constructor which allows you to explicitly specify the connection parameters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientRole clientRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricClientRole clientRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientRole As FabricClientRole)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientRole -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient clientRole" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRole" Type="System.Fabric.FabricClientRole" />
      </Parameters>
      <Docs>
        <param name="clientRole">
          <para><span data-ttu-id="b984c-109">Fabric クライアントの役割です。</span><span class="sxs-lookup"><span data-stu-id="b984c-109">The fabric client role.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="b984c-110">新しいインスタンスを初期化、 <see cref="T:System.Fabric.FabricClient" /> - 指定されたファブリック クライアントの役割を持つクラス<see cref="T:System.Fabric.FabricClientRole" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-110">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with the specified fabric client role - <see cref="T:System.Fabric.FabricClientRole" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient settings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="b984c-111">Fabric クライアントによって使用されるファブリックのクライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="b984c-111">The fabric client settings used by the fabric client.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-112">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />目的を持つクラス<see cref="T:System.Fabric.FabricClientSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-112">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with the desired <see cref="T:System.Fabric.FabricClientSettings" />.</span></span> <span data-ttu-id="b984c-113">場合、 <see cref="T:System.Fabric.FabricClient" /> 、サービスと同じクラスターには、ローカルを使用して<see cref="T:System.Fabric.FabricClient" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-113">If the <see cref="T:System.Fabric.FabricClient" /> is on the same cluster as the service, then use a Local <see cref="T:System.Fabric.FabricClient" />.</span></span> <span data-ttu-id="b984c-114">ローカル<see cref="T:System.Fabric.FabricClient" />できるサービス ファブリックの機能、<see cref="T:System.Fabric.FabricClient" />一覧から選択することではなくローカル ゲートウェイ サービスに接続します。</span><span class="sxs-lookup"><span data-stu-id="b984c-114">Local <see cref="T:System.Fabric.FabricClient" /> is a feature of Service Fabric that allows the <see cref="T:System.Fabric.FabricClient" /> to connect to the local Gateway Service instead of choosing from a list.</span></span> <span data-ttu-id="b984c-115">これにより、クライアントは、追加のネットワーク ホップをバイパスできます。</span><span class="sxs-lookup"><span data-stu-id="b984c-115">This way, your client can bypass an extra network hop.</span></span> <span data-ttu-id="b984c-116">場合、サービスは、同じクラスター内の別のサービス パーティションを解決し、ローカルを使用することをお勧め<see cref="T:System.Fabric.FabricClient" />の自動負荷分散を有効にし、パフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="b984c-116">In case a service is resolving another service partition in the same cluster, then it is recommended that you use Local <see cref="T:System.Fabric.FabricClient" />, as it enables automatic load balancing and improves performance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient hostEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostEndpoints">
          <para><span data-ttu-id="b984c-117">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-117">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-118">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />サービス ファブリック ゲートウェイ アドレスを指定したクラスです。</span><span class="sxs-lookup"><span data-stu-id="b984c-118">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses.</span></span> <span data-ttu-id="b984c-119">これらのホストのエンドポイントの一覧は、':' 区切りの文字列で最初の部分は、クラスターの ip アドレスと 2 番目の部分は、クライアント接続のエンドポイント ポートです。</span><span class="sxs-lookup"><span data-stu-id="b984c-119">These host-endpoints are list of ':' delimited strings where the first part is the ip of the cluster and the second part is the client-connection endpoint-port.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="b984c-120">Fabric クライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="b984c-120">The fabric client settings.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="b984c-121">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-121">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-122">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />サービス ファブリックのゲートウェイ アドレスと、目的の指定したクラス<see cref="T:System.Fabric.FabricClientSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-122">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses and the desired <see cref="T:System.Fabric.FabricClientSettings" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <span data-ttu-id="b984c-123"><see cref="T:System.Fabric.SecurityCredentials" />セキュリティ設定を定義、<see cref="T:System.Fabric.FabricClient" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-123"><see cref="T:System.Fabric.SecurityCredentials" /> defines the security settings for the<see cref="T:System.Fabric.FabricClient" />.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="b984c-124">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-124">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-125">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />クラスに指定されたサービス ファブリック ゲートウェイ アドレスと<see cref="T:System.Fabric.SecurityCredentials" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-125">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses and <see cref="T:System.Fabric.SecurityCredentials" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="keepAliveInterval">
          <para><span data-ttu-id="b984c-126">定期的なキープ アライブ メッセージの間隔を定義します。</span><span class="sxs-lookup"><span data-stu-id="b984c-126">Defines the periodic keep alive message interval.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para> <span data-ttu-id="b984c-127">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-127">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-128">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="b984c-128">DEPRECATED.</span></span> <span data-ttu-id="b984c-129">新しいインスタンスを初期化、 <see cref="T:System.Fabric.FabricClient" /> keepAliveInterval および Service Fabric ゲートウェイ アドレス (hostEndpoints) 指定されているクラスです。</span><span class="sxs-lookup"><span data-stu-id="b984c-129">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given keepAliveInterval and Service Fabric Gateway addresses (hostEndpoints).</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="b984c-130">接続の維持を定期的にメッセージを必要とするクライアントからクラスターへの接続の間の外部のデバイスがある場合 FabricClient のキープア ライブの機能を使用することを確認してください。</span><span class="sxs-lookup"><span data-stu-id="b984c-130">If there are external devices in between the connection from the client to the cluster that require periodic messages to keep the connection alive, then make sure to use the KeepAlive feature of FabricClient.</span></span> <span data-ttu-id="b984c-131">ユーザーは、FabricClient の初期化中に、TimeSpan keepAliveInterval を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-131">During the initialization of the FabricClient, users can specify a TimeSpan keepAliveInterval.</span></span> <span data-ttu-id="b984c-132">この引数を指定すると、FabricClient は定期的に ping を実行 Service Fabric のゲートウェイ サービスと現在通信保留中の操作がある限り、します。</span><span class="sxs-lookup"><span data-stu-id="b984c-132">If this argument is specified, then the FabricClient will periodically ping the Service Fabric Gateway Service it is currently communicating with, as long as there is a pending operation.</span></span> <span data-ttu-id="b984c-133">この機能は便利なシナリオの例では、Windows Azure です。</span><span class="sxs-lookup"><span data-stu-id="b984c-133">An example of a scenario where this feature is useful is Windows Azure.</span></span> <span data-ttu-id="b984c-134">場合、 <see cref="T:System.Fabric.FabricClient" /> Windows Azure の外部では、クラスターは、Windows Azure 内で、すべての接続はを介して、Azure ロード バランサー (alb モード) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b984c-134">If the <see cref="T:System.Fabric.FabricClient" /> is outside of Windows Azure and the cluster is inside of Windows Azure, then all connections will go through the Azure Load Balancer (ALB).</span></span> <span data-ttu-id="b984c-135">Alb モードでは、60 秒より長くアイドル状態になっている接続を終了します。</span><span class="sxs-lookup"><span data-stu-id="b984c-135">ALB terminates connections that are idle for more than 60 seconds.</span></span> <span data-ttu-id="b984c-136">そのため、これらの状況で<see cref="T:System.Fabric.FabricClient" />KeepAliveInterval に設定を作成する&lt;59 の秒数 (20-30 をお勧めします)。</span><span class="sxs-lookup"><span data-stu-id="b984c-136">Hence, in these situations, <see cref="T:System.Fabric.FabricClient" /> should be created with KeepAliveInterval set to &lt;59 seconds (20 -30 is recommended).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <span data-ttu-id="b984c-137"><see cref="T:System.Fabric.SecurityCredentials" />セキュリティ設定を定義、<see cref="T:System.Fabric.FabricClient" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-137"><see cref="T:System.Fabric.SecurityCredentials" /> defines the security settings for the<see cref="T:System.Fabric.FabricClient" />.</span></span></para>
        </param>
        <param name="settings">
          <para><span data-ttu-id="b984c-138">Fabric クライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="b984c-138">The fabric client settings.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="b984c-139">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-139">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-140">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />指定されたサービス ファブリック ゲートウェイ アドレス クラス<see cref="T:System.Fabric.SecurityCredentials" />と<see cref="T:System.Fabric.FabricClientSettings" />です。</span><span class="sxs-lookup"><span data-stu-id="b984c-140">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses, <see cref="T:System.Fabric.SecurityCredentials" /> and <see cref="T:System.Fabric.FabricClientSettings" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="b984c-141">セキュリティ資格情報を定義します。</span><span class="sxs-lookup"><span data-stu-id="b984c-141">Defines the security credentials.</span></span></param>
        <param name="keepAliveInterval">
          <para><span data-ttu-id="b984c-142">定期的なキープ アライブ メッセージの間隔を定義します。</span><span class="sxs-lookup"><span data-stu-id="b984c-142">Defines the periodic keep alive message interval.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para> <span data-ttu-id="b984c-143">ゲートウェイ アドレスのセットを定義、<see cref="T:System.Fabric.FabricClient" />クラスターへの接続に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-143">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-144">推奨されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="b984c-144">DEPRECATED.</span></span> <span data-ttu-id="b984c-145">新しいインスタンスを初期化、<see cref="T:System.Fabric.FabricClient" />が指定されている資格情報、keepAliveInterval Service Fabric ゲートウェイ アドレス (hostEndpoints) クラスします。</span><span class="sxs-lookup"><span data-stu-id="b984c-145">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given credentials, keepAliveInterval and Service Fabric Gateway addresses (hostEndpoints).</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="b984c-146">接続の維持を定期的にメッセージを必要とするクライアントからクラスターへの接続の間の外部のデバイスがある場合 FabricClient のキープア ライブの機能を使用することを確認してください。</span><span class="sxs-lookup"><span data-stu-id="b984c-146">If there are external devices in between the connection from the client to the cluster that require periodic messages to keep the connection alive, then make sure to use the KeepAlive feature of FabricClient.</span></span> <span data-ttu-id="b984c-147">ユーザーは、FabricClient の初期化中に、TimeSpan keepAliveInterval を指定できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-147">During the initialization of the FabricClient, users can specify a TimeSpan keepAliveInterval.</span></span> <span data-ttu-id="b984c-148">この引数を指定すると、FabricClient は定期的に ping を実行 Service Fabric のゲートウェイ サービスと現在通信保留中の操作がある限り、します。</span><span class="sxs-lookup"><span data-stu-id="b984c-148">If this argument is specified, then the FabricClient will periodically ping the Service Fabric Gateway Service it is currently communicating with, as long as there is a pending operation.</span></span> <span data-ttu-id="b984c-149">この機能は便利なシナリオの例では、Windows Azure です。</span><span class="sxs-lookup"><span data-stu-id="b984c-149">An example of a scenario where this feature is useful is Windows Azure.</span></span> <span data-ttu-id="b984c-150">場合、 <see cref="T:System.Fabric.FabricClient" /> Windows Azure の外部では、クラスターは、Windows Azure 内で、すべての接続はを介して、Azure ロード バランサー (alb モード) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="b984c-150">If the <see cref="T:System.Fabric.FabricClient" /> is outside of Windows Azure and the cluster is inside of Windows Azure, then all connections will go through the Azure Load Balancer (ALB).</span></span> <span data-ttu-id="b984c-151">Alb モードでは、60 秒より長くアイドル状態になっている接続を終了します。</span><span class="sxs-lookup"><span data-stu-id="b984c-151">ALB terminates connections that are idle for more than 60 seconds.</span></span> <span data-ttu-id="b984c-152">そのため、これらの状況で<see cref="T:System.Fabric.FabricClient" />KeepAliveInterval に設定を作成する&lt;59 の秒数 (20-30 をお勧めします)。</span><span class="sxs-lookup"><span data-stu-id="b984c-152">Hence, in these situations, <see cref="T:System.Fabric.FabricClient" /> should be created with KeepAliveInterval set to &lt;59 seconds (20 -30 is recommended).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ApplicationManagementClient ApplicationManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ApplicationManagementClient ApplicationManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ApplicationManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationManager As FabricClient.ApplicationManagementClient" />
      <MemberSignature Language="F#" Value="member this.ApplicationManager : System.Fabric.FabricClient.ApplicationManagementClient" Usage="System.Fabric.FabricClient.ApplicationManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ApplicationManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-153">取得、<see cref="P:System.Fabric.FabricClient.ApplicationManager" />アプリケーションおよびアプリケーションの種類に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-153">Gets the <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> that can be used to perform operations related to applications and application types.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-154"><see cref="P:System.Fabric.FabricClient.ApplicationManager" />アプリケーションおよびアプリケーションの種類に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-154">The <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> that can be used to perform operations related to applications and application types.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimsRetrieval">
      <MemberSignature Language="C#" Value="public event System.Fabric.FabricClient.ClaimsRetrievalEventHandler ClaimsRetrieval;" />
      <MemberSignature Language="ILAsm" Value=".event class System.Fabric.FabricClient/ClaimsRetrievalEventHandler ClaimsRetrieval" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClaimsRetrieval" />
      <MemberSignature Language="VB.NET" Value="Public Event ClaimsRetrieval As FabricClient.ClaimsRetrievalEventHandler " />
      <MemberSignature Language="F#" Value="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " Usage="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClaimsRetrievalEventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b984c-155">クライアントは、ゲートウェイと承認の要求トークンを提供する必要がある場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="b984c-155">Occurs when the client needs to provide a claims token for authorization with the gateway</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="b984c-156">参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" />Azure Active Directory 認証を使用してセキュリティで保護されたクラスターに接続するためです。</span><span class="sxs-lookup"><span data-stu-id="b984c-156">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" /> for connecting to secure cluster using Azure Active Directory authentication.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientConnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler " Usage="member this.ClientConnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b984c-157">クライアントがゲートウェイに接続しているときに発生します。</span><span class="sxs-lookup"><span data-stu-id="b984c-157">Occurs when the client is connected to gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler " Usage="member this.ClientDisconnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b984c-158">クライアントが、ゲートウェイから切断されている場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="b984c-158">Occurs when the client is disconnected from the gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ClusterManagementClient ClusterManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ClusterManagementClient ClusterManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClusterManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterManager As FabricClient.ClusterManagementClient" />
      <MemberSignature Language="F#" Value="member this.ClusterManager : System.Fabric.FabricClient.ClusterManagementClient" Usage="System.Fabric.FabricClient.ClusterManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClusterManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-159">取得、 <see cref="P:System.Fabric.FabricClient.ClusterManager" /> Service Fabric クラスターに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-159">Gets the <see cref="P:System.Fabric.FabricClient.ClusterManager" /> that can be used to perform operations related to the Service Fabric cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-160"><see cref="P:System.Fabric.FabricClient.ClusterManager" /> Service Fabric クラスターに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-160">The <see cref="P:System.Fabric.FabricClient.ClusterManager" /> that can be used to perform operations related to the Service Fabric cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ComposeDeploymentClient ComposeDeploymentManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ComposeDeploymentClient ComposeDeploymentManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentManager As FabricClient.ComposeDeploymentClient" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentManager : System.Fabric.FabricClient.ComposeDeploymentClient" Usage="System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ComposeDeploymentClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-161">取得、<see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" />展開の作成に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-161">Gets the <see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" /> that can be used to perform operations related to compose deployment.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-162"><see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" />展開の作成に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-162">The <see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" /> that can be used to perform operations related to compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="b984c-163">Fabric クライアントを破棄します。</span><span class="sxs-lookup"><span data-stu-id="b984c-163">Disposes of the fabric client.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSystemApplication">
      <MemberSignature Language="C#" Value="public readonly Uri FabricSystemApplication;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Uri FabricSystemApplication" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly FabricSystemApplication As Uri " />
      <MemberSignature Language="F#" Value="val mutable FabricSystemApplication : Uri" Usage="System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-164">サービス ファブリック システム アプリケーションです。</span><span class="sxs-lookup"><span data-stu-id="b984c-164">The Service Fabric System application.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.FaultManagementClient FaultManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/FaultManagementClient FaultManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.FaultManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultManager As FabricClient.FaultManagementClient" />
      <MemberSignature Language="F#" Value="member this.FaultManager : System.Fabric.FabricClient.FaultManagementClient" Usage="System.Fabric.FabricClient.FaultManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+FaultManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b984c-165">取得、<see cref="T:System.Fabric.FabricClient.FaultManagementClient" />を強制実行エラー。</span><span class="sxs-lookup"><span data-stu-id="b984c-165">Gets the <see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> to induce faults.</span></span> <span data-ttu-id="b984c-166">たとえば、RestartNodeAsync です。</span><span class="sxs-lookup"><span data-stu-id="b984c-166">For example, RestartNodeAsync.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="b984c-167"><see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b984c-167">Returns <see cref="T:System.Fabric.FabricClient.FaultManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="fabricClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="b984c-168">Fabric クライアントのデストラクターです。</span><span class="sxs-lookup"><span data-stu-id="b984c-168">Destructor of fabric client.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.HealthClient HealthManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/HealthClient HealthManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.HealthManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthManager As FabricClient.HealthClient" />
      <MemberSignature Language="F#" Value="member this.HealthManager : System.Fabric.FabricClient.HealthClient" Usage="System.Fabric.FabricClient.HealthManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+HealthClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-169">関連するヘルスを実行するために使用する正常性のクライアントを取得、操作などの正常性のレポートまたはエンティティのヘルスを取得します。</span><span class="sxs-lookup"><span data-stu-id="b984c-169">Gets the health client that can be used to perform health related operations, like report health or get entity health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-170">正常性のクライアント正常性を実行するために使用するには、レポートの正常性アドインまたは get エンティティのヘルスなどの操作が関連します。</span><span class="sxs-lookup"><span data-stu-id="b984c-170">The health client that can be used to perform health related operations, like report health or get entity health.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfrastructureManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.InfrastructureServiceClient InfrastructureManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/InfrastructureServiceClient InfrastructureManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.InfrastructureManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InfrastructureManager As FabricClient.InfrastructureServiceClient" />
      <MemberSignature Language="F#" Value="member this.InfrastructureManager : System.Fabric.FabricClient.InfrastructureServiceClient" Usage="System.Fabric.FabricClient.InfrastructureManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+InfrastructureServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-171">取得、<see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" />クラスターが実行されているインフラストラクチャに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-171">Gets the <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> that can be used to perform operations related to the infrastructure on which the cluster is running.</span></span></para>
          <para><span data-ttu-id="b984c-172">このプロパティは、Service Fabric プラットフォームをサポートしています。コードから直接呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="b984c-172">This property supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-173"><see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" />クラスターが実行されているインフラストラクチャに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-173">The <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> that can be used to perform operations related to the infrastructure on which the cluster is running.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.PropertyManagementClient PropertyManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/PropertyManagementClient PropertyManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.PropertyManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyManager As FabricClient.PropertyManagementClient" />
      <MemberSignature Language="F#" Value="member this.PropertyManager : System.Fabric.FabricClient.PropertyManagementClient" Usage="System.Fabric.FabricClient.PropertyManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+PropertyManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-174">取得、<see cref="P:System.Fabric.FabricClient.PropertyManager" />名前およびプロパティに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-174">Gets the <see cref="P:System.Fabric.FabricClient.PropertyManager" /> that can be used to perform operations related to names and properties.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-175"><see cref="P:System.Fabric.FabricClient.PropertyManager" />名前およびプロパティに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-175">The <see cref="P:System.Fabric.FabricClient.PropertyManager" /> that can be used to perform operations related to names and properties.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.QueryClient QueryManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/QueryClient QueryManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.QueryManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryManager As FabricClient.QueryClient" />
      <MemberSignature Language="F#" Value="member this.QueryManager : System.Fabric.FabricClient.QueryClient" Usage="System.Fabric.FabricClient.QueryManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+QueryClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-176">Service Fabric クラスターに対してクエリを実行するために使用するクエリ マネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b984c-176">Gets the query manager that can be used to execute queries against the Service Fabric cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-177">Service Fabric クラスターに対するクエリの実行に使用できるクエリ マネージャー。</span><span class="sxs-lookup"><span data-stu-id="b984c-177">The query manager that can be used to execute queries against the Service Fabric cluster.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="b984c-178">クラスターに対してクエリを実行するクエリ マネージャーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-178">The query manager can be used to execute queries against the cluster.</span></span>
            <span data-ttu-id="b984c-179">ほとんどのクエリが分散されます。</span><span class="sxs-lookup"><span data-stu-id="b984c-179">Most of the queries are distributed.</span></span> <span data-ttu-id="b984c-180">さまざまな情報を取得する複数のシステム コンポーネントを呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="b984c-180">They call multiple system components to get different information.</span></span>
            <span data-ttu-id="b984c-181">システム コンポーネントへの呼び出しを並列で実行し、返される結果の共通のキーに基づき集計します。</span><span class="sxs-lookup"><span data-stu-id="b984c-181">The calls to the system components are executed in parallel and the returned results are aggregated based on a common key.</span></span>
            <span data-ttu-id="b984c-182">たとえば、クラスター内のノードの一覧を取得する、<see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />クエリはフェールオーバー マネージャー、クラスター マネージャー、およびヘルス マネージャーのシステム サービスに移動します。</span><span class="sxs-lookup"><span data-stu-id="b984c-182">For example, to get the list of nodes in the cluster, the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> query goes to Failover Manager, Cluster Manager, and Health Manager system services.</span></span>
            <span data-ttu-id="b984c-183">このため、一部のクエリは手間がかかります。</span><span class="sxs-lookup"><span data-stu-id="b984c-183">For this reason, some queries are expensive.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RepairManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.RepairManagementClient RepairManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/RepairManagementClient RepairManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.RepairManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepairManager As FabricClient.RepairManagementClient" />
      <MemberSignature Language="F#" Value="member this.RepairManager : System.Fabric.FabricClient.RepairManagementClient" Usage="System.Fabric.FabricClient.RepairManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+RepairManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-184">取得、<see cref="T:System.Fabric.FabricClient.RepairManagementClient" />修復作業の管理に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-184">Gets the <see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> that can be used to manage repair tasks.</span></span></para>
          <para><span data-ttu-id="b984c-185">このプロパティは、Service Fabric プラットフォームをサポートしています。コードから直接呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="b984c-185">This property supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-186"><see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b984c-186">Returns <see cref="T:System.Fabric.FabricClient.RepairManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceGroupManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceGroupManagementClient ServiceGroupManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceGroupManagementClient ServiceGroupManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceGroupManager As FabricClient.ServiceGroupManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceGroupManager : System.Fabric.FabricClient.ServiceGroupManagementClient" Usage="System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceGroupManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-187">取得、<see cref="P:System.Fabric.FabricClient.ServiceGroupManager" />サービス グループに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-187">Gets the <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> that can be used to perform operations related to service groups.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-188"><see cref="P:System.Fabric.FabricClient.ServiceGroupManager" />サービス グループに関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-188">The <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> that can be used to perform operations related to service groups.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceManagementClient ServiceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceManagementClient ServiceManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManager As FabricClient.ServiceManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceManager : System.Fabric.FabricClient.ServiceManagementClient" Usage="System.Fabric.FabricClient.ServiceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-189">取得、<see cref="P:System.Fabric.FabricClient.ServiceManager" />サービスとサービスの種類に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-189">Gets the <see cref="P:System.Fabric.FabricClient.ServiceManager" /> that can be used to perform operations related to services and service types.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-190"><see cref="P:System.Fabric.FabricClient.ServiceManager" />サービスとサービスの種類に関連する操作の実行に使用できます。</span><span class="sxs-lookup"><span data-stu-id="b984c-190">The <see cref="P:System.Fabric.FabricClient.ServiceManager" /> that can be used to perform operations related to services and service types.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClientSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClientSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As FabricClientSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.FabricClientSettings" Usage="System.Fabric.FabricClient.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClientSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="b984c-191">ファブリックのクライアント設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="b984c-191">Gets the fabric client settings.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="b984c-192">Fabric クライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="b984c-192">The fabric client settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.TestManagementClient TestManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/TestManagementClient TestManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.TestManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestManager As FabricClient.TestManagementClient" />
      <MemberSignature Language="F#" Value="member this.TestManager : System.Fabric.FabricClient.TestManagementClient" Usage="System.Fabric.FabricClient.TestManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+TestManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b984c-193">取得、 <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> FaultAnalysisService を通過する複雑なアクションを実行します。</span><span class="sxs-lookup"><span data-stu-id="b984c-193">Gets the <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> to perform complex actions that go through FaultAnalysisService.</span></span> <span data-ttu-id="b984c-194">たとえば、StartPartitionDataLossAsync です。</span><span class="sxs-lookup"><span data-stu-id="b984c-194">For example, StartPartitionDataLossAsync.</span></span>
            <span data-ttu-id="b984c-195">これも (つまり FaultAnalysisService を通過しない) の検証の Api をサポートします。</span><span class="sxs-lookup"><span data-stu-id="b984c-195">This also supports APIs for validation (that do not go through FaultAnalysisService).</span></span> <span data-ttu-id="b984c-196">たとえば、ValidateServiceAsync です。</span><span class="sxs-lookup"><span data-stu-id="b984c-196">For example, ValidateServiceAsync.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="b984c-197"><see cref="T:System.Fabric.FabricClient.TestManagementClient" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="b984c-197">Returns <see cref="T:System.Fabric.FabricClient.TestManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecurityCredentials">
      <MemberSignature Language="C#" Value="public void UpdateSecurityCredentials (System.Fabric.SecurityCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSecurityCredentials(class System.Fabric.SecurityCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSecurityCredentials(System.Fabric.SecurityCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSecurityCredentials (credentials As SecurityCredentials)" />
      <MemberSignature Language="F#" Value="member this.UpdateSecurityCredentials : System.Fabric.SecurityCredentials -&gt; unit" Usage="fabricClient.UpdateSecurityCredentials credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="System.Fabric.SecurityCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="b984c-198">使用する新しいセキュリティ資格情報。</span><span class="sxs-lookup"><span data-stu-id="b984c-198">The new security credentials to be used.</span></span></param>
        <summary>
            <span data-ttu-id="b984c-199">Fabric クライアントのセキュリティ資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="b984c-199">Updates the fabric client security credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSettings">
      <MemberSignature Language="C#" Value="public void UpdateSettings (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSettings(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSettings(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSettings (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateSettings : System.Fabric.FabricClientSettings -&gt; unit" Usage="fabricClient.UpdateSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="b984c-200">使用する新しい fabric クライアントの設定をします。</span><span class="sxs-lookup"><span data-stu-id="b984c-200">The new fabric client settings to be used.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="b984c-201">Fabric クライアント設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="b984c-201">Updates the fabric client settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="b984c-202">指定した fabric クライアント設定を null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="b984c-202">The specified fabric client settings can’t be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <span data-ttu-id="b984c-203"><see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />0 以上にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="b984c-203"><see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" /> must be greater or equal to zero.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>