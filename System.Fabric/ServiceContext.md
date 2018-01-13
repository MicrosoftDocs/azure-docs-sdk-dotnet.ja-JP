<Type Name="ServiceContext" FullName="System.Fabric.ServiceContext">
  <TypeSignature Language="C#" Value="public abstract class ServiceContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceContext" />
  <TypeSignature Language="F#" Value="type ServiceContext = class" />
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
            <span data-ttu-id="fda10-101">サービス コンテキスト下で、サービスが動作しています。</span><span class="sxs-lookup"><span data-stu-id="fda10-101">The service context that the service is operating under.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ServiceContext (System.Fabric.NodeContext nodeContext, System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, Uri serviceName, byte[] initializationData, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.NodeContext nodeContext, class System.Fabric.ICodePackageActivationContext codePackageActivationContext, string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceContext.#ctor(System.Fabric.NodeContext,System.Fabric.ICodePackageActivationContext,System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
      <MemberSignature Language="F#" Value="new System.Fabric.ServiceContext : System.Fabric.NodeContext * System.Fabric.ICodePackageActivationContext * string * Uri * byte[] * Guid * int64 -&gt; System.Fabric.ServiceContext" Usage="new System.Fabric.ServiceContext (nodeContext, codePackageActivationContext, serviceTypeName, serviceName, initializationData, partitionId, replicaOrInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeContext" Type="System.Fabric.NodeContext" />
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.ICodePackageActivationContext" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeContext"><span data-ttu-id="fda10-102">ステートレス サービス インスタンスが実行されているノードに関する情報を含むノードのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="fda10-102">The node context, which contains information about the node where the stateless service instance is running.</span></span></param>
        <param name="codePackageActivationContext"><span data-ttu-id="fda10-103">コード パッケージのアクティベーション コンテキスト サービス マニフェストと現在アクティブ化されたコード パッケージからの情報を格納しているコンテキスト ID など、like の作業ディレクトリです。</span><span class="sxs-lookup"><span data-stu-id="fda10-103">The code package activation context, which contains information from the service manifest and the currently activated code package, like work directory, context ID etc.</span></span></param>
        <param name="serviceTypeName"><span data-ttu-id="fda10-104">サービス型の名前。</span><span class="sxs-lookup"><span data-stu-id="fda10-104">The service type name.</span></span></param>
        <param name="serviceName"><span data-ttu-id="fda10-105">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="fda10-105">The service name.</span></span></param>
        <param name="initializationData"><span data-ttu-id="fda10-106">サービスの初期化データ、サービスの作成者によって提供されるカスタムの初期化データを表します。</span><span class="sxs-lookup"><span data-stu-id="fda10-106">The service initialization data, which represents custom initialization data provided by the creator of the service.</span></span></param>
        <param name="partitionId"><span data-ttu-id="fda10-107">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="fda10-107">The partition ID.</span></span></param>
        <param name="replicaOrInstanceId"><span data-ttu-id="fda10-108">レプリカまたはインスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="fda10-108">The replica or instance ID.</span></span></param>
        <summary>
            <span data-ttu-id="fda10-109"><see cref="T:System.Fabric.ServiceContext" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fda10-109">Initializes a new instance of the <see cref="T:System.Fabric.ServiceContext" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageActivationContext">
      <MemberSignature Language="C#" Value="public System.Fabric.ICodePackageActivationContext CodePackageActivationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ICodePackageActivationContext CodePackageActivationContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageActivationContext As ICodePackageActivationContext" />
      <MemberSignature Language="F#" Value="member this.CodePackageActivationContext : System.Fabric.ICodePackageActivationContext" Usage="System.Fabric.ServiceContext.CodePackageActivationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ICodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="fda10-110">サービス マニフェストと現在アクティブ化されたコード パッケージからの情報を含むコード パッケージ アクティベーション コンテキストを取得 like の作業ディレクトリ、コンテキスト ID などです。</span><span class="sxs-lookup"><span data-stu-id="fda10-110">Gets the code package activation context, which contains information from the service manifest and the currently activated code package, like work directory, context ID etc.</span></span></para>
        </summary>
        <value><span data-ttu-id="fda10-111">コード パッケージのアクティベーション コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="fda10-111">The code package activation context.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.ServiceContext.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fda10-112">サービスの初期化データを取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-112">Gets the initialization data of the service.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-113">初期化データ。</span><span class="sxs-lookup"><span data-stu-id="fda10-113">The initialization data.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenAddress">
      <MemberSignature Language="C#" Value="public string ListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ListenAddress : string" Usage="System.Fabric.ServiceContext.ListenAddress" />
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
          <para><span data-ttu-id="fda10-114">これで、サービスが通信リスナーを開始します。 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="fda10-114">The address at which the service should start the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fda10-115">これで、サービスが通信リスナーを開始します。 アドレスです。</span><span class="sxs-lookup"><span data-stu-id="fda10-115">The address at which the service should start the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeContext">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeContext NodeContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeContext NodeContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.NodeContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeContext As NodeContext" />
      <MemberSignature Language="F#" Value="member this.NodeContext : System.Fabric.NodeContext" Usage="System.Fabric.ServiceContext.NodeContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fda10-116">サービスのレプリカがインスタンス化されたノードに関する情報を含むノードのコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-116">Gets the node context with information about the node where the service replica is instantiated.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-117">サービス レプリカまたはインスタンスがインスタンス化されるノードのノードのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="fda10-117">The node context for the node where the service replica or instance is instantiated.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceContext.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fda10-118">パーティション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="fda10-118">Gets the partition ID.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-119">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="fda10-119">The partition ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAddress">
      <MemberSignature Language="C#" Value="public string PublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.PublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.PublishAddress : string" Usage="System.Fabric.ServiceContext.PublishAddress" />
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
          <para><span data-ttu-id="fda10-120">リッスン アドレスとして、サービスが公開されるアドレスです。</span><span class="sxs-lookup"><span data-stu-id="fda10-120">The address which the service should publish as the listen address.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="fda10-121">リッスン アドレスとして、サービスが公開されるアドレスです。</span><span class="sxs-lookup"><span data-stu-id="fda10-121">The address which the service should publish as the listen address.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceId">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ReplicaOrInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaOrInstanceId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceId : int64" Usage="System.Fabric.ServiceContext.ReplicaOrInstanceId" />
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
            <span data-ttu-id="fda10-122">ステートフル サービス レプリカ ID またはステートレス サービス インスタンス ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-122">Gets the stateful service replica ID or the stateless service instance ID.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-123">ステートフル サービス レプリカ ID またはステートレス サービス インスタンス id。</span><span class="sxs-lookup"><span data-stu-id="fda10-123">The stateful service replica ID or the stateless service instance ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceContext.ServiceName" />
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
            <span data-ttu-id="fda10-124">サービス名を取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-124">Get the service name.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-125">サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="fda10-125">The service name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.ServiceContext.ServiceTypeName" />
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
            <span data-ttu-id="fda10-126">サービス型の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-126">Gets the service type name.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-127">サービス型の名前。</span><span class="sxs-lookup"><span data-stu-id="fda10-127">The service type name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="public string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceContext.TraceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="System.Fabric.ServiceContext.TraceId" />
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
            <span data-ttu-id="fda10-128">サービスのトレース ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="fda10-128">Gets the trace ID of the service.</span></span>
            </summary>
        <value><span data-ttu-id="fda10-129">サービスのトレース ID。</span><span class="sxs-lookup"><span data-stu-id="fda10-129">The trace ID of the service.</span></span></value>
        <remarks><span data-ttu-id="fda10-130">トレース ID は、生成されたトレースの識別子として使用できます。</span><span class="sxs-lookup"><span data-stu-id="fda10-130">The trace ID can be used as an identifier for generated traces.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>