<Type Name="StatelessService" FullName="Microsoft.ServiceFabric.Services.Runtime.StatelessService">
  <TypeSignature Language="C#" Value="public abstract class StatelessService" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit StatelessService extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class StatelessService" />
  <TypeSignature Language="F#" Value="type StatelessService = class&#xA;    interface IStatelessUserServiceInstance" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fe654-101">ステートレス リライアブル サービス基本クラスを表す Microsoft Service Fabric に基づいています。</span><span class="sxs-lookup"><span data-stu-id="fe654-101">Represents the Microsoft Service Fabric based stateless reliable service base class.</span></span> <span data-ttu-id="fe654-102">Microsoft Service Fabric が基づくステートレス リライアブル サービスを実装するには、このクラスから派生します。</span><span class="sxs-lookup"><span data-stu-id="fe654-102">Derive from this class to implement a Microsoft Service Fabric based stateless reliable service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected StatelessService (System.Fabric.StatelessServiceContext serviceContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.#ctor(System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (serviceContext As StatelessServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Runtime.StatelessService : System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService" Usage="new Microsoft.ServiceFabric.Services.Runtime.StatelessService serviceContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
            <span data-ttu-id="fe654-103">A<see cref="T:System.Fabric.StatelessServiceContext" />サービス コンテキストをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="fe654-103">A <see cref="T:System.Fabric.StatelessServiceContext" /> that describes the service context.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fe654-104">新しい <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" /> のインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="fe654-104">Creates a new <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatelessService" /> instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException" />
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public System.Fabric.StatelessServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.StatelessServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As StatelessServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : System.Fabric.StatelessServiceContext" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.StatelessServiceContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe654-105">このステートレス サービスが動作しているサービス コンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="fe654-105">Gets the service context that this stateless service is operating under.</span></span> <span data-ttu-id="fe654-106">InstanceId、PartitionId ServiceName などのような情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="fe654-106">It provides information like InstanceId, PartitionId, ServiceName etc.</span></span>
            </summary>
        <value>
            <span data-ttu-id="fe654-107">A<see cref="T:System.Fabric.StatelessServiceContext" />サービス コンテキストをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="fe654-107">A <see cref="T:System.Fabric.StatelessServiceContext" /> that describes the service context.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceInstanceListeners">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceInstanceListeners() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.CreateServiceInstanceListeners" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateServiceInstanceListeners () As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="abstract member CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;&#xA;override this.CreateServiceInstanceListeners : unit -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;" Usage="statelessService.CreateServiceInstanceListeners " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.CreateServiceInstanceListeners</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe654-108">サービス インスタンスの通信リスナーを指定するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="fe654-108">Override this method to supply the communication listeners for the service instance.</span></span> <span data-ttu-id="fe654-109">通信リスナーのによって返されるエンドポイントが ListenerName の JSON 文字列として格納されているなどの文字列のエンドポイントのペア {「エンドポイント」: {"Listener1":"Endpoint1"、"Listener2":"Endpoint2"...}}</span><span class="sxs-lookup"><span data-stu-id="fe654-109">The endpoints returned by the communication listener's are stored as a JSON string of ListenerName, Endpoint string pairs like {"Endpoints":{"Listener1":"Endpoint1","Listener2":"Endpoint2" ...}}</span></span>
            <span data-ttu-id="fe654-110"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="fe654-110"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns><span data-ttu-id="fe654-111">ServiceInstanceListeners の一覧</span><span class="sxs-lookup"><span data-stu-id="fe654-111">List of ServiceInstanceListeners</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAddresses">
      <MemberSignature Language="C#" Value="protected System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; GetAddresses ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; GetAddresses() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.GetAddresses" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetAddresses () As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.GetAddresses : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="statelessService.GetAddresses " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe654-112">すべてのアドレスの一覧のこのサービス インスタンスとして取得 (ListenerName、エンドポイント) キーと値のペア。</span><span class="sxs-lookup"><span data-stu-id="fe654-112">Gets the list of all the addresses for this service instance as (ListenerName, Endpoint) key-value pair.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fe654-113"><see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> (ListenerName、エンドポイント) とアドレスの一覧を含むキーと値のペア。</span><span class="sxs-lookup"><span data-stu-id="fe654-113">An <see cref="T:System.Collections.Generic.IReadOnlyDictionary`2" /> containing list of addresses as (ListenerName, Endpoint) key-value pair.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="statelessService.OnAbort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnAbort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fe654-114">通知サービスを中止しています。</span><span class="sxs-lookup"><span data-stu-id="fe654-114">Notification that the service is being aborted.</span></span>  <span data-ttu-id="fe654-115">RunAsync は、取り消し処理は中止パスには待機されなかったとして、このメソッドの実行と同時に実行可能性があります。</span><span class="sxs-lookup"><span data-stu-id="fe654-115">RunAsync MAY be running concurrently with the execution of this method, as cancellation is not awaited on the abort path.</span></span>
            <span data-ttu-id="fe654-116"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="fe654-116"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnCloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="fe654-117">キャンセル要求を監視する指定されたキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe654-117">Cancellation token provided to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="fe654-118">サービスを閉じるための最後の手順として、このメソッドが呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="fe654-118">This method is called as the final step of closing the service.</span></span>
            <span data-ttu-id="fe654-119">このインスタンスの内部コンポーネントの終了が完了したことを通知するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="fe654-119">Override this method to be notified that Close has completed for this instance's internal components.</span></span>
            <span data-ttu-id="fe654-120"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="fe654-120"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="fe654-121">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="fe654-121">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.OnOpenAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.OnOpenAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.OnOpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="fe654-122">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe654-122">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="fe654-123">このメソッドは、サービスを開くの最後の手順として呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="fe654-123">This method is called as the final step of opening the service.</span></span>
            <span data-ttu-id="fe654-124">このインスタンスの内部コンポーネントのオープンが完了したことを通知するには、このメソッドをオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="fe654-124">Override this method to be notified that Open has completed for this instance's internal components.</span></span>
            <span data-ttu-id="fe654-125"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="fe654-125"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="fe654-126">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="fe654-126">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partition">
      <MemberSignature Language="C#" Value="protected System.Fabric.IStatelessServicePartition Partition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.IStatelessServicePartition Partition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property Partition As IStatelessServicePartition" />
      <MemberSignature Language="F#" Value="member this.Partition : System.Fabric.IStatelessServicePartition" Usage="Microsoft.ServiceFabric.Services.Runtime.StatelessService.Partition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IStatelessServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fe654-127">サービスを現在のサービス インスタンスが属するパーティションをします。</span><span class="sxs-lookup"><span data-stu-id="fe654-127">Service partition to which current service instance belongs.</span></span> 
            </summary>
        <value>
            <span data-ttu-id="fe654-128"><see cref="T:System.Fabric.IStatelessServicePartition" />を表す、このサービス レプリカが属しているパーティション。</span><span class="sxs-lookup"><span data-stu-id="fe654-128">An <see cref="T:System.Fabric.IStatelessServicePartition" /> that represents the partition to which this service replica belongs.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task RunAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task RunAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RunAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="statelessService.RunAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Runtime.IStatelessUserServiceInstance.RunAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="fe654-129">キャンセル要求を監視するキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fe654-129">Cancellation token to monitor for cancellation requests.</span></span></param>
        <summary>
            <span data-ttu-id="fe654-130">サービスが、サービスが表示されたら、動作するバック グラウンド タスクを実装するには、ロジックでこのメソッドをオーバーライドする必要があります。</span><span class="sxs-lookup"><span data-stu-id="fe654-130">Services that want to implement a background task, which runs when the service comes up, should override this method with their logic.</span></span>
            <span data-ttu-id="fe654-131"><para>信頼性の高いサービス ライフ サイクルに関する情報を参照してください https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle</para></span><span class="sxs-lookup"><span data-stu-id="fe654-131"><para> For information about Reliable Services life cycle please see https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-lifecycle </para></span></span></summary>
        <returns>
            <span data-ttu-id="fe654-132">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="fe654-132">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fe654-133">オーバーライドする場合は、これらのガイドラインに従うようにしてください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"> <item> <description>確認<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />が実行と通知を受けた、1 回<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />として適切に終了します。できるだけ早くです。場合に注意してください<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、目的の操作が完了を待つ必要はありません<paramref name="cancellationToken" />シグナル状態になる正常に返すことができます。</description></item><item><description>Service Fabric ランタイムがエスケープからすべての例外を処理しない<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />です。未処理の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムには、次のアクション、: <list type="bullet"> <item> <description>場合、 <see cref="T:System.Fabric.FabricException" /> (またはその派生例外のいずれか) からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabricランタイムは、このサービス インスタンスをドロップして、新しいインスタンスが作成されます。ヘルスの警告は、未処理の例外に関する詳細を含む Service Fabric Explorer に表示されます。</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムは、通知することによって取り消しを要求しましたが、<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、Service Fabric ランタイムは、この例外を処理し、として正常に完了であると判断<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />.</description></item><item><description>場合、<see cref="T:System.OperationCanceledException" />からエスケープ<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />Service Fabric ランタイムに通知することによって取り消しを要求されません<paramref name="cancellationToken" />に渡される<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />、このサービス インスタンスをホストしているプロセスが終了します。これは、同じプロセスでホストされているその他のすべてのサービス インスタンスに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item><item><description>その他の種類の例外をからエスケープする場合<see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />このサービス インスタンスをホストしているプロセスが終了し、します。これは、同じプロセスでホストされているその他のすべてのサービス インスタンスに影響します。未処理の例外に関する詳細な情報は、Windows イベント ビューアーで表示できます。</description></item></list></description></item></list><para>準拠するように失敗しているこれらのガイドラインにフェールオーバー、再構成またはスタックを取得するようにサービスのアップグレードが発生することができ、サービスの可用性に影響を与えることができます。</para></span><span class="sxs-lookup"><span data-stu-id="fe654-133">Please ensure you follow these guidelines when overriding <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />: <list type="bullet"><item><description> Make sure <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> is honored and once it has been signaled, <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> exits gracefully as soon as possible. Please note that if <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> has finished its intended work, it does not need to wait for <paramref name="cancellationToken" /> to be signaled and can return gracefully. </description></item><item><description> Service Fabric runtime does not handle all exception(s) escaping from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. If an unhandled exception escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, then Service Fabric runtime takes following action(s): <list type="bullet"><item><description> If a <see cref="T:System.Fabric.FabricException" /> (or one of its derived exception) escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime will drop this service instance and a new instance will be created. A health warning will be appear in Service Fabric Explorer containing details about unhandled exception. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, Service Fabric runtime handles this exception and considers it as graceful completion of <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />. </description></item><item><description> If an <see cref="T:System.OperationCanceledException" /> escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> and Service Fabric runtime has NOT requested cancellation by signaling <paramref name="cancellationToken" /> passed to <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" />, the process that is hosting this service instance is brought down. This will impact all other service instances that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item><item><description> If an exception of any other type escapes from <see cref="M:Microsoft.ServiceFabric.Services.Runtime.StatelessService.RunAsync(System.Threading.CancellationToken)" /> then the process that is hosting this service instance is brought down. This will impact all other service instances that are hosted by the same process. The details about unhandled exceptions can be viewed in Windows Event Viewer. </description></item></list></description></item></list><para> Failing to conform to these guidelines can cause fail-over, reconfiguration or upgrade of your service to get stuck and can impact availability of your service. </para></span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>