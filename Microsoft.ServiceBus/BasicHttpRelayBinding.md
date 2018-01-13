<Type Name="BasicHttpRelayBinding" FullName="Microsoft.ServiceBus.BasicHttpRelayBinding">
  <TypeSignature Language="C#" Value="public class BasicHttpRelayBinding : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BasicHttpRelayBinding extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class BasicHttpRelayBinding&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayBinding = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
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
    <summary><span data-ttu-id="90113-101">ASMX ベースの Web サービスと、WS に準拠するその他のサービスと通信できるエンドポイントを構成するクライアントが使用できるバインディングを表す、基本プロファイル 1.1 です。</span><span class="sxs-lookup"><span data-stu-id="90113-101">Represents a binding that a client can use to configure endpoints that can communicate with ASMX-based Web services and other services that conform to the WS-I Basic Profile 1.1.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="90113-102"><see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="90113-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.BasicHttpRelayBinding : string -&gt; Microsoft.ServiceBus.BasicHttpRelayBinding" Usage="new Microsoft.ServiceBus.BasicHttpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="90113-103">使用する構成。</span><span class="sxs-lookup"><span data-stu-id="90113-103">The configuration to use.</span></span> </param>
        <summary><span data-ttu-id="90113-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />クラスの指定の構成を使用します。</span><span class="sxs-lookup"><span data-stu-id="90113-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class using the specified configuration.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBinding (Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.BasicHttpRelayBinding : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.BasicHttpRelayBinding" Usage="new Microsoft.ServiceBus.BasicHttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="90113-105">SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類。</span><span class="sxs-lookup"><span data-stu-id="90113-105">The type of security used with the SOAP message and for the client.</span></span> </param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="90113-106">クライアントで使用される認証の種類。</span><span class="sxs-lookup"><span data-stu-id="90113-106">The type of authentication used by the client.</span></span> </param>
        <summary><span data-ttu-id="90113-107">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />バインディングによって使用されるセキュリティの種類を指定し、クライアントによって使用される認証の種類を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="90113-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> class with a specified type of security used by the binding and the authentication type used by the client.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-108">取得またはクライアントが cookie を許可するかどうかを決定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-108">Gets or sets a value that determines if the client allows cookies.</span></span></summary>
        <value><span data-ttu-id="90113-109">返します<see cref="T:System.Boolean" />.true; cookie を許可するそれ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="90113-109">Returns <see cref="T:System.Boolean" />.true to allow cookies; otherwise, false.</span></span> <span data-ttu-id="90113-110">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="90113-110">The default value is false.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.BasicHttpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="basicHttpRelayBinding.CreateBindingElements " />
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
        <summary><span data-ttu-id="90113-111">現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを返します。</span><span class="sxs-lookup"><span data-stu-id="90113-111">Returns an ordered collection of binding elements contained in the current binding.</span></span></summary>
        <returns><span data-ttu-id="90113-112">返します<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />です。により記述されたバインド要素の順序付けられたスタックを含む、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="90113-112">Returns <see cref="T:System.ServiceModel.Channels.BindingElementCollection" />.Contains the ordered stack of binding elements described by the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span> <span data-ttu-id="90113-113">ボトムアップからバインド要素の順序は、トランスポート、エンコーディング、およびセキュリティです。</span><span class="sxs-lookup"><span data-stu-id="90113-113">The order of the binding elements starting from the bottom is transport, encoding, and security.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-114">このバインドによって処理されるメッセージに使用される SOAP のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="90113-114">Gets the version of SOAP that is used for messages that are processed by this binding.</span></span> </summary>
        <value><span data-ttu-id="90113-115">返します<see cref="T:System.ServiceModel.EnvelopeVersion" />です。このバインディングで使用される値。</span><span class="sxs-lookup"><span data-stu-id="90113-115">Returns <see cref="T:System.ServiceModel.EnvelopeVersion" />.The value that is used with this binding.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-116">取得またはホスト名の比較方法を設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-116">Gets or sets how the host name should be compared.</span></span></summary>
        <value><span data-ttu-id="90113-117">ホスト名で使用される比較メソッドです。</span><span class="sxs-lookup"><span data-stu-id="90113-117">The comparison method used in the host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-118">取得またはバインド要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-118">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="90113-119">バインド要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="90113-119">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-120">バインドによって処理される TCP メッセージを保存するバッファー プールの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-120">Gets or sets the maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="90113-121">バインドによって処理される TCP メッセージを保存するバッファー プールの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="90113-121">The maximum size allowed for a buffer pool that stores TCP messages processed by the binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-122">チャネルからメッセージを受信するバッファーの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-122">Gets or sets the maximum size for a buffer that receives messages from the channel.</span></span></summary>
        <value><span data-ttu-id="90113-123">返します<see cref="T:System.Int32" />です。このバインディングで構成されたエンドポイントに対して処理されるときにメッセージを格納するバッファーのバイト単位の最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="90113-123">Returns <see cref="T:System.Int32" />.The maximum size, in bytes, of a buffer that stores messages while they are processed for an endpoint configured with this binding.</span></span> <span data-ttu-id="90113-124">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="90113-124">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-125">このバインドで構成されたチャネルで受信可能な最大メッセージ サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-125">Gets or sets the maximum size for a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="90113-126">返します<see cref="T:System.Int64" />です。最大サイズ (バイト単位)、バインディングによって処理されるメッセージ。</span><span class="sxs-lookup"><span data-stu-id="90113-126">Returns <see cref="T:System.Int64" />.The maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="90113-127">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="90113-127">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-128">取得またはメッセージのエンコードの種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-128">Gets or sets the type of message encoding.</span></span></summary>
        <value><span data-ttu-id="90113-129">返します、<see cref="T:System.ServiceModel.WSMessageEncoding" />メッセージのエンコードの種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="90113-129">Returns a <see cref="T:System.ServiceModel.WSMessageEncoding" /> that contains the type of message encoding.</span></span> <span data-ttu-id="90113-130">既定値はテキストです。</span><span class="sxs-lookup"><span data-stu-id="90113-130">The default value is Text.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-131">取得またはプロキシのアドレスを設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-131">Gets or sets the proxy address.</span></span></summary>
        <value><span data-ttu-id="90113-132">返します、<see cref="T:System.Uri" />プロキシ アドレスを格納します。</span><span class="sxs-lookup"><span data-stu-id="90113-132">Returns a <see cref="T:System.Uri" /> that  contains the proxy address.</span></span> <span data-ttu-id="90113-133">既定値は NULL です。</span><span class="sxs-lookup"><span data-stu-id="90113-133">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-134">取得またはリーダーのクォータを設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-134">Gets or sets the reader quotas.</span></span></summary>
        <value><span data-ttu-id="90113-135">返します、<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />交換される SOAP メッセージに対する複雑さの制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="90113-135">Returns a <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> that specifies the complexity constraints on SOAP messages exchanged.</span></span> <span data-ttu-id="90113-136">これらの制約の既定値については、後の「解説」で説明します。</span><span class="sxs-lookup"><span data-stu-id="90113-136">The default values for these constraints are provided in the following Remarks section.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-137">このバインディングで構成されたチャネルとリスナーのための URI トランスポート スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="90113-137">Gets the URI transport scheme for the channels and listeners that are configured with this binding.</span></span></summary>
        <value><span data-ttu-id="90113-138">チャネルとリスナーがこのバインディングで構成されているの URI トランスポート スキーム。</span><span class="sxs-lookup"><span data-stu-id="90113-138">The URI transport scheme for the channels and listeners that are configured with this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.BasicHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.BasicHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As BasicHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.BasicHttpRelaySecurity" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.BasicHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-139">このバインディングで使用されるセキュリティ バインディングのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="90113-139">Gets the collection of security bindings used with this binding.</span></span></summary>
        <value><span data-ttu-id="90113-140">返します、<see cref="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" />バインドで使用されるセキュリティ設定を格納しています。</span><span class="sxs-lookup"><span data-stu-id="90113-140">Returns a <see cref="T:Microsoft.ServiceBus.BasicHttpRelaySecurity" /> that contains the  security settings used in the binding.</span></span> <span data-ttu-id="90113-141">既定値が Transport に設定 EndToEndBasicSecurityMode、RelayClientAuthenticationType が HttypProxyCredentialType のいずれも、HttpRelayTransportSecurity と BasicHttpRelayMessageSecurity と RelayAccessToken に設定BasicHttpMessageCredentialType.UserName と、AlgorithmSuite SecurityAlgorithmSuite.Basic256 の ClientCredentialType します。</span><span class="sxs-lookup"><span data-stu-id="90113-141">The default value has EndToEndBasicSecurityMode set to Transport, RelayClientAuthenticationType set to RelayAccessToken, HttpRelayTransportSecurity with HttypProxyCredentialType of None, and BasicHttpRelayMessageSecurity with ClientCredentialType of BasicHttpMessageCredentialType.UserName and an AlgorithmSuite of SecurityAlgorithmSuite.Basic256.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
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
            <span data-ttu-id="90113-142">受信要求が非同期的に処理されることを示します。</span><span class="sxs-lookup"><span data-stu-id="90113-142">Indicates that incoming requests are handled asynchronously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.TextEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-143">メッセージ テキストに使用される文字エンコーディングを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-143">Gets or sets the character encoding that is used for the message text.</span></span></summary>
        <value><span data-ttu-id="90113-144">返します、<see cref="T:System.Text.Encoding" />を示すために使用される文字エンコーディングします。</span><span class="sxs-lookup"><span data-stu-id="90113-144">Returns a <see cref="T:System.Text.Encoding" /> that indicates the character encoding that is used.</span></span> <span data-ttu-id="90113-145">既定値は、UTF8Encoding です。</span><span class="sxs-lookup"><span data-stu-id="90113-145">The default is UTF8Encoding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-146">転送モードを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-146">Gets or sets the transfer mode.</span></span></summary>
        <value><span data-ttu-id="90113-147">返します、<see cref="T:System.ServiceModel.TransferMode" />ストリームまたはバッファー内のバインドを使用して (または両方) でサービスが構成されているかどうかを示すメッセージ転送のモード。</span><span class="sxs-lookup"><span data-stu-id="90113-147">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="90113-148">既定では、HTTP、TCP/IP、および名前付きパイプ トランスポートは、バッファー内のメッセージ転送を使用します。</span><span class="sxs-lookup"><span data-stu-id="90113-148">By default, the HTTP, TCP/IP, and named pipe transports use buffered message transfers.</span></span> <span data-ttu-id="90113-149">既定値はバッファーです。</span><span class="sxs-lookup"><span data-stu-id="90113-149">The default value is buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayBinding.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayBinding.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="90113-150">取得またはクライアントが既定の web プロキシを使用するかどうかを決定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="90113-150">Gets or sets a value that determines if the client uses the default web proxy.</span></span></summary>
        <value><span data-ttu-id="90113-151">クライアントは、既定の web プロキシ; を使用している場合、true を返しますそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="90113-151">Returns true if the client uses the default web proxy; otherwise, false.</span></span> <span data-ttu-id="90113-152">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="90113-152">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>