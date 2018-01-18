<Type Name="WSHttpRelayBindingBase" FullName="Microsoft.ServiceBus.WSHttpRelayBindingBase">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingBase : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingBase extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingBase&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingBase = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="29f8c-101">共通するメンバーを持つ基本クラスを提供、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-101">Provides the base class with members common to the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="29f8c-102"><see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> class.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBase (bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (reliableSessionEnabled As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WSHttpRelayBindingBase : bool -&gt; Microsoft.ServiceBus.WSHttpRelayBindingBase" Usage="new Microsoft.ServiceBus.WSHttpRelayBindingBase reliableSessionEnabled" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="reliableSessionEnabled"><span data-ttu-id="29f8c-103">信頼できるセッションが有効である場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-103">true, if a reliable session is enabled; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="29f8c-104">信頼できるセッションが有効かどうかを示す値を使用して、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> class with a value that indicates whether a reliable session is enabled.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="wSHttpRelayBindingBase.CreateBindingElements " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BindingElementCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="29f8c-105">Azure Service Bus の現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-105">Returns an ordered collection of binding elements contained in the current Azure Service Bus binding.</span></span> </summary>
        <returns><span data-ttu-id="29f8c-106">返します<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />です。バインドのオブジェクトが含まれています。</span><span class="sxs-lookup"><span data-stu-id="29f8c-106">Returns <see cref="T:System.ServiceModel.Channels.BindingElementCollection" />.Contains the objects for the binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected abstract System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wSHttpRelayBindingBase.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="29f8c-107">派生クラスとして実装された場合は、Azure Service Bus の現在のバインドからセキュリティ バインド要素を返します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-107">When implemented in a derived class, returns the security binding element from the current Azure Service Bus binding.</span></span> </summary>
        <returns><span data-ttu-id="29f8c-108">返します<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />です。Azure Service Bus の現在のバインドからセキュリティ バインド要素が含まれています。</span><span class="sxs-lookup"><span data-stu-id="29f8c-108">Returns <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />.Contains the security binding element from the current Azure Service Bus binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-109">このバインドによって処理されるメッセージに使用される SOAP のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-109">Gets the version of SOAP that is used for messages that are processed by this binding.</span></span> </summary>
        <value><span data-ttu-id="29f8c-110">返します<see cref="T:System.ServiceModel.EnvelopeVersion" />です。この Azure Service Bus バインディングで使用されるエンベロープ バージョンの値。</span><span class="sxs-lookup"><span data-stu-id="29f8c-110">Returns <see cref="T:System.ServiceModel.EnvelopeVersion" />.The value of the envelope version that is used with this Azure Service Bus binding.</span></span> <span data-ttu-id="29f8c-111">値は、常に SOAP 1.2 です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-111">The value is always SOAP 1.2.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransport">
      <MemberSignature Language="C#" Value="protected abstract System.ServiceModel.Channels.TransportBindingElement GetTransport ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.TransportBindingElement GetTransport() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.GetTransport" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function GetTransport () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="abstract member GetTransport : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="wSHttpRelayBindingBase.GetTransport " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.TransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="29f8c-112">派生クラスとして実装された場合は、Azure Service Bus の現在のバインドからトランスポート バインド要素を返します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-112">When implemented in a derived class, returns the transport binding element from the current Azure Service Bus binding.</span></span> </summary>
        <returns><span data-ttu-id="29f8c-113">返します<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />です。Azure Service Bus の現在のバインドからトランスポート バインド要素が含まれています。</span><span class="sxs-lookup"><span data-stu-id="29f8c-113">Returns <see cref="T:System.ServiceModel.Channels.TransportBindingElement" />.Contains the transport binding element from the current Azure Service Bus binding.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-114">取得または使用するホスト名比較モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-114">Gets or sets the comparison mode used on the host name.</span></span></summary>
        <value><span data-ttu-id="29f8c-115">ホスト名を使用する比較モード。</span><span class="sxs-lookup"><span data-stu-id="29f8c-115">The comparison mode used on the host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-116">取得またはリレー バインドが動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-116">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="29f8c-117">リレー バインドは、動的; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-117">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-118">取得またはこの Azure Service Bus のバインドを使用してエンドポイントによって必要とするバッファーを管理するバッファー マネージャーに割り当てられたメモリの最大量を設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-118">Gets or sets the maximum amount of memory allocated for the buffer manager that manages the buffers required by endpoints using this Azure Service Bus binding.</span></span> </summary>
        <value><span data-ttu-id="29f8c-119">返します<see cref="T:System.Int64" />です。このバインディングで構成されるエンドポイントによって使用されるバッファーのプールのバイト単位で最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="29f8c-119">Returns <see cref="T:System.Int64" />.The maximum size, in bytes, for the pool of buffers used by an endpoint configured with this binding.</span></span> <span data-ttu-id="29f8c-120">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="29f8c-120">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-121">取得または Azure Service Bus バインディングにより処理可能なメッセージの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-121">Gets or sets the maximum size for a message that can be processed by the Azure Service Bus binding.</span></span> </summary>
        <value><span data-ttu-id="29f8c-122">返します<see cref="T:System.Int64" />です。最大サイズ (バイト単位)、Azure Service Bus バインディングによって処理されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="29f8c-122">Returns <see cref="T:System.Int64" />.The maximum size, in bytes, for a message that is processed by the Azure Service Bus binding.</span></span> <span data-ttu-id="29f8c-123">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="29f8c-123">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-124">SOAP メッセージのエンコードに MTOM または Text/XML が使用されるかどうかを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-124">Gets or sets whether MTOM or Text/XML is used to encode SOAP messages.</span></span> </summary>
        <value><span data-ttu-id="29f8c-125">返します<see cref="T:System.ServiceModel.WSMessageEncoding" />です。SOAP メッセージのエンコードに MTOM または TEXT/XML が使用されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-125">Returns <see cref="T:System.ServiceModel.WSMessageEncoding" />.Indicates whether MTOM or Text/XML is used to encode SOAP messages.</span></span> <span data-ttu-id="29f8c-126">既定値は、TEXT/XML です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-126">The default value is Text/XML.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-127">HTTP プロキシの URI アドレスを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-127">Gets or sets the URI address of the HTTP proxy.</span></span> </summary>
        <value><span data-ttu-id="29f8c-128">返します<see cref="T:System.Uri" />です。HTTP プロキシのアドレスとして機能します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-128">Returns <see cref="T:System.Uri" />.Serves as the address of the HTTP proxy.</span></span> <span data-ttu-id="29f8c-129">既定値は NULL です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-129">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-130">取得または、このセキュリティ バス バインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-130">Gets or sets constraints on the complexity of SOAP messages that can be processed by endpoints configured with this Security Bus binding.</span></span> </summary>
        <value><span data-ttu-id="29f8c-131">返します<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />です。複雑さの制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-131">Returns <see cref="T:System.Xml.XmlDictionaryReaderQuotas" />.Specifies the complexity constraints.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.OptionalReliableSession ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.OptionalReliableSession ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As OptionalReliableSession" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.OptionalReliableSession" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.OptionalReliableSession</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-132">システム指定のバインディングのいずれかを使用するときに使用できる信頼性の高い Azure Service Bus セッションをバインド要素のプロパティに簡単にアクセスを提供するオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-132">Gets an object that provides convenient access to the properties of a reliable Azure Service Bus session binding element that are available when using one of the system-provided bindings.</span></span> </summary>
        <value><span data-ttu-id="29f8c-133">返します<see cref="T:System.ServiceModel.OptionalReliableSession" />です。システム指定のバインディングのいずれかを使用するときに使用できる信頼性の高い Azure Service Bus セッションをバインド要素のプロパティに簡単にアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-133">Returns <see cref="T:System.ServiceModel.OptionalReliableSession" />.Provides convenient access to the properties of a reliable Azure Service Bus session binding element that are available when using one of the system-provided bindings.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-134">このバインディングで構成されたチャネルとリスナーのための URI トランスポート スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-134">Gets the URI transport scheme for the channels and listeners that are configured with this binding.</span></span> </summary>
        <value><span data-ttu-id="29f8c-135">返します<see cref="T:System.String" />を表す URI トランスポート スキーム。</span><span class="sxs-lookup"><span data-stu-id="29f8c-135">Returns <see cref="T:System.String" /> that represents the URI transport scheme.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29f8c-136">受信要求が非同期的に処理されることを示します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-136">Indicates that incoming requests are handled asynchronously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.TextEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-137">メッセージ テキストに使用される文字エンコーディングを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-137">Gets or sets the character encoding that is used for the message text.</span></span></summary>
        <value><span data-ttu-id="29f8c-138">文字エン コードは、メッセージ テキストに使用されます。</span><span class="sxs-lookup"><span data-stu-id="29f8c-138">The character encoding that is used for the message text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="29f8c-139">使用できる場合にシステムの自動構成される HTTP プロキシを使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="29f8c-139">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used, if available.</span></span></summary>
        <value><span data-ttu-id="29f8c-140">使用可能な場合、システムの自動設定 HTTP プロキシを使用する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="29f8c-140">true if the auto-configured HTTP proxy of the system should be used, if available; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>