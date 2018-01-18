<Type Name="TcpRelayConnectionMode" FullName="Microsoft.ServiceBus.TcpRelayConnectionMode">
  <TypeSignature Language="C#" Value="public enum TcpRelayConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TcpRelayConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum TcpRelayConnectionMode" />
  <TypeSignature Language="F#" Value="type TcpRelayConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="b055b-101">接続モードをについて説明します、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="b055b-101">Describes the connection mode for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Hybrid">
      <MemberSignature Language="C#" Value="Hybrid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Hybrid = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberSignature Language="VB.NET" Value="Hybrid" />
      <MemberSignature Language="F#" Value="Hybrid = 1" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="b055b-102">通信は、クライアントとサービスのエンドポイントが互いに直接ソケット接続をネゴシエート中に、Azure Service Bus インフラストラクチャを介して中継されます。</span><span class="sxs-lookup"><span data-stu-id="b055b-102">Communication is relayed through the Azure Service Bus infrastructure while the Client and Service endpoints negotiate a direct socket connection to each other.</span></span> <span data-ttu-id="b055b-103">この直接接続の調整は、Azure Service Bus クラウド サービスによって制御されます。</span><span class="sxs-lookup"><span data-stu-id="b055b-103">The coordination of this direct connection is governed by the Azure Service Bus cloud service.</span></span> <span data-ttu-id="b055b-104">直接ソケット接続アルゴリズムはファイアウォールや NAT の両後ろに配置された 2 つのパーティ間の直接接続を確立できるデバイス。</span><span class="sxs-lookup"><span data-stu-id="b055b-104">The direct socket connection algorithm is capable of establishing direct connections between two parties that sit behind opposing Firewalls and NAT devices.</span></span> <span data-ttu-id="b055b-105">アルゴリズムはファイアウォール トラバーサルで発信接続のみを使用して、NAT トラバーサル用相互ポート予測アルゴリズムに依存しています。</span><span class="sxs-lookup"><span data-stu-id="b055b-105">The algorithm uses only outbound connections for Firewall traversal and relies on a mutual port prediction algorithm for NAT traversal.</span></span> <span data-ttu-id="b055b-106">アルゴリズムがクライアントの数が少ないホーム ネットワークまたは小規模ビジネスのシナリオは非常に高い成功率に NAT トラバーサル アルゴリズムが非常に限定された時間指定の調整と NAT に予期される動作は最善の推測の予測に依存するので、大きな Nat とその成功率が低下するとします。</span><span class="sxs-lookup"><span data-stu-id="b055b-106">Since the NAT traversal algorithm is dependent on a very narrowly timed coordination and a best-guess prediction about the expected NAT behavior, the algorithm tends to have a very high success rate for Home and Small Business scenarios with a small number of clients and degrades in its success rate with larger NATs.</span></span> <span data-ttu-id="b055b-107">直接接続を確立することができる場合、リレー接続はメッセージまたはデータを失わずに直接接続を自動的にアップグレードします。</span><span class="sxs-lookup"><span data-stu-id="b055b-107">If a direct connection can be established, the relayed connection is automatically upgraded to the direct connection without message or data loss.</span></span> <span data-ttu-id="b055b-108">直接接続を確立できない場合は、データを Azure Service Bus リレーを通過継続されます。</span><span class="sxs-lookup"><span data-stu-id="b055b-108">If the direct connection cannot be established, data will continue to flow through the Azure Service Bus Relay.</span></span> 
            
            <span data-ttu-id="b055b-109">さらに、このモードでは、NAT 予測アルゴリズムの送信ポート 819 が必要です。</span><span class="sxs-lookup"><span data-stu-id="b055b-109">This mode additionally requires outbound port 819 for the NAT prediction algorithm.</span></span> <span data-ttu-id="b055b-110">多くの個人のファイアウォール製品の直接によって確立されているが送信ソケットを接続接続モードも必要になります (個人用の Windows ファイアウォールと他の製品が通常プロンプトを表示、ユーザーを許可する、1 回限りのポリシー例外ユーザー)、ホスト アプリケーションにします。</span><span class="sxs-lookup"><span data-stu-id="b055b-110">With most personal firewall products, the outbound socket connection that is being established by the direct connect mode will also require a one-time policy exception to be granted by the user (the Windows Personal Firewall and other products will typically prompt the user) to the hosting application.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Relayed">
      <MemberSignature Language="C#" Value="Relayed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Relayed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberSignature Language="VB.NET" Value="Relayed" />
      <MemberSignature Language="F#" Value="Relayed = 0" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="b055b-111">すべての通信は、Azure Service Bus クラウドを介して中継されます。</span><span class="sxs-lookup"><span data-stu-id="b055b-111">All communication is relayed through the Azure Service Bus cloud.</span></span> <span data-ttu-id="b055b-112">SSL で保護された制御接続を使用して、クライアント サービスのすべての通信を通過するリレー型のエンド ツー エンドのソケット接続をネゴシエートします。</span><span class="sxs-lookup"><span data-stu-id="b055b-112">The SSL-protected control connection is used to negotiate a relayed end-to-end socket connection that all Client-Service communication flows through.</span></span> <span data-ttu-id="b055b-113">接続が確立されると、Azure Service Bus のインフラストラクチャは非常によく似た双方向のバイト ストリームをリレーするソケット フォワーダー プロキシという役割を果たします。</span><span class="sxs-lookup"><span data-stu-id="b055b-113">After the connection is established, the Azure Service Bus infrastructure acts much like a socket forwarder proxy relaying a bidirectional byte stream.</span></span> <span data-ttu-id="b055b-114">さらに、このモードでは、NAT 予測アルゴリズムの送信ポート 819 が必要です。</span><span class="sxs-lookup"><span data-stu-id="b055b-114">This mode additionally requires outbound port 819 for the NAT prediction algorithm.</span></span> <span data-ttu-id="b055b-115">多くの個人のファイアウォール製品の直接によって確立されているが送信ソケットを接続接続モードも必要になります (個人用の Windows ファイアウォールと他の製品が通常プロンプトを表示、ユーザーを許可する、1 回限りのポリシー例外ユーザー)、ホスト アプリケーションにします。</span><span class="sxs-lookup"><span data-stu-id="b055b-115">With most personal firewall products, the outbound socket connection that is being established by the direct connect mode will also require a one-time policy exception to be granted by the user (the Windows Personal Firewall and other products will typically prompt the user) to the hosting application.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>