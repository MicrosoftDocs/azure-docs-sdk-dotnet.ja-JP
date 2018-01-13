<Type Name="NetMessagingTransportBindingElement" FullName="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement">
  <TypeSignature Language="C#" Value="public sealed class NetMessagingTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Description.IPolicyExportExtension, System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetMessagingTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Description.IPolicyExportExtension, class System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetMessagingTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension, IWsdlExportExtension" />
  <TypeSignature Language="F#" Value="type NetMessagingTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension&#xA;    interface IWsdlExportExtension" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="5c4b5-101">メッセージングの Service Bus にメッセージの送信トランスポート net を指定するために使用するバインド要素を表します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-101">Represents the binding element used to specify a net messaging transport for transmitting messages on the Service Bus.</span></span></summary>
    <remarks>
            <span data-ttu-id="5c4b5-102">NetMessagingTransportBindingElement は、作成元の IOutputChannel、IInputChannel、IInputChannel + ReceiveContext、IInputSessionChannel、および IInputSessionChannel + ReceiveContext をサポートします。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-102">The NetMessagingTransportBindingElement supports creating IOutputChannel, IInputChannel, IInputChannel+ReceiveContext, IInputSessionChannel, and IInputSessionChannel+ReceiveContext.</span></span> <span data-ttu-id="5c4b5-103">セッション対応チャネル (IInputSessionChannel、IInputSessionChannel + ReceiveContext) はセッションをサポートします。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-103">The session-aware channels (IInputSessionChannel, IInputSessionChannel+ReceiveContext) are for session support.</span></span>
             </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetMessagingTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5c4b5-104"><see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="netMessagingTransportBindingElement.BuildChannelFactory context" />
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
        <typeparam name="TChannel"> <span data-ttu-id="5c4b5-105">チャネルの種類。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-105">Type of the channel.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="5c4b5-106">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-106">The binding context.</span></span> </param>
        <summary> <span data-ttu-id="5c4b5-107">チャネル ファクトリを構築します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-107">Builds a channel factory.</span></span> </summary>
        <returns> <span data-ttu-id="5c4b5-108">チャネル ファクトリによって実装されるインターフェイス。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-108">The interface implemented by the channel factory.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5c4b5-109">TChannel がサポートされているチャネルの種類をされていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-109">Thrown when TChannel isn't a supported channel type</span></span> </exception>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="5c4b5-110">コンテキストが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-110">Thrown when context is null.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="netMessagingTransportBindingElement.BuildChannelListener context" />
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
        <typeparam name="TChannel"> <span data-ttu-id="5c4b5-111">チャネルの種類。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-111">Type of the channel.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="5c4b5-112">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-112">The binding context.</span></span> </param>
        <summary> <span data-ttu-id="5c4b5-113">チャネル リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-113">Builds a channel listener.</span></span> </summary>
        <returns> <span data-ttu-id="5c4b5-114">実装の IChannelListener インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-114">A implemented IChannelListener interface.</span></span> </returns>
        <remarks>
                     <span data-ttu-id="5c4b5-115">チャネル リスナーおよび各リスナーに関連付けられたチャネルは、通常、クライアントが開始した通信を受信するサービスによって使用されます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-115">Channel listeners and their associated channels are generally used by services that receive communications initiated by clients.</span></span> <span data-ttu-id="5c4b5-116">に対する IChannelFactory インターフェイスを実装するチャネル ファクトリは、これに対し、サービスとの通信を開始するチャネルを作成するための機構を提供します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-116">Channel factories that implement the IChannelFactory interface, by contrast, provide the mechanisms used to create the channels through which communication with a service is initiated.</span></span> </remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="5c4b5-117">コンテキストが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-117">Thrown when context is null.</span></span> </exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="5c4b5-118">TChannel がサポートされているチャネルの種類をされていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-118">Thrown when TChannel isn't a supported channel type</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;T&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of T) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="netMessagingTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="T"> <span data-ttu-id="5c4b5-119">チャネルの種類。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-119">Type of the channel.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="5c4b5-120">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-120">The binding context.</span></span> </param>
        <summary> <span data-ttu-id="5c4b5-121">クエリ、チャネル ファクトリは、'コンテキスト' を構築できます。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-121">Queries the channel factory can build 'context'.</span></span> </summary>
        <returns> <span data-ttu-id="5c4b5-122">指定した種類のチャネルに対するチャネル ファクトリをバインド要素が作成できるかどうかを示す値を返します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-122">Returns a value that indicates whether the binding element can build a channel factory for a specific type of channel.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="5c4b5-123">場合にスローされる引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-123">Thrown when argument null.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of T As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'T : null and 'T :&gt; System.ServiceModel.Channels.IChannel)" Usage="netMessagingTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
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
        <typeparam name="T"> <span data-ttu-id="5c4b5-124">ジェネリック型パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-124">Generic type parameter.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="5c4b5-125">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-125">The binding context.</span></span> </param>
        <summary> <span data-ttu-id="5c4b5-126">'Context' のチャネル リスナーを構築することができる場合のクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-126">Queries if we can build channel listener 'context'.</span></span> </summary>
        <returns> <span data-ttu-id="5c4b5-127">バインド要素が特定の種類のチャネルに対するチャネル リスナーを作成できるかどうかを示す値を返します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-127">Returns a value that indicates whether the binding element can build a channel listener for a specific type of channel.</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="5c4b5-128">場合にスローされる引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-128">Thrown when argument null.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="netMessagingTransportBindingElement.Clone " />
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
        <summary><span data-ttu-id="5c4b5-129">このバインド要素のディープ コピーを作成します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-129">Makes a deep copy of this binding element.</span></span></summary>
        <returns><span data-ttu-id="5c4b5-130">このバインド要素のコピー。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-130">A copy of this binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="netMessagingTransportBindingElement.GetProperty context" />
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
        <typeparam name="T"> <span data-ttu-id="5c4b5-131">ジェネリック型パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-131">Generic type parameter.</span></span> </typeparam>
        <param name="context"> <span data-ttu-id="5c4b5-132">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-132">The binding context.</span></span> </param>
        <summary> <span data-ttu-id="5c4b5-133">特定のバインディング要素のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-133">Gets a specific binding element property.</span></span> </summary>
        <returns> <span data-ttu-id="5c4b5-134">T プロパティ</span><span class="sxs-lookup"><span data-stu-id="5c4b5-134">The property T</span></span> </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="5c4b5-135">場合にスローされる引数が null です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-135">Thrown when argument null.</span></span> </exception>
      </Docs>
    </Member>
    <Member MemberName="PrefetchCount">
      <MemberSignature Language="C#" Value="public int PrefetchCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PrefetchCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.PrefetchCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PrefetchCount As Integer" />
      <MemberSignature Language="F#" Value="member this.PrefetchCount : int with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.PrefetchCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(-1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5c4b5-136">取得またはプリフェッチ数を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-136">Gets or sets the number of prefetch.</span></span></summary>
        <value><span data-ttu-id="5c4b5-137">プリフェッチ数。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-137">The number of prefetch.</span></span></value>
        <remarks> <span data-ttu-id="5c4b5-138">サーバーに次の受信呼び出しで有効になります</span><span class="sxs-lookup"><span data-stu-id="5c4b5-138">Takes effect on the next receive call to the server</span></span> </remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5c4b5-139">トランスポートの URI スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-139">Gets the URI scheme for the transport.</span></span></summary>
        <value><span data-ttu-id="5c4b5-140">トランスポートの URI スキーム。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-140">The URI scheme for the transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionIdleTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan SessionIdleTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan SessionIdleTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.SessionIdleTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionIdleTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.SessionIdleTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.SessionIdleTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(typeof(System.TimeSpan), "00:01:00")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5c4b5-141">取得またはセッションがタイムアウトするまでに待機する非アクティブな期間を指定する timespan 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-141">Gets or sets the timespan value that specifies period of inactivity that the session waits before timing out.</span></span></summary>
        <value><span data-ttu-id="5c4b5-142">Timespan 値です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-142">The timespan value.</span></span> <span data-ttu-id="5c4b5-143">既定値は 1 分です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-143">The default value is 1 minute.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
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
        <param name="exporter"><span data-ttu-id="5c4b5-144">エクスポート プロセスを変更に使用できる MetadataExporter です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-144">The MetadataExporter that you can use to modify the exporting process.</span></span></param>
        <param name="context"><span data-ttu-id="5c4b5-145">カスタム ポリシー アサーションの挿入に使用できる PolicyConversionContext です。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-145">The PolicyConversionContext that you can use to insert your custom policy assertion.</span></span></param>
        <summary>
            <span data-ttu-id="5c4b5-146">このバインドに関するカスタム ポリシー アサーションをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-146">Exports a custom policy assertion about this binding.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportContract">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportContract (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportContract(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportContract (exporter As WsdlExporter, context As WsdlContractConversionContext) Implements IWsdlExportExtension.ExportContract" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlContractConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">To be added.</param>
        <param name="context">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportEndpoint (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlEndpointConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlEndpointConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
      <MemberSignature Language="VB.NET" Value="Sub ExportEndpoint (exporter As WsdlExporter, context As WsdlEndpointConversionContext) Implements IWsdlExportExtension.ExportEndpoint" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exporter" Type="System.ServiceModel.Description.WsdlExporter" />
        <Parameter Name="context" Type="System.ServiceModel.Description.WsdlEndpointConversionContext" />
      </Parameters>
      <Docs>
        <param name="exporter">To be added.</param>
        <param name="context">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransportSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings TransportSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.TransportSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TransportSettings As NetMessagingTransportSettings" />
      <MemberSignature Language="F#" Value="member this.TransportSettings : Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings with get, set" Usage="Microsoft.ServiceBus.Messaging.NetMessagingTransportBindingElement.TransportSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.NetMessagingTransportSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5c4b5-147">取得または net メッセージング用のトランスポート設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-147">Gets or sets the transport settings for the net messaging.</span></span></summary>
        <value><span data-ttu-id="5c4b5-148">Net メッセージングのトランスポート設定。</span><span class="sxs-lookup"><span data-stu-id="5c4b5-148">The transport settings for the net messaging.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>