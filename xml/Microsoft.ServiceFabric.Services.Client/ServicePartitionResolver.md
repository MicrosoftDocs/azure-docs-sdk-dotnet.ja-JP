<Type Name="ServicePartitionResolver" FullName="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver">
  <TypeSignature Language="C#" Value="public class ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServicePartitionResolver extends System.Object implements class Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class ServicePartitionResolver&#xA;Implements IServicePartitionResolver" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolver = class&#xA;    interface IServicePartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>
            <span data-ttu-id="d83a8-101">使用して、サービス パーティションの競合回避モジュールのクラスを実装して、 <see cref="T:System.Fabric.FabricClient">FabricClient の</see><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />サービス解決のためのメソッドをそのメソッドからのエラーに戻る/再試行メカニズムを実装します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-101">Implements the Service partition resolver class that uses the <see cref="T:System.Fabric.FabricClient">FabricClient's </see><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> method for service resolution and implements a back-off/retry mechanism on errors from that method.</span></span>
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver createFabricClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient"><span data-ttu-id="d83a8-102">Fabric クライアントを作成するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d83a8-102">Delegate to create fabric client.</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-103">FabricClient のインスタンスを作成する特定のデリゲートを呼び出すの ServicePartitionResolver をインスタンス化します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-103">Instantiates a ServicePartitionResolver, invoking the given delegate to instantiate FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver connectionEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="connectionEndpoints"><span data-ttu-id="d83a8-104">クラスターの管理エンドポイントの配列です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-104">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-105">ServicePartitionResolver をインスタンス化は、特定 connectionEndpoints を使用して、FabricClient の新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-105">Instantiates a ServicePartitionResolver, uses the given connectionEndpoints to create a new instance of the FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate createFabricClient, class Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate recreateFabricClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate,Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createFabricClient As CreateFabricClientDelegate, recreateFabricClient As CreateFabricClientDelegate)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate * Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (createFabricClient, recreateFabricClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
        <Parameter Name="recreateFabricClient" Type="Microsoft.ServiceFabric.Services.Client.CreateFabricClientDelegate" />
      </Parameters>
      <Docs>
        <param name="createFabricClient"><span data-ttu-id="d83a8-106">Fabric クライアントを作成するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d83a8-106">Delegate to create the fabric client.</span></span></param>
        <param name="recreateFabricClient"><span data-ttu-id="d83a8-107">Fabric クライアントを再作成するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="d83a8-107">Delegate to re-create the fabric client.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="d83a8-108">取得する最初のデリゲートを呼び出すの ServicePartionResolver をインスタンス化、 <see cref="T:System.Fabric.FabricClient">FabricClient。</see>です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-108">Instantiates a ServicePartionResolver, invoking the first delegate to get the <see cref="T:System.Fabric.FabricClient">FabricClient.</see>.</span></span>
            <span data-ttu-id="d83a8-109">パーティションの解決時に、FabricClient オブジェクトが破棄を取得し、2 番目のデリゲートを指定すると場合、2 番目のデリゲートを使用、FabricClient をもう一度取得されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-109">During partition resolution if FabricClient object gets disposed and second delegate is provided, it uses the second delegate to get the FabricClient again.</span></span> <span data-ttu-id="d83a8-110">2 番目のデリゲートは、破棄を取得または FabricClient が最初のデリゲートで作成された場合、FabricClient を作成する別の方法を指定する方法を提供します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-110">The second delegate provides a way to specify an alternate way to get or create FabricClient if FabricClient created with first delegate get disposed.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="d83a8-111">Fabric クライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-111">Fabric client Settings.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="d83a8-112">クラスターの管理エンドポイントの配列です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-112">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-113">ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する指定された FabricClient 設定と、connectionEndpoints を使用します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-113">Instantiates a ServicePartitionResolver, uses the given FabricClient Settings and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="d83a8-114">Fabric クライアントのセキュリティ資格情報。</span><span class="sxs-lookup"><span data-stu-id="d83a8-114">Security credentials for the fabric client.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="d83a8-115">クラスターの管理エンドポイントの配列です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-115">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-116">ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する特定のセキュリティ資格情報と、connectionEndpoints を使用します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-116">Instantiates a ServicePartitionResolver, uses the given security credentials and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServicePartitionResolver (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] connectionEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] connectionEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray connectionEndpoints As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="new Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver (credential, settings, connectionEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="connectionEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="d83a8-117">Fabric クライアントのセキュリティ資格情報。</span><span class="sxs-lookup"><span data-stu-id="d83a8-117">Security credentials for the fabric client.</span></span></param>
        <param name="settings"><span data-ttu-id="d83a8-118">Fabric クライアント設定します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-118">Fabric client Settings.</span></span></param>
        <param name="connectionEndpoints"><span data-ttu-id="d83a8-119">クラスターの管理エンドポイントの配列です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-119">Array of management endpoints of the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-120">ServicePartitionResolver をインスタンス化、FabricClient の新しいインスタンスを作成する特定のセキュリティ資格情報と FabricClient 設定、connectionEndpoints を使用します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-120">Instantiates a ServicePartitionResolver, uses the given security credentials, FabricClient Settings and the connectionEndpoints to create a new instance of FabricClient.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultMaxRetryBackoffInterval">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultMaxRetryBackoffInterval;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultMaxRetryBackoffInterval As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultMaxRetryBackoffInterval : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d83a8-121">既定最大バックオフ時間 maxRetryBackoffInterval 引数を明示的に指定せずにメソッドが呼び出されたときに、再試行する前に ServicePartitionResolver の ResolveAsync メソッドで使用します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-121">The default maximum back-off time used by ServicePartitionResolver's ResolveAsync method before retrying, when it is invoked without explicitly specifying the maxRetryBackoffInterval argument.</span></span> <span data-ttu-id="d83a8-122">既定値は、5 秒です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-122">The default value is 5 seconds.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultResolveTimeout">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultResolveTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultResolveTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultResolveTimeout As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultResolveTimeout : TimeSpan" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d83a8-123">既定値は、try の ResolveAsync メソッドで使用される単位のタイムアウトを解決する<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />resolveTimeoutPerTry 引数を明示的に指定することがなく呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="d83a8-123">The default resolve timeout per try used by the ResolveAsync method of <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /> when it is invoked without explicitly specifying the resolveTimeoutPerTry argument.</span></span> <span data-ttu-id="d83a8-124">既定値は 30 秒です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-124">The default value is 30 seconds.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver GetDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetDefault () As ServicePartitionResolver" />
      <MemberSignature Language="F#" Value="static member GetDefault : unit -&gt; Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.GetDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d83a8-125">ServicePartitionResolver 既定値を取得します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-125">Gets the default ServicePartitionResolver.</span></span>
            <span data-ttu-id="d83a8-126"><remarks><para>既定のサービス パーティションの競合回避モジュール インスタンスがローカルを使用して<see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">fabric クライアント</see>です。適切なエンドポイントまたは FabricClient を使用して ServicePartitionResolver を作成し、既定値を更新する方法を推奨は、リモート クラスターで実行されているサービスを解決するのには、ServicePartitionResolver を使用している場合ServicePartitionResolver です。</para></remarks></span><span class="sxs-lookup"><span data-stu-id="d83a8-126"><remarks><para> The default service partition resolver instance uses the local <see href="https://docs.microsoft.com/en-us/dotnet/api/system.fabric.fabricclient#System_Fabric_FabricClient__ctor">fabric client</see>. If you are using the ServicePartitionResolver to resolve services that are running on a remote cluster, the recommended practice is to create a ServicePartitionResolver using the appropriate endpoints or FabricClient and then update the default ServicePartitionResolver. </para></remarks></span></span></summary>
        <returns><span data-ttu-id="d83a8-127">既定値<see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></span><span class="sxs-lookup"><span data-stu-id="d83a8-127">Default <see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" /></span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : System.Fabric.ResolvedServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="d83a8-128">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</span><span class="sxs-lookup"><span data-stu-id="d83a8-128">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="d83a8-129">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-129">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="d83a8-130">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-130">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="d83a8-131">指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />再試行可能エラー時に戻る/再試行を持つメソッドです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-131">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method with back-off/retry on retry-able errors.</span></span> <span data-ttu-id="d83a8-132">これには、解決済みのサービス パーティション内に、ResolveAsync() メソッドの以前の呼び出しを使用した取得しました。</span><span class="sxs-lookup"><span data-stu-id="d83a8-132">This takes in the resolved service partition that was got via an earlier invocation of the ResolveAsync() method.</span></span> <span data-ttu-id="d83a8-133">このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-133">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d83a8-134">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-134">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="d83a8-135">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d83a8-135">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="d83a8-136">このメソッドは、すべての一時的な例外で再試行します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-136">This method retries on all transient exceptions.</span></span> <span data-ttu-id="d83a8-137">このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-137">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="d83a8-138">このメソッドは、サービスが以前に解決されましたが、クラスター内に存在がなくなった場合、FabricServiceNotFoundExcepion をスローできます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-138">This method can throw a FabricServiceNotFoundExcepion if the service which was resolved previously is no longer present in the cluster.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="d83a8-139">解決するのには、サービス インスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-139">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="d83a8-140"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-140"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="d83a8-141"><see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-141">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="d83a8-142">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-142">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="d83a8-143">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-143">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="d83a8-144">指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-144">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method.</span></span> <span data-ttu-id="d83a8-145">既定の設定を使用してこの<see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">タイムアウト</see>と<see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">バックオフ再試行</see>間隔。</span><span class="sxs-lookup"><span data-stu-id="d83a8-145">This uses the default settings for <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultResolveTimeout">timeout</see> and <see cref="F:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.DefaultMaxRetryBackoffInterval">back-off retry</see> intervals.</span></span>
            </para>
        </summary>
        <returns>
            <span data-ttu-id="d83a8-146">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-146">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="d83a8-147">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d83a8-147">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="d83a8-148">このメソッドは、すべての一時的な例外で再試行します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-148">This method retries on all transient exceptions.</span></span> <span data-ttu-id="d83a8-149">このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-149">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="d83a8-150">指定した serviceUri に一致するクラスターでサービス インスタンスがない場合、このメソッドは、FabricServiceNotFoundExcepion をスローできます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-150">This method can throw a FabricServiceNotFoundExcepion if there is no service instance in the cluster matching the specified serviceUri.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="d83a8-151">このメソッドは、ServicePartitionKey で指定されたスキームがサービス インスタンスの作成に使用されるスキームと一致しない場合、FabricException をスローできます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-151">This method can throw a FabricException if the scheme specified in the ServicePartitionKey doesn't match the scheme used to create the service instance.</span></span>
            <span data-ttu-id="d83a8-152">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">エラーと例外</see>FabricClient の一般的な障害を処理するためです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-152">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Errors and Exceptions</see> for handling common FabricClient failures.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (System.Fabric.ResolvedServicePartition previousRsp, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Fabric.ResolvedServicePartition previousRsp, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : System.Fabric.ResolvedServicePartition * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (previousRsp, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Fabric.ResolvedServicePartition,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousRsp" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="previousRsp"><span data-ttu-id="d83a8-153">クライアントが ResolveAsync() メソッドの以前の呼び出しから取得した解決済みのサービス パーティション。</span><span class="sxs-lookup"><span data-stu-id="d83a8-153">The resolved service partition that the client got from the earlier invocation of the ResolveAsync() method.</span></span></param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="d83a8-154">FabricClient に渡されるタイムアウト<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド</span><span class="sxs-lookup"><span data-stu-id="d83a8-154">The timeout passed to FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method</span></span> </param>
        <param name="maxRetryBackoffInterval">
          <para>
            <span data-ttu-id="d83a8-155">ときに再試行する前にバックオフする最大間隔 FabricClient の<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド再試行可能例外で失敗します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-155">The max interval to back-off before retrying when FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method fails with a retry-able exception.</span></span> <span data-ttu-id="d83a8-156">元に戻し間隔には、実際にはランダムな時間間隔が指定された maxRetryBackoffInterval 小さいします。</span><span class="sxs-lookup"><span data-stu-id="d83a8-156">The actual back off interval is a random time interval which is less than or equal to the specified maxRetryBackoffInterval.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="d83a8-157">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-157">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="d83a8-158">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-158">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="d83a8-159">指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />再試行可能エラー時に戻る/再試行を持つメソッドです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-159">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method with back-off/retry on retry-able errors.</span></span> <span data-ttu-id="d83a8-160">これには、解決済みのサービス パーティション内に、ResolveAsync() メソッドの以前の呼び出しを使用した取得しました。</span><span class="sxs-lookup"><span data-stu-id="d83a8-160">This takes in the resolved service partition that was got via an earlier invocation of the ResolveAsync() method.</span></span> <span data-ttu-id="d83a8-161">このメソッドのオーバー ロードは、クライアントが、解決済みのサービス パーティションを持つことが有効ではなくなったことを確認する場合に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-161">This method overload is used in cases where the client knows that the resolved service partition that it has is no longer valid.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d83a8-162">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-162">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="d83a8-163">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d83a8-163">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="d83a8-164">このメソッドは、すべての一時的な例外で再試行します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-164">This method retries on all transient exceptions.</span></span> <span data-ttu-id="d83a8-165">このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-165">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="d83a8-166">このメソッドは、サービスが以前に解決されましたが、クラスター内に存在がなくなった場合、FabricServiceNotFoundExcepion をスローできます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-166">This method can throw a FabricServiceNotFoundExcepion if the service which was resolved previously is no longer present in the cluster.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveAsync (Uri serviceUri, Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, TimeSpan resolveTimeoutPerTry, TimeSpan maxRetryBackoffInterval, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveAsync(class System.Uri serviceUri, class Microsoft.ServiceFabric.Services.Client.ServicePartitionKey partitionKey, valuetype System.TimeSpan resolveTimeoutPerTry, valuetype System.TimeSpan maxRetryBackoffInterval, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;&#xA;override this.ResolveAsync : Uri * Microsoft.ServiceFabric.Services.Client.ServicePartitionKey * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="servicePartitionResolver.ResolveAsync (serviceUri, partitionKey, resolveTimeoutPerTry, maxRetryBackoffInterval, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Client.IServicePartitionResolver.ResolveAsync(System.Uri,Microsoft.ServiceFabric.Services.Client.ServicePartitionKey,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceUri" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionKey" />
        <Parameter Name="resolveTimeoutPerTry" Type="System.TimeSpan" />
        <Parameter Name="maxRetryBackoffInterval" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceUri"><span data-ttu-id="d83a8-167">解決するのには、サービス インスタンスの名前です。</span><span class="sxs-lookup"><span data-stu-id="d83a8-167">Name of the service instance to resolve.</span></span></param>
        <param name="partitionKey">
          <para>
            <span data-ttu-id="d83a8-168"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">キー</see>サービス インスタンスの対象のパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-168"><see cref="T:Microsoft.ServiceFabric.Services.Client.ServicePartitionKey">Key</see> that determines the target partition of the service instance.</span></span> <span data-ttu-id="d83a8-169"><see cref="T:System.Fabric.ServicePartitionKind">パーティション</see>で指定されてキーは、パーティション スキームの一致使用サービス インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-169">The <see cref="T:System.Fabric.ServicePartitionKind">partitioning scheme</see> specified in the key should match the partitioning scheme used to create the service instance.</span></span>
            </para>
        </param>
        <param name="resolveTimeoutPerTry"><span data-ttu-id="d83a8-170">FabricClient に渡されるタイムアウト<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-170">The timeout passed to FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method.</span></span></param>
        <param name="maxRetryBackoffInterval">
          <para>
            <span data-ttu-id="d83a8-171">ときに再試行する前にバックオフする最大間隔 FabricClient の<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッド再試行可能例外で失敗します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-171">The max interval to back-off before retrying when FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />method fails with a retry-able exception.</span></span> <span data-ttu-id="d83a8-172">元に戻し間隔には、実際にはランダムな時間間隔が指定された maxRetryBackoffInterval 小さいします。</span><span class="sxs-lookup"><span data-stu-id="d83a8-172">The actual back off interval is a random time interval which is less than or equal to the specified maxRetryBackoffInterval.</span></span>
            </para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="d83a8-173">この CancellationToken は、この操作を確認します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-173">The CancellationToken that this operation is observing.</span></span> <span data-ttu-id="d83a8-174">取り消す必要がある操作の通知に使用されます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-174">It is used to notify the operation that it should be canceled.</span></span>
            </para>
        </param>
        <summary>
            <span data-ttu-id="d83a8-175">指定されたサービスのパーティションを FabricClient を呼び出すことによって解決<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />メソッドを指定したタイムアウトと再試行可能エラー時に戻る/再試行します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-175">Resolves a partition of the specified service by invoking FabricClient's <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> method with the given timeout and back-off/retry on retry-able errors.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d83a8-176">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="d83a8-176">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="d83a8-177">タスクから結果が、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス エンドポイントを含む、解決済みのサービス パーティションに関する情報を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d83a8-177">The result from the task is the <see cref="T:System.Fabric.ResolvedServicePartition" /> object, that contains the information about the resolved service partition including the service endpoints.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="d83a8-178">このメソッドは、すべての一時的な例外で再試行します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-178">This method retries on all transient exceptions.</span></span> <span data-ttu-id="d83a8-179">このメソッドの最大実行時間を制限する場合、作成する必要があります、<see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">その最大実行時間に関連付けられたキャンセル トークン</see>そのキャンセル トークンをこのメソッドに渡します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-179">For cases where you want to limit the max execution time of this method, you should create a <see href="https://docs.microsoft.com/en-us/dotnet/core/api/system.threading.cancellationtokensource#System_Threading_CancellationTokenSource__ctor_System_TimeSpan_">cancellation token associated with that max execution time</see> and pass that cancellation token to this method.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricServiceNotFoundException">
          <para>
            <span data-ttu-id="d83a8-180">指定した serviceUri に一致するクラスターでサービス インスタンスがない場合、このメソッドは、FabricServiceNotFoundExcepion をスローできます。</span><span class="sxs-lookup"><span data-stu-id="d83a8-180">This method can throw a FabricServiceNotFoundExcepion if there is no service instance in the cluster matching the specified serviceUri.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="d83a8-181">ServicePartitionKey で指定されたスキームがサービス インスタンスの作成に使用されるスキームと一致しない場合は、FabricException がスローします。</span><span class="sxs-lookup"><span data-stu-id="d83a8-181">This can throw a FabricException if the scheme specified in the ServicePartitionKey doesn't match the scheme used to create the service instance.</span></span>
            <span data-ttu-id="d83a8-182">関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">エラーと例外</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="d83a8-182">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/">Errors and Exceptions</see> for more information.</span></span>
            </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefault">
      <MemberSignature Language="C#" Value="public static void SetDefault (Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void SetDefault(class Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver defaultServiceResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault(Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub SetDefault (defaultServiceResolver As ServicePartitionResolver)" />
      <MemberSignature Language="F#" Value="static member SetDefault : Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver -&gt; unit" Usage="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver.SetDefault defaultServiceResolver" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="defaultServiceResolver" Type="Microsoft.ServiceFabric.Services.Client.ServicePartitionResolver" />
      </Parameters>
      <Docs>
        <param name="defaultServiceResolver"><span data-ttu-id="d83a8-183">新しい既定値</span><span class="sxs-lookup"><span data-stu-id="d83a8-183">The new default value</span></span></param>
        <summary>
            <span data-ttu-id="d83a8-184">ServicePartitionResolver 既定値を更新します。</span><span class="sxs-lookup"><span data-stu-id="d83a8-184">Updates the default ServicePartitionResolver.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>