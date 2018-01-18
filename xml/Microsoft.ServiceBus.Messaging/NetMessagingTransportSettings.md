<Type Name="NetMessagingTransportSettings" FullName="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportSettings" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportSettings = class&#xA;    interface ITransportSettings&#xA;    interface IServiceBusSecuritySettings" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="5d616-101">.NET メッセージング トランスポート設定を表します。</span><span class="sxs-lookup"><span data-stu-id="5d616-101">Represents .NET messaging transport settings.</span></span></summary>
    <remarks>
            <span data-ttu-id="5d616-102">このクラスは、NetMessagingBinding.MessagingFactorySettings プロパティ Net Messaging Protocol (SBMP) 特定の構成のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="5d616-102">This class provides Net Messaging Protocol (SBMP) specific configuration support for the NetMessagingBinding.MessagingFactorySettings property.</span></span>  
            <span data-ttu-id="5d616-103">MessagingFactorySettings で使用可能な設定を構成すると、公開されます。</span><span class="sxs-lookup"><span data-stu-id="5d616-103">It exposes to configuration the settings available on the MessagingFactorySettings.</span></span>
            </remarks>
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactory" />
    <altmember cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />
    <example>
      <code>
            <span data-ttu-id="5d616-104">MessagingFactorySettings factorySettings MessagingFactory (実行時の操作) の設定を作成する新しい MessagingFactorySettings() = {NetMessagingTransportSettings = 新しい NetMessagingTransportSettings()、資格情報 =TransportClientCredentialBase.CreateSharedSecretCredential (IssuerName、IssuerKey)} です。</span><span class="sxs-lookup"><span data-stu-id="5d616-104">// Create settings for the MessagingFactory (for runtime operations) MessagingFactorySettings factorySettings = new MessagingFactorySettings() { NetMessagingTransportSettings = new NetMessagingTransportSettings(), Credential = TransportClientCredentialBase.CreateSharedSecretCredential(IssuerName, IssuerKey), };</span></span>
            
            <span data-ttu-id="5d616-105">MessagingFactory MessagingFactory ファクトリの作成 (myServiceBusNamespace、factorySettings); MessagingFactory.Create を =</span><span class="sxs-lookup"><span data-stu-id="5d616-105">// Create the MessagingFactory MessagingFactory factory = MessagingFactory.Create(myServiceBusNamespace, factorySettings);</span></span>
            
            <span data-ttu-id="5d616-106">キュー クライアントを作成します。</span><span class="sxs-lookup"><span data-stu-id="5d616-106">// Create queue client</span></span>
            
            </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5d616-107"><see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5d616-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFlushInterval">
      <MemberSignature Language="C#" Value="public TimeSpan BatchFlushInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan BatchFlushInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFlushInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.BatchFlushInterval : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.BatchFlushInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5d616-108">取得またはバッチのフラッシュ間隔を設定します。</span><span class="sxs-lookup"><span data-stu-id="5d616-108">Gets or sets the batch flush interval.</span></span></summary>
        <value><span data-ttu-id="5d616-109">バッチのフラッシュ間隔。</span><span class="sxs-lookup"><span data-stu-id="5d616-109">The batch flush interval.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public object Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As Object" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; obj&#xA;override this.Clone : unit -&gt; obj" Usage="netMessagingTransportSettings.Clone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceBus.Messaging.ITransportSettings.Clone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5d616-110">このオブジェクトのディープ コピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="5d616-110">Makes a deep copy of this object.</span></span></summary>
        <returns><span data-ttu-id="5d616-111">このオブジェクトのコピー。</span><span class="sxs-lookup"><span data-stu-id="5d616-111">A copy of this object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableRedirect">
      <MemberSignature Language="C#" Value="public bool EnableRedirect { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableRedirect" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableRedirect As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableRedirect : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.EnableRedirect" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5d616-112">メッセージ リダイレクトが有効になっているかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d616-112">Gets a value that indicates whether the message redirect is enabled.</span></span></summary>
        <value><span data-ttu-id="5d616-113">メッセージ リダイレクトが有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="5d616-113">true if the message redirect is enabled; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings.LeaseTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d616-114">取得または LeaseTimeout プロパティ内のリース タイムアウト値を設定、<seealso cref="P:System.ServiceModel.Channels.TcpTransportBindingElement.ConnectionPoolSettings" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="5d616-114">Gets or sets the lease timeout value for the LeaseTimeout property within the <seealso cref="P:System.ServiceModel.Channels.TcpTransportBindingElement.ConnectionPoolSettings" /> class.</span></span>
            <span data-ttu-id="5d616-115">既定値は 5 分です。</span><span class="sxs-lookup"><span data-stu-id="5d616-115">Default is 5 minutes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="5d616-116">値が TimeSpan.Zero よりか Int32.MaxValue ミリ秒よりも大きい場合にスローします。</span><span class="sxs-lookup"><span data-stu-id="5d616-116">throw if value is less than TimeSpan.Zero or larger than Int32.MaxValue milliseconds</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>