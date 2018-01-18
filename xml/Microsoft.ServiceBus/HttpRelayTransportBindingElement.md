<Type Name="HttpRelayTransportBindingElement" FullName="Microsoft.ServiceBus.HttpRelayTransportBindingElement">
  <TypeSignature Language="C#" Value="public class HttpRelayTransportBindingElement : System.ServiceModel.Channels.TransportBindingElement, System.ServiceModel.Channels.ITransportTokenAssertionProvider, System.ServiceModel.Description.IPolicyExportExtension, System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpRelayTransportBindingElement extends System.ServiceModel.Channels.TransportBindingElement implements class System.ServiceModel.Channels.ITransportTokenAssertionProvider, class System.ServiceModel.Description.IPolicyExportExtension, class System.ServiceModel.Description.IWsdlExportExtension" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpRelayTransportBindingElement&#xA;Inherits TransportBindingElement&#xA;Implements IPolicyExportExtension, ITransportTokenAssertionProvider, IWsdlExportExtension" />
  <TypeSignature Language="F#" Value="type HttpRelayTransportBindingElement = class&#xA;    inherit TransportBindingElement&#xA;    interface IPolicyExportExtension&#xA;    interface IWsdlExportExtension&#xA;    interface ITransportTokenAssertionProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.TransportBindingElement</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.ITransportTokenAssertionProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IPolicyExportExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.ServiceModel.Description.IWsdlExportExtension</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="cf8bf-101">Azure Service Bus にメッセージを送信するための HTTP トランスポートを指定するために使用するバインド要素を表します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-101">Represents the binding element used to specify an HTTP transport for transmitting messages on the Azure Service Bus.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cf8bf-102"><see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected HttpRelayTransportBindingElement (Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.HttpRelayTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (elementToBeCloned As HttpRelayTransportBindingElement)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpRelayTransportBindingElement : Microsoft.ServiceBus.HttpRelayTransportBindingElement -&gt; Microsoft.ServiceBus.HttpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpRelayTransportBindingElement elementToBeCloned" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="elementToBeCloned" Type="Microsoft.ServiceBus.HttpRelayTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="elementToBeCloned"><span data-ttu-id="cf8bf-103">複製対象となる要素。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-103">The element to be cloned.</span></span></param>
        <summary><span data-ttu-id="cf8bf-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />クラス、クローンを作成する、指定した要素を使用します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> class, using the specified element to be cloned.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportBindingElement (Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.#ctor(Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.HttpRelayTransportBindingElement : Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.HttpRelayTransportBindingElement" Usage="new Microsoft.ServiceBus.HttpRelayTransportBindingElement relayClientAuthenticationType" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="relayClientAuthenticationType"><span data-ttu-id="cf8bf-105">クライアント認証の種類。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-105">The client authentication type.</span></span></param>
        <summary><span data-ttu-id="cf8bf-106">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />クラス、指定したクライアント認証の種類を使用します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-106">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> class using the specified client authentication type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-107">クライアントがクッキーを受け入れて、それらを今後の要求に反映させるかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-107">Gets or sets a value that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="cf8bf-108">cookie を許可する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-108">true if cookies are allowed; otherwise, false.</span></span> <span data-ttu-id="cf8bf-109">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-109">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelFactory&lt;TChannel&gt; BuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelFactory`1&lt;!!TChannel&gt; BuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.BuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelFactory(Of TChannel) (context As BindingContext) As IChannelFactory(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelFactory&lt;'Channel&gt;" Usage="httpRelayTransportBindingElement.BuildChannelFactory context" />
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
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="cf8bf-110">チャネルのバインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-110">The binding context for the channel.</span></span></param>
        <summary><span data-ttu-id="cf8bf-111">チャネルを作成するために使用できるチャネル ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-111">Creates a channel factory that can be used to create a channel.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-112">指定した型のチャネル ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-112">The channel factory of the specified type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.IChannelListener&lt;TChannel&gt; BuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.IChannelListener`1&lt;!!TChannel&gt; BuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.BuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function BuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As IChannelListener(Of TChannel)" />
      <MemberSignature Language="F#" Value="override this.BuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; System.ServiceModel.Channels.IChannelListener&lt;'Channel (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)&gt; (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="httpRelayTransportBindingElement.BuildChannelListener context" />
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
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="cf8bf-113">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-113">The binding context.</span></span></param>
        <summary><span data-ttu-id="cf8bf-114">指定されたジェネリック型のチャネルに対するチャネル リスナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-114">Creates a channel listener for channels of the specified generic type.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-115">チャネル リスナー。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-115">A channel listener.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelFactory&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelFactory&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelFactory&lt;TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CanBuildChannelFactory``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelFactory(Of TChannel) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelFactory : System.ServiceModel.Channels.BindingContext -&gt; bool" Usage="httpRelayTransportBindingElement.CanBuildChannelFactory context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TChannel" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="context" Type="System.ServiceModel.Channels.BindingContext" />
      </Parameters>
      <Docs>
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="cf8bf-116">チャネルのバインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-116">The binding context for the channel.</span></span></param>
        <summary><span data-ttu-id="cf8bf-117">指定した種類のチャネル ファクトリを作成できるかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-117">Determines whether a channel factory of the specified type can be built.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-118">true の場合、チャネル ファクトリを作成することができます。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-118">true if a channel factory can be built; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanBuildChannelListener&lt;TChannel&gt;">
      <MemberSignature Language="C#" Value="public override bool CanBuildChannelListener&lt;TChannel&gt; (System.ServiceModel.Channels.BindingContext context) where TChannel : class, System.ServiceModel.Channels.IChannel;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanBuildChannelListener&lt;class (class System.ServiceModel.Channels.IChannel) TChannel&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CanBuildChannelListener``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanBuildChannelListener(Of TChannel As {Class, IChannel}) (context As BindingContext) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanBuildChannelListener : System.ServiceModel.Channels.BindingContext -&gt; bool (requires 'Channel : null and 'Channel :&gt; System.ServiceModel.Channels.IChannel)" Usage="httpRelayTransportBindingElement.CanBuildChannelListener context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
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
        <typeparam name="TChannel">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="cf8bf-119">バインド要素のコンテキストを提供するバインディング コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-119">The binding context that provides context for the binding element.</span></span></param>
        <summary><span data-ttu-id="cf8bf-120">指定した種類のチャネルに対するリスナーをバインド要素が作成できるかどうかを示す値を返します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-120">Returns a value that indicates whether the binding element can build a listener for a specific type of channel.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-121">true の場合、IChannelListener&lt;TChannel&gt;の型 IChannel できるは、それ以外のバインド要素によって作成 false。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-121">true if the IChannelListener&lt;TChannel&gt; of type IChannel can be built by the binding element; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="cf8bf-122">コンテキストが null です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-122">context is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElement Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElement Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Clone () As BindingElement" />
      <MemberSignature Language="F#" Value="override this.Clone : unit -&gt; System.ServiceModel.Channels.BindingElement" Usage="httpRelayTransportBindingElement.Clone " />
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
        <summary><span data-ttu-id="cf8bf-123">バインド要素オブジェクトのコピーを返します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-123">Returns a copy of the binding element object.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-124">返します、<see cref="T:System.ServiceModel.Channels.BindingElement" />オリジナルのディープ クローンを格納しています。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-124">Returns a <see cref="T:System.ServiceModel.Channels.BindingElement" /> that contains a deep clone of the original.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected virtual System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.HttpTransportBindingElement CreateInnerChannelBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.CreateInnerChannelBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateInnerChannelBindingElement () As HttpTransportBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateInnerChannelBindingElement : unit -&gt; System.ServiceModel.Channels.HttpTransportBindingElement&#xA;override this.CreateInnerChannelBindingElement : unit -&gt; System.ServiceModel.Channels.HttpTransportBindingElement" Usage="httpRelayTransportBindingElement.CreateInnerChannelBindingElement " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.HttpTransportBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cf8bf-125">作成、<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルにします。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-125">Creates a <see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" /> for the inner channel.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-126">A<see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" />内部チャネルにします。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-126">A <see cref="T:System.ServiceModel.Channels.HttpTransportBindingElement" /> for the inner channel.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProperty&lt;T&gt;">
      <MemberSignature Language="C#" Value="public override T GetProperty&lt;T&gt; (System.ServiceModel.Channels.BindingContext context) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance !!T GetProperty&lt;class T&gt;(class System.ServiceModel.Channels.BindingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.GetProperty``1(System.ServiceModel.Channels.BindingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetProperty(Of T As Class) (context As BindingContext) As T" />
      <MemberSignature Language="F#" Value="override this.GetProperty : System.ServiceModel.Channels.BindingContext -&gt; 'T (requires 'T : null)" Usage="httpRelayTransportBindingElement.GetProperty context" />
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
        <typeparam name="T">To be added.</typeparam>
        <param name="context"> <span data-ttu-id="cf8bf-127">バインド コンテキスト。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-127">The binding context.</span></span></param>
        <summary><span data-ttu-id="cf8bf-128">指定したバインド コンテキストから指定したプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-128">Gets the specified property from the specified binding context.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-129">指定したバインド コンテキストからプロパティです。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-129">The property from the specified binding context.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransportTokenAssertion">
      <MemberSignature Language="C#" Value="public System.Xml.XmlElement GetTransportTokenAssertion ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Xml.XmlElement GetTransportTokenAssertion() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.GetTransportTokenAssertion" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTransportTokenAssertion () As XmlElement" />
      <MemberSignature Language="F#" Value="abstract member GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement&#xA;override this.GetTransportTokenAssertion : unit -&gt; System.Xml.XmlElement" Usage="httpRelayTransportBindingElement.GetTransportTokenAssertion " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.ServiceModel.Channels.ITransportTokenAssertionProvider.GetTransportTokenAssertion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cf8bf-130">セキュリティ バインドで使用されるトランスポート トークンを表す XML 要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-130">Gets the XML element that represents the transport token used in the security binding.</span></span></summary>
        <returns><span data-ttu-id="cf8bf-131">セキュリティ バインドで使用されるトランスポート トークンです。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-131">The transport token used in the security binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-132">取得またはホスト名比較モードを使用するを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-132">Gets or sets the comparison mode use in the host name.</span></span></summary>
        <value><span data-ttu-id="cf8bf-133">ホスト名に、比較モードを使用します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-133">The comparison mode use in the host name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeInnerChannelBindingElement">
      <MemberSignature Language="C#" Value="protected virtual void InitializeInnerChannelBindingElement (System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void InitializeInnerChannelBindingElement(class System.ServiceModel.Channels.HttpTransportBindingElement httpTransportElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.InitializeInnerChannelBindingElement(System.ServiceModel.Channels.HttpTransportBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub InitializeInnerChannelBindingElement (httpTransportElement As HttpTransportBindingElement)" />
      <MemberSignature Language="F#" Value="abstract member InitializeInnerChannelBindingElement : System.ServiceModel.Channels.HttpTransportBindingElement -&gt; unit&#xA;override this.InitializeInnerChannelBindingElement : System.ServiceModel.Channels.HttpTransportBindingElement -&gt; unit" Usage="httpRelayTransportBindingElement.InitializeInnerChannelBindingElement httpTransportElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpTransportElement" Type="System.ServiceModel.Channels.HttpTransportBindingElement" />
      </Parameters>
      <Docs>
        <param name="httpTransportElement"> <span data-ttu-id="cf8bf-134">初期化するためにバインド要素。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-134">The binding element to initialize.</span></span></param>
        <summary><span data-ttu-id="cf8bf-135">現在のインスタンスの設定で指定されたバインド要素の初期化、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" />バインド要素。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-135">Initializes the specified binding element with the settings from the current instance of the<see cref="T:Microsoft.ServiceBus.HttpRelayTransportBindingElement" /> binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-136">取得またはバインド要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-136">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="cf8bf-137">バインド要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-137">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveEnabled">
      <MemberSignature Language="C#" Value="public bool KeepAliveEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool KeepAliveEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.KeepAliveEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.KeepAliveEnabled : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.KeepAliveEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-138">サービス エンドポイントへの永続的な接続を行うかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-138">Gets or sets a value that indicates whether to make a persistent connection to a service endpoint.</span></span> </summary>
        <value><span data-ttu-id="cf8bf-139">true の場合は、サービス エンドポイントに要求がキープ アライブ; の値を持つ接続 HTTP ヘッダーを含める必要があります。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-139">true if the request to the service endpoint should contain a Connection HTTP header with the value Keep-alive; otherwise, false.</span></span> <span data-ttu-id="cf8bf-140">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-140">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-141">使用するバッファーの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-141">Gets or sets the maximum size of the buffer to use.</span></span></summary>
        <value><span data-ttu-id="cf8bf-142">バッファーのバイト単位の最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-142">Returns the maximum size, in bytes, of the buffer.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-143">HTTP 要求に使用するプロキシのアドレスを格納する URI を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-143">Gets or sets a URI that contains the address of the proxy to use for HTTP requests.</span></span></summary>
        <value><span data-ttu-id="cf8bf-144">返します、<see cref="T:System.Uri" />プロキシのアドレスを格納します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-144">Returns a <see cref="T:System.Uri" /> that contains the address for the proxy.</span></span> <span data-ttu-id="cf8bf-145">既定値は NULL です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-145">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAuthenticationScheme">
      <MemberSignature Language="C#" Value="public System.Net.AuthenticationSchemes ProxyAuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.AuthenticationSchemes ProxyAuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAuthenticationScheme As AuthenticationSchemes" />
      <MemberSignature Language="F#" Value="member this.ProxyAuthenticationScheme : System.Net.AuthenticationSchemes with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.ProxyAuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.AuthenticationSchemes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-146">HTTP プロキシにより処理されるクライアント要求の認証に使用する認証方式を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-146">Gets or sets the authentication scheme used to authenticate client requests being processed by an HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="cf8bf-147">値のいずれか、<see cref="T:System.Net.AuthenticationSchemes" />プロキシでのクライアント認証を使用するプロトコルを指定する列挙体です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-147">One of the values of the <see cref="T:System.Net.AuthenticationSchemes" /> enumeration that specifies the protocols used for client authentication on the proxy.</span></span> <span data-ttu-id="cf8bf-148">既定は Anonymous です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-148">The default is Anonymous.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-149">取得またはリレー クライアントの認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-149">Gets or sets the relay client authentication type.</span></span> </summary>
        <value><span data-ttu-id="cf8bf-150">返します<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />です。認証の種類が含まれています。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-150">Returns <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />.Contains the authentication type.</span></span> <span data-ttu-id="cf8bf-151">既定値は RelayClientAuthenticationType.RelayAccessToken</span><span class="sxs-lookup"><span data-stu-id="cf8bf-151">The default value is RelayClientAuthenticationType.RelayAccessToken</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-152">トランスポートの URI スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-152">Gets the URI scheme for the transport.</span></span></summary>
        <value><span data-ttu-id="cf8bf-153">URI スキームを返します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-153">Returns the URI scheme.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy">
      <MemberSignature Language="C#" Value="void IPolicyExportExtension.ExportPolicy (System.ServiceModel.Description.MetadataExporter exporter, System.ServiceModel.Description.PolicyConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IPolicyExportExtension.ExportPolicy(class System.ServiceModel.Description.MetadataExporter exporter, class System.ServiceModel.Description.PolicyConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IPolicyExportExtension#ExportPolicy(System.ServiceModel.Description.MetadataExporter,System.ServiceModel.Description.PolicyConversionContext)" />
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
        <param name="exporter"><span data-ttu-id="cf8bf-154">エクスポート プロセスを変更に使用できる MetadataExporter です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-154">The MetadataExporter that you can use to modify the exporting process.</span></span></param>
        <param name="context"><span data-ttu-id="cf8bf-155">カスタム ポリシー アサーションの挿入に使用できる PolicyConversionContext です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-155">The PolicyConversionContext that you can use to insert your custom policy assertion.</span></span></param>
        <summary>
            <span data-ttu-id="cf8bf-156">このバインドに関するカスタム ポリシー アサーションをエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-156">Exports a custom policy assertion about this binding.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportContract">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportContract (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlContractConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportContract(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlContractConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportContract(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlContractConversionContext)" />
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
        <param name="exporter"><span data-ttu-id="cf8bf-157">この WsdlExporter は、コントラクト情報をエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-157">The WsdlExporter that exports the contract information.</span></span></param>
        <param name="context"><span data-ttu-id="cf8bf-158">エクスポートされた WSDL 要素からコントラクトの説明へのマッピングを提供します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-158">Provides mappings from exported WSDL elements to the contract description.</span></span></param>
        <summary>
            <span data-ttu-id="cf8bf-159">コントラクトに対して生成される Web サービス記述言語 (WSDL) に、カスタム WSDL 要素を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-159">Writes custom Web Services Description Language (WSDL) elements into the generated WSDL for a contract.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint">
      <MemberSignature Language="C#" Value="void IWsdlExportExtension.ExportEndpoint (System.ServiceModel.Description.WsdlExporter exporter, System.ServiceModel.Description.WsdlEndpointConversionContext context);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.ServiceModel.Description.IWsdlExportExtension.ExportEndpoint(class System.ServiceModel.Description.WsdlExporter exporter, class System.ServiceModel.Description.WsdlEndpointConversionContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.HttpRelayTransportBindingElement.System#ServiceModel#Description#IWsdlExportExtension#ExportEndpoint(System.ServiceModel.Description.WsdlExporter,System.ServiceModel.Description.WsdlEndpointConversionContext)" />
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
        <param name="exporter"><span data-ttu-id="cf8bf-160">この WsdlExporter は、コントラクト情報をエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-160">The WsdlExporter that exports the contract information.</span></span></param>
        <param name="context"><span data-ttu-id="cf8bf-161">エクスポートされた WSDL 要素からコントラクトの説明へのマッピングを提供します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-161">Provides mappings from exported WSDL elements to the contract description.</span></span></param>
        <summary>
            <span data-ttu-id="cf8bf-162">エンドポイントに対して生成される Web サービス記述言語 (WSDL) に、カスタム WSDL 要素を書き込みます。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-162">Writes custom Web Services Description Language (WSDL) elements into the generated WSDL for an endpoint.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-163">転送モードを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-163">Gets or sets the transfer mode.</span></span></summary>
        <value><span data-ttu-id="cf8bf-164">返します、<see cref="T:System.ServiceModel.TransferMode" />転送モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-164">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains the transfer mode.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.HttpRelayTransportBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.HttpRelayTransportBindingElement.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="cf8bf-165">ユーザー固有の設定ではなく、コンピューター全体のプロキシ設定を使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-165">Gets or sets a value that indicates whether the machine-wide proxy settings are used rather than the user specific settings.</span></span></summary>
        <value><span data-ttu-id="cf8bf-166">true の場合は、コンピューター全体のプロキシ設定が使用されます。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-166">true if the machine-wide proxy settings are used; otherwise, false.</span></span> <span data-ttu-id="cf8bf-167">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="cf8bf-167">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>