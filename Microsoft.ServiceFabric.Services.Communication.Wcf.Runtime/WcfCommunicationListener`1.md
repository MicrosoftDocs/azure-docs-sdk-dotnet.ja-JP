<Type Name="WcfCommunicationListener&lt;TServiceContract&gt;" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;TServiceContract&gt;">
  <TypeSignature Language="C#" Value="public class WcfCommunicationListener&lt;TServiceContract&gt; : Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfCommunicationListener`1&lt;TServiceContract&gt; extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfCommunicationListener(Of TServiceContract)&#xA;Implements ICommunicationListener" />
  <TypeSignature Language="F#" Value="type WcfCommunicationListener&lt;'ServiceContract&gt; = class&#xA;    interface ICommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TServiceContract" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TServiceContract"><span data-ttu-id="17eed-101">WCF サービス コントラクトの型。</span><span class="sxs-lookup"><span data-stu-id="17eed-101">Type of the WCF service contract.</span></span></typeparam>
    <summary>
            <span data-ttu-id="17eed-102">Service Fabric 用 Windows Communication Foundation のベースのリスナーは、ステートレスまたはステートフルなサービスを基づいています。</span><span class="sxs-lookup"><span data-stu-id="17eed-102">A Windows Communication Foundation based listener for Service Fabric based stateless or stateful service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="17eed-103">この通信リスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="17eed-103">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="17eed-104">WCF サービスが指定された WCF サービス コントラクトを実装します。</span><span class="sxs-lookup"><span data-stu-id="17eed-104">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <summary>
                <span data-ttu-id="17eed-105">既定のバインディングと既定のエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="17eed-105">Constructs a WCF based communication listener that uses default binding and default endpoint address.</span></span>
            </summary>
        <remarks>
          <para>
                    <span data-ttu-id="17eed-106">使用して、既定のリスナーのバインドを作成<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-106">The default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </para>
          <para>
                    <span data-ttu-id="17eed-107">サービス マニフェストで定義されているエンドポイント リソースを使用して、既定のエンドポイント アドレスが作成されます。</span><span class="sxs-lookup"><span data-stu-id="17eed-107">The default endpoint address is created using the endpoint resource defined in the service manifest.</span></span> <span data-ttu-id="17eed-108">エンドポイント リソースの名前は、WCF サービス コントラクトを使用して型から派生<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-108">The name of the endpoint resource is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                    <span data-ttu-id="17eed-109">サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。</span><span class="sxs-lookup"><span data-stu-id="17eed-109">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                    </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, System.ServiceModel.EndpointAddress address = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, class System.ServiceModel.EndpointAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.ServiceModel.EndpointAddress)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * System.ServiceModel.EndpointAddress -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, address)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="address" Type="System.ServiceModel.EndpointAddress" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="17eed-110">この通信リスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="17eed-110">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="17eed-111">WCF サービスが指定された WCF サービス コントラクトを実装します。</span><span class="sxs-lookup"><span data-stu-id="17eed-111">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <param name="listenerBinding">
                <span data-ttu-id="17eed-112">WCF エンドポイントで使用するバインディング。</span><span class="sxs-lookup"><span data-stu-id="17eed-112">The binding to use for the WCF endpoint.</span></span> <span data-ttu-id="17eed-113">使用して既定のリスナーをバインディングを作成する場合は、listenerBinding が指定されていないか、null である、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-113">If the listenerBinding is not specified or it is null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </param>
        <param name="address">
                <span data-ttu-id="17eed-114">WCF エンドポイントのリッスン アドレスです。</span><span class="sxs-lookup"><span data-stu-id="17eed-114">The listen address for the WCF endpoint.</span></span> <span data-ttu-id="17eed-115">アドレスが指定されていないか、null である、既定のアドレスがサービス マニフェストのエンドポイント リソースの参照によって作成されます。</span><span class="sxs-lookup"><span data-stu-id="17eed-115">If the address is not specified or it is null, a default address is created by looking up the endpoint resource from the service manifest.</span></span> <span data-ttu-id="17eed-116">エンドポイントのリソース名は、WCF サービス コントラクトを使用して型から派生<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-116">The endpoint resource name is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                <span data-ttu-id="17eed-117">サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。</span><span class="sxs-lookup"><span data-stu-id="17eed-117">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="17eed-118">指定されたリスナーのバインドと指定したエンドポイント アドレスから派生したエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="17eed-118">Constructs a WCF based communication listener that uses specified listener binding and endpoint address derived from the specified endpoint address.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfCommunicationListener (System.Fabric.ServiceContext serviceContext, TServiceContract wcfServiceObject, System.ServiceModel.Channels.Binding listenerBinding = null, string endpointResourceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, !TServiceContract wcfServiceObject, class System.ServiceModel.Channels.Binding listenerBinding, string endpointResourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.#ctor(System.Fabric.ServiceContext,`0,System.ServiceModel.Channels.Binding,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; : System.Fabric.ServiceContext * 'ServiceContract * System.ServiceModel.Channels.Binding * string -&gt; Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;" Usage="new Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt; (serviceContext, wcfServiceObject, listenerBinding, endpointResourceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="wcfServiceObject" Type="TServiceContract" />
        <Parameter Name="listenerBinding" Type="System.ServiceModel.Channels.Binding" />
        <Parameter Name="endpointResourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceContext">
                <span data-ttu-id="17eed-119">この通信リスナーが構築される、サービスのコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="17eed-119">The context of the service for which this communication listener is being constructed.</span></span>
            </param>
        <param name="wcfServiceObject">
                <span data-ttu-id="17eed-120">WCF サービスが指定された WCF サービス コントラクトを実装します。</span><span class="sxs-lookup"><span data-stu-id="17eed-120">WCF service implementing the specified WCF service contract.</span></span>
            </param>
        <param name="listenerBinding">
                <span data-ttu-id="17eed-121">WCF エンドポイントで使用するバインディング。</span><span class="sxs-lookup"><span data-stu-id="17eed-121">The binding to use for the WCF endpoint.</span></span> <span data-ttu-id="17eed-122">使用して既定のリスナーをバインディングを作成する場合は、listenerBinding が指定されていないか、null である、<see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-122">If the listenerBinding is not specified or it is null, a default listener binding is created using <see cref="M:Microsoft.ServiceFabric.Services.Communication.Wcf.WcfUtility.CreateTcpListenerBinding(System.Int64,System.TimeSpan,System.TimeSpan)" /> method.</span></span>
                </param>
        <param name="endpointResourceName">
                <span data-ttu-id="17eed-123">アドレスをリスナーの作成に使用するサービス マニフェストで定義されているエンドポイント リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="17eed-123">The name of the endpoint resource defined in the service manifest that should be used to create the address for the listener.</span></span> <span data-ttu-id="17eed-124">WCF サービス コントラクト型を使用して、派生した名前で、endpointResourceName が指定されていない、または null である、<see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />メソッドです。</span><span class="sxs-lookup"><span data-stu-id="17eed-124">If the endpointResourceName is not specified or it is null, its name is derived from the WCF service contract type using <see cref="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" /> method.</span></span>
                <span data-ttu-id="17eed-125">サービス マニフェストには、エンドポイント リソースと一致することが見つかりません、ポート 0 既定エンドポイント リソースの定義が使用されます。</span><span class="sxs-lookup"><span data-stu-id="17eed-125">If matching endpoint resource is not found in the service manifest, a default endpoint resource definition with port zero is used.</span></span>
                </param>
        <summary>
                <span data-ttu-id="17eed-126">指定されたリスナーのバインドと、指定したエンドポイント リソース名から派生したエンドポイント アドレスを使用する通信リスナーを WCF 構成要素に基づいています。</span><span class="sxs-lookup"><span data-stu-id="17eed-126">Constructs a WCF based communication listener that uses specified listener binding and endpoint address derived from the specified endpoint resource name.</span></span>
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort">
      <MemberSignature Language="C#" Value="void ICommunicationListener.Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#Abort" />
      <MemberSignature Language="VB.NET" Value="Sub Abort () Implements ICommunicationListener.Abort" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="17eed-127">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="17eed-127">This method causes the communication listener to close.</span></span> <span data-ttu-id="17eed-128">閉じる終了の状態は、このメソッドは、異常終了への移行。</span><span class="sxs-lookup"><span data-stu-id="17eed-128">Close is a terminal state and this method causes the transition to close ungracefully.</span></span> <span data-ttu-id="17eed-129">このメソッドが呼び出されたときに、(閉じるを含む) の未処理の操作を取り消す必要があります。</span><span class="sxs-lookup"><span data-stu-id="17eed-129">Any outstanding operations (including close) should be canceled when this method is called.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task ICommunicationListener.CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#CloseAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1/&lt;Microsoft-ServiceFabric-Services-Communication-Runtime-ICommunicationListener-CloseAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="17eed-130">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="17eed-130">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="17eed-131">このメソッドによって、通信リスナーを閉じます。</span><span class="sxs-lookup"><span data-stu-id="17eed-131">This method causes the communication listener to close.</span></span> <span data-ttu-id="17eed-132">終了が終了状態と、このメソッドは、安全な方法でこの状態に遷移する通信リスナーを使用します。</span><span class="sxs-lookup"><span data-stu-id="17eed-132">Close is a terminal state and this method allows the communication listener to transition to this state in a graceful manner.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="17eed-133">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="17eed-133">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync">
      <MemberSignature Language="C#" Value="System.Threading.Tasks.Task&lt;string&gt; ICommunicationListener.OpenAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.Microsoft#ServiceFabric#Services#Communication#Runtime#ICommunicationListener#OpenAsync(System.Threading.CancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="17eed-134">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="17eed-134">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="17eed-135">このメソッドによって、通信リスナーを開くことができません。</span><span class="sxs-lookup"><span data-stu-id="17eed-135">This method causes the communication listener to be opened.</span></span> <span data-ttu-id="17eed-136">Open が完了すると、通信リスナーが使用可能になります - 受け付けるし、メッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="17eed-136">Once the Open completes, the communication listener becomes usable - accepts and sends messages.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="17eed-137">A<see cref="T:System.Threading.Tasks.Task">タスク</see>未処理の操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="17eed-137">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="17eed-138">タスクの結果は、エンドポイントの文字列です。</span><span class="sxs-lookup"><span data-stu-id="17eed-138">The result of the Task is the endpoint string.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceHost">
      <MemberSignature Language="C#" Value="public System.ServiceModel.ServiceHost ServiceHost { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.ServiceHost ServiceHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener`1.ServiceHost" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceHost As ServiceHost" />
      <MemberSignature Language="F#" Value="member this.ServiceHost : System.ServiceModel.ServiceHost" Usage="Microsoft.ServiceFabric.Services.Communication.Wcf.Runtime.WcfCommunicationListener&lt;'ServiceContract&gt;.ServiceHost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.ServiceHost</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
                <span data-ttu-id="17eed-139">取得、<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。</span><span class="sxs-lookup"><span data-stu-id="17eed-139">Gets the <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </summary>
        <value>
                <span data-ttu-id="17eed-140">A<see cref="T:System.ServiceModel.ServiceHost" />このリスナーで WCF サービスの実装をホストするために使用します。</span><span class="sxs-lookup"><span data-stu-id="17eed-140">A <see cref="T:System.ServiceModel.ServiceHost" /> used by this listener to host the WCF service implementation.</span></span>
                </value>
        <remarks>
                <span data-ttu-id="17eed-141">サービス ホストは、そのコンス トラクターでリスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="17eed-141">The service host is created by the listener in its constructor.</span></span> <span data-ttu-id="17eed-142">使用して、ランタイムによってこのような通信する前にリスナーが開かれました<see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" />メソッドでは、このプロパティを介してアクセスすると、サービス ホストをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="17eed-142">Before this communication listener is opened by the runtime via <see cref="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener.OpenAsync(System.Threading.CancellationToken)" /> method, the service host can be customized by accessing it via this property.</span></span>
                </remarks>
      </Docs>
    </Member>
  </Members>
</Type>