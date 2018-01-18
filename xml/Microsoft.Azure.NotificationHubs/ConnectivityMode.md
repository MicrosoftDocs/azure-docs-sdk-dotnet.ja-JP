<Type Name="ConnectivityMode" FullName="Microsoft.Azure.NotificationHubs.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="deb96-101">接続モードをについて説明します。</span><span class="sxs-lookup"><span data-stu-id="deb96-101">Describes the connectivity mode.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="deb96-102">自動検出モードです。</span><span class="sxs-lookup"><span data-stu-id="deb96-102">Auto-detect mode.</span></span> <span data-ttu-id="deb96-103">現在のネットワーク環境のいずれかの接続オプションがあるかどうかを調べる自動検出メカニズムに基づいて、TCP、HTTP および HTTPS モード間で自動的に選択します。</span><span class="sxs-lookup"><span data-stu-id="deb96-103">Automatically selects between the TCP, HTTP and HTTPS modes based on an auto-detection mechanism that probes whether either connectivity option is available for the current network environment.</span></span> <span data-ttu-id="deb96-104">両方がある場合、システムでは、既定で TCP を選択します。</span><span class="sxs-lookup"><span data-stu-id="deb96-104">If both are available, the system will choose TCP by default.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="deb96-105">HTTP モードです。</span><span class="sxs-lookup"><span data-stu-id="deb96-105">HTTP mode.</span></span> <span data-ttu-id="deb96-106">リスナーは、Windows Azure Service Bus サービスとメッセージのポーリングを使用した HTTPS 接続での後に、HTTP 接続を試みます。</span><span class="sxs-lookup"><span data-stu-id="deb96-106">Listeners attempt an HTTP connection followed by an HTTPS connection with the Windows Azure Service Bus service and poll for messages.</span></span> <span data-ttu-id="deb96-107">簡単に TCP ポートの制約を回避するためよりこれを許可する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="deb96-107">This might allow you to more easily work around TCP port constraints.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.NotificationHubs.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.Azure.NotificationHubs.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="deb96-108">TCP モード (既定)。</span><span class="sxs-lookup"><span data-stu-id="deb96-108">TCP mode (default).</span></span> <span data-ttu-id="deb96-109">リスナーは、9350 から 9354 の範囲内で宛先のポートを Windows Azure Service Bus サービスへの TCP 接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="deb96-109">Listeners create TCP connections to the Windows Azure Service Bus service to a destination port in the range 9350 to 9354.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>