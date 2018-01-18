<Type Name="ConnectivityMode" FullName="Microsoft.ServiceBus.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="007a9-101">Service Bus との通信に使用される基になるワイヤレベル プロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="007a9-101">Sets the underlying wire-level protocol used to communicate with Service Bus.</span></span> </summary>
    <remarks><span data-ttu-id="007a9-102">接続モードとは異なります、<see cref="T:Microsoft.ServiceBus.Messaging.TransportType" />プロトコル サービスがクライアントとの通信を指定します。</span><span class="sxs-lookup"><span data-stu-id="007a9-102">The connectivity mode differs from the <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> protocol that the service specifies for client communication.</span></span> <span data-ttu-id="007a9-103">トランスポートの種類は、使用するバインディングによって決まります。</span><span class="sxs-lookup"><span data-stu-id="007a9-103">The transport type is determined by the binding used.</span></span> <span data-ttu-id="007a9-104">関係なく<see cref="T:Microsoft.ServiceBus.Messaging.TransportType" />(NetMessaging または AMQP) を選択する、選択した接続モードで、通信が行われます。</span><span class="sxs-lookup"><span data-stu-id="007a9-104">No matter which <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> you select (NetMessaging or AMQP), the communication occurs over the selected connectivity mode.</span></span> <span data-ttu-id="007a9-105">たとえば、AMQP が TCP または HTTP (S) 経由で発生することができます。</span><span class="sxs-lookup"><span data-stu-id="007a9-105">For example, you can have AMQP occur over TCP or HTTP(S).</span></span> </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="007a9-106">自動検出モードです。</span><span class="sxs-lookup"><span data-stu-id="007a9-106">Auto-detect mode.</span></span> <span data-ttu-id="007a9-107">現在のネットワーク環境のいずれかの接続オプションがあるかどうかを調べる自動検出メカニズムに基づいて、TCP、HTTP および HTTPS モード間で自動的に選択します。</span><span class="sxs-lookup"><span data-stu-id="007a9-107">Automatically selects between the TCP, HTTP and HTTPS modes based on an auto-detection mechanism that probes whether either connectivity option is available for the current network environment.</span></span> <span data-ttu-id="007a9-108">両方がある場合、システムでは、既定で TCP を選択します。</span><span class="sxs-lookup"><span data-stu-id="007a9-108">If both are available, the system will choose TCP by default.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="007a9-109">HTTP モードです。</span><span class="sxs-lookup"><span data-stu-id="007a9-109">HTTP mode.</span></span> <span data-ttu-id="007a9-110">リスナーは、メッセージを待って、Service Bus サービスに HTTPS 接続での後に、HTTP 接続を試行します。</span><span class="sxs-lookup"><span data-stu-id="007a9-110">Listeners attempt an HTTP connection followed by an HTTPS connection with the Service Bus service, then wait for messages.</span></span> <span data-ttu-id="007a9-111">簡単に TCP ポートの制約を回避するためよりこれを許可する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="007a9-111">This might allow you to more easily work around TCP port constraints.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Https">
      <MemberSignature Language="C#" Value="Https" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Https = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberSignature Language="VB.NET" Value="Https" />
      <MemberSignature Language="F#" Value="Https = 3" Usage="Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="007a9-112">HTTPS モードです。</span><span class="sxs-lookup"><span data-stu-id="007a9-112">HTTPS mode.</span></span> <span data-ttu-id="007a9-113">リスナーは、Service Bus サービスとの HTTPS 接続を試行し、メッセージを待機します。</span><span class="sxs-lookup"><span data-stu-id="007a9-113">Listeners attempt an HTTPS connection with the Service Bus service, then wait  for messages.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="007a9-114">TCP モード (既定)。</span><span class="sxs-lookup"><span data-stu-id="007a9-114">TCP mode (default).</span></span> <span data-ttu-id="007a9-115">リスナーは、9350 から 9354 の範囲内で宛先ポートに Service Bus サービスへの TCP 接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="007a9-115">Listeners create TCP connections to the Service Bus service to a destination port in the range 9350 to 9354.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>