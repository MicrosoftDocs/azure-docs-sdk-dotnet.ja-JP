<Type Name="TcpRelayTransportBindingElement" FullName="Microsoft.ServiceBus.TcpRelayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class TcpRelayTransportBindingElement : Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TcpRelayTransportBindingElement extends Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class TcpRelayTransportBindingElement&#xA;Inherits ConnectionOrientedTransportBindingElement&#xA;Implements IPolicyExportExtension" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportBindingElement = class&#xA;    inherit ConnectionOrientedTransportBindingElement&#xA;    interface IPolicyExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Channels.ConnectionOrientedTransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="366f5-101">TCP トランスポート リレーのバインド要素を表します。</span><span class="sxs-lookup"><span data-stu-id="366f5-101">Represents the binding element for the TCP transport relay.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="366f5-102"><see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="366f5-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TcpRelayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.TcpRelayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType"><span data-ttu-id="366f5-103">リレー クライアントの認証の種類。</span><span class="sxs-lookup"><span data-stu-id="366f5-103">The relay client authentication type.</span></span></param>
        <summary><span data-ttu-id="366f5-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" />クラスの指定されたリレー クライアントの認証の種類を使用します。</span><span class="sxs-lookup"><span data-stu-id="366f5-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> class using the specified relay client authentication type.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TcpRelayTransportBindingElement (Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (elementToBeCloned As TcpRelayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TcpRelayTransportBindingElement : Microsoft.ServiceBus.TcpRelayTransportBindingElement -&gt; Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.TcpRelayTransportBindingElement elementToBeCloned" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToBeCloned" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToBeCloned"><span data-ttu-id="366f5-105">複製対象となる要素。</span><span class="sxs-lookup"><span data-stu-id="366f5-105">The element to be cloned.</span></span></param>
        <summary><span data-ttu-id="366f5-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" />クラスの指定されたリレー バインド要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="366f5-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.TcpRelayTransportBindingElement" /> class using the specified relay binding element.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="tcpRelayTransportBindingElement.BuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"> <span data-ttu-id="366f5-107">チャネル ファクトリの型。</span><span class="sxs-lookup"><span data-stu-id="366f5-107">The type of channel factory.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="366f5-108">バインディング、動作、コントラクト、およびチャネル ファクトリの作成に必要なその他の情報について説明します。</span><span class="sxs-lookup"><span data-stu-id="366f5-108">Describes the bindings, behaviors, contracts, and other information required to create the channel factory.</span></span></param>
        <summary><span data-ttu-id="366f5-109">チャネルを作成するために使用できるチャネル ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="366f5-109">Creates a channel factory that can be used to create a channel.</span></span></summary>
        <returns><span data-ttu-id="366f5-110">指定した種類のチャネル ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="366f5-110">A channel factory of the specified type.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="366f5-111">トランスポートの保護が有効にし、接続モードは、ハイブリッドまたは Direct.This のいずれかのメンバーに設定を直接使用される可能性はありませんカスタム バインドを作成するときに使用することがあります。詳細については、カスタム AppFabric Service Bus のバインドを作成する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="366f5-111">When Transport protection is enabled and the Connection Mode is set to either Hybrid or Direct.This member is unlikely to be used directly, but may be used when creating a custom binding.For more information, see Creating a Custom AppFabric Service Bus Binding.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="tcpRelayTransportBindingElement.BuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
            <InterfaceName>System.ServiceModel.Channels.IChannel</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel"> <span data-ttu-id="366f5-112">チャネル ファクトリの型。</span><span class="sxs-lookup"><span data-stu-id="366f5-112">The type of channel factory.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="366f5-113">バインディング、動作、コントラクト、およびチャネル ファクトリの作成に必要なその他の情報について説明します。</span><span class="sxs-lookup"><span data-stu-id="366f5-113">Describes the bindings, behaviors, contracts, and other information required to create the channel factory.</span></span></param>
        <summary><span data-ttu-id="366f5-114">指定した種類のチャネル リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="366f5-114">Creates a channel listener of the specified type.</span></span></summary>
        <returns><span data-ttu-id="366f5-115">指定した種類のチャネル リスナー。</span><span class="sxs-lookup"><span data-stu-id="366f5-115">A channel listener of the specified type.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="366f5-116">トランスポートの保護が有効になっているし、接続モードがハイブリッドまたは直接のいずれかに設定されます。</span><span class="sxs-lookup"><span data-stu-id="366f5-116">When Transport protection is enabled and the Connection Mode is set to either Hybrid or Direct.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="tcpRelayTransportBindingElement.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="366f5-117">現在のバインド要素のコピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="366f5-117">Creates a copy of the current binding element.</span></span></summary>
        <returns><span data-ttu-id="366f5-118">返します、<see cref="T:System.ServiceModel.Channels.BindingElement" />バインド要素のコピーを格納します。</span><span class="sxs-lookup"><span data-stu-id="366f5-118">Returns a <see cref="T:System.ServiceModel.Channels.BindingElement" /> that contains a copy of the binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="366f5-119">取得または接続モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="366f5-119">Gets or sets the connection mode.</span></span></summary>
        <value><span data-ttu-id="366f5-120">返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />接続モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="366f5-120">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.SocketConnectionPoolSettings ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPoolSettings As SocketConnectionPoolSettings" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.SocketConnectionPoolSettings" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketConnectionPoolSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="366f5-121">接続プールの現在のインスタンスの設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="366f5-121">Gets the connection pool settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="366f5-122">現在のインスタンスの接続プールの設定。</span><span class="sxs-lookup"><span data-stu-id="366f5-122">The connection pool settings for the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="tcpRelayTransportBindingElement.GetProperty context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"> <span data-ttu-id="366f5-123">取得するオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="366f5-123">The type of object to get.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="366f5-124">コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="366f5-124">The context.</span></span> </param>
        <summary><span data-ttu-id="366f5-125">バインド コンテキストから指定したオブジェクトを返します。</span><span class="sxs-lookup"><span data-stu-id="366f5-125">Returns a specified object from the binding context.</span></span></summary>
        <returns><span data-ttu-id="366f5-126">バインド要素がない場合、指定したオブジェクトまたは null が含まれています。</span><span class="sxs-lookup"><span data-stu-id="366f5-126">A binding element that contains the specified object, or null if not found.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="366f5-127">取得またはバインド要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="366f5-127">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="366f5-128">バインド要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="366f5-128">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="366f5-129">取得またはサービス クライアントで使用される認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="366f5-129">Gets or sets the type of authentication used by the service client.</span></span></summary>
        <value><span data-ttu-id="366f5-130">返します<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />です。認証の種類が含まれています。</span><span class="sxs-lookup"><span data-stu-id="366f5-130">Returns <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />.Contains the authentication type.</span></span> <span data-ttu-id="366f5-131">既定値は、RelayAccessToken です。</span><span class="sxs-lookup"><span data-stu-id="366f5-131">The default value is RelayAccessToken.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.TcpRelayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.TcpRelayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="366f5-132">トランスポートの URI スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="366f5-132">Gets the URI scheme for the transport.</span></span></summary>
        <value><span data-ttu-id="366f5-133">"TCP"であるトランスポートの URI スキームを返します。</span><span class="sxs-lookup"><span data-stu-id="366f5-133">Returns the URI scheme for the transport, which is “TCP”.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TcpRelayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportPolicy (exporter As MetadataExporter, context As PolicyConversionContext) Implements IPolicyExportExtension.ExportPolicy" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.MetadataExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.PolicyConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter"><span data-ttu-id="366f5-134">エクスポート プロセスを変更に使用できる MetadataExporter です。</span><span class="sxs-lookup"><span data-stu-id="366f5-134">The MetadataExporter that you can use to modify the exporting process.</span></span></param>
        <param name="context"><span data-ttu-id="366f5-135">カスタム ポリシー アサーションの挿入に使用できる PolicyConversionContext です。</span><span class="sxs-lookup"><span data-stu-id="366f5-135">The PolicyConversionContext that you can use to insert your custom policy assertion.</span></span></param>
        <summary>
            <span data-ttu-id="366f5-136">このバインドに関するカスタム ポリシー アサーションをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="366f5-136">Exports a custom policy assertion about this binding.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>