<Type Name="WebHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class WebHttpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHttpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHttpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type WebHttpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="7ac4b-101">SOAP メッセージに代わって HTTP 要求に応答する Azure Service Bus リレー サービスのエンドポイントを構成するために使用するバインド要素。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-101">A binding element used to configure endpoints for an Azure Service Bus relay service that responds to HTTP requests instead of SOAP messages.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="7ac4b-102"><see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7ac4b-103">新しいバインド要素の名前。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-103">The name of the new binding element.</span></span></param>
        <summary><span data-ttu-id="7ac4b-104">指定された名前を使用して、<see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement" /> class using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("allowCookies", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-105">クライアントがクッキーを受け入れて、それらを今後の要求に反映させるかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-105">Gets or sets a value that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="7ac4b-106">cookie を許可する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-106">true if cookies are allowed; otherwise, false.</span></span> <span data-ttu-id="7ac4b-107">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-107">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-108">この構成要素を表すバインディングの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-108">Gets the type of binding that this configuration element represents.</span></span></summary>
        <value><span data-ttu-id="7ac4b-109">返します、<see cref="T:System.Type" />バインドの種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-109">Returns a <see cref="T:System.Type" /> that contains the binding type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.InitializeFrom binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="7ac4b-110">この構成要素を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-110">The binding to update this configuration element from.</span></span></param>
        <summary><span data-ttu-id="7ac4b-111">指定したバインディングのプロパティ値からこのバインド構成要素の内容を初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-111">Initializes the contents of this binding configuration element from the property values of a specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("isDynamic", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-112">取得またはバインド要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-112">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="7ac4b-113">バインド要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-113">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferPoolSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=0)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-114">このバイディングを使用するエンドポイントが必要とするバッファーを管理するバッファー マネージャーに割り当てるメモリの最大量を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-114">Gets or sets the maximum amount of memory allocated for the buffer manager that manages the buffers required by endpoints that use this binding.</span></span></summary>
        <value><span data-ttu-id="7ac4b-115">このバインディングで構成されるエンドポイントによって使用されるバッファーのプールのバイト単位で最大のサイズを返します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-115">Returns the maximum size, in bytes, for the pool of buffers used by an endpoint configured with this binding.</span></span> <span data-ttu-id="7ac4b-116">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-116">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-117">チャネルからメッセージを受け取るメッセージ バッファー マネージャーが使用するために割り当てられる最大メモリ量を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-117">Gets or sets the maximum amount of memory that is allocated for use by the manager of the message buffers that receive messages from the channel.</span></span></summary>
        <value><span data-ttu-id="7ac4b-118">(バイト)、メッセージ バッファー マネージャーで使用可能な最大メモリ量を返します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-118">Returns the maximum amount of memory, in bytes, available for use by the message buffer manager.</span></span> <span data-ttu-id="7ac4b-119">既定値は 524,288 (0x80000) バイトです。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-119">The default value is 524,288 (0x80000) bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7ac4b-120">値が 0 以下の値に設定されています。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-120">The value set is less than or equal to zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxReceivedMessageSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.LongValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-121">バインディングで処理可能なメッセージの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-121">Gets or sets the maximum size for a message that can be processed by the binding.</span></span></summary>
        <value><span data-ttu-id="7ac4b-122">(バイト単位) は、バインディングによって処理されるメッセージの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-122">Returns the maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="7ac4b-123">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-123">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7ac4b-124">値が 0 未満です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-124">The value is less than zero.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="webHttpRelayBindingElement.OnApplyConfiguration binding" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binding" Type="System.ServiceModel.Channels.Binding" />
      </Parameters>
      <Docs>
        <param name="binding"> <span data-ttu-id="7ac4b-125">設定を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-125">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="7ac4b-126">指定されたバインディングには、この構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-126">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-127">属性を保持できるオブジェクト、またはこの構成要素の構成要素オブジェクトのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-127">Gets a collection of objects that can be attributes or configuration element objects of this configuration element.</span></span></summary>
        <value><span data-ttu-id="7ac4b-128">返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />属性を保持できる ConfigurationProperty オブジェクトまたは ConfigurationElement オブジェクトでこの構成要素のコレクションを格納します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-128">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects on this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyAddress", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-129">HTTP プロキシの URI アドレスを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-129">Gets or sets the URI address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="7ac4b-130">返します、 <see cref="T:System.Uri" /> HTTP プロキシのアドレスとして機能します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-130">Returns a <see cref="T:System.Uri" /> that serves as the address of the HTTP proxy.</span></span> <span data-ttu-id="7ac4b-131">既定値は NULL です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-131">The default value is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("readerQuotas")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-132">このバインディングを使用して構成されるエンドポイントにより処理可能な、SOAP メッセージの複雑さに対する制約を格納する構成要素を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-132">Gets or sets the configuration element that contains the constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="7ac4b-133">返します、<see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" />複雑さの制約を格納しています。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-133">Returns an <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that contains the complexity restraints.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="7ac4b-134">値セットが null です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-134">The valueset is null.</span></span></exception>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="7ac4b-135">XmlDictionaryReaderQuotas のクォータ値は読み取り専用です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-135">The quota values of XmlDictionaryReaderQuotas are read only.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="7ac4b-136">必ず正のクォータ値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-136">The quotas set must be positive.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WebHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("security")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-137">このバインディングで使用されるセキュリティ設定を格納する構成要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-137">Gets the configuration element that contains the security settings used with this binding.</span></span></summary>
        <value><span data-ttu-id="7ac4b-138">返します、<see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" />このバインディングのセキュリティ設定を格納しています。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-138">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.WebHttpRelaySecurityElement" /> that contains the security settings for this binding.</span></span> <span data-ttu-id="7ac4b-139">既定値は none です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-139">The default value is none.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transferMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-140">取得またはサービスがメッセージ転送の関連付けられているバインド (またはその両方) を使用してストリーム、バッファー モードで構成されているかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-140">Gets or sets a value that indicates whether the service configured with the associated binding uses streamed or buffered (or both) modes of message transfer.</span></span></summary>
        <value><span data-ttu-id="7ac4b-141">返します、<see cref="T:System.ServiceModel.TransferMode" />を格納しているサービスをストリームまたはバッファー内のバインドを使用して (または両方) が構成されているかどうかを示すメッセージ転送のモード。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-141">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="7ac4b-142">既定値はバッファーです。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-142">The default value is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ComponentModel.InvalidEnumArgumentException"><span data-ttu-id="7ac4b-143">値セットは、有効な TransferMode 値ではありません。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-143">The value set is not a valid TransferMode value.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("useDefaultWebProxy", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-144">取得またはを使用可能な場合は、バインディングでは、関連付けられている、システムの自動設定 HTTP プロキシを使用するかどうかを示す値を設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-144">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used with the associated binding, if available.</span></span></summary>
        <value><span data-ttu-id="7ac4b-145">使用可能な場合、システムの自動設定 HTTP プロキシを使用する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-145">true if the auto-configured HTTP proxy of the system should be used, if available; otherwise, false.</span></span> <span data-ttu-id="7ac4b-146">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-146">The default value is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding WriteEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding WriteEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.WriteEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WebHttpRelayBindingElement.WriteEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.Configuration.EncodingConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("writeEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="7ac4b-147">取得または関連付けられているバインディングでメッセージ テキストに使用される文字エンコーディングを設定します。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-147">Gets or sets the character encoding that is used for the message text in the associated binding.</span></span></summary>
        <value><span data-ttu-id="7ac4b-148">返します、<see cref="T:System.Text.Encoding" />を示すために使用される文字エンコーディングします。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-148">Returns a <see cref="T:System.Text.Encoding" /> that indicates the character encoding that is used.</span></span> <span data-ttu-id="7ac4b-149">既定値は、UTF8Encoding です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-149">The default is UTF8Encoding.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="7ac4b-150">設定されている値は null です。</span><span class="sxs-lookup"><span data-stu-id="7ac4b-150">The value set is null.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>