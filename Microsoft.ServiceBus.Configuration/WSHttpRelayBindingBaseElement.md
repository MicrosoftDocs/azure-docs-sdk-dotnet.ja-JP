<Type Name="WSHttpRelayBindingBaseElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingBaseElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingBaseElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingBaseElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingBaseElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="fc659-101">基本クラスを提供、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" />分散トランザクションとセキュリティで保護された信頼できるセッションをサポートするバインディングを指定する構成要素。</span><span class="sxs-lookup"><span data-stu-id="fc659-101">Provides a base class for the<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingElement" /> configuration element that specifies a binding that supports distributed transactions and secure, reliable sessions.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBaseElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="fc659-102"><see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc659-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBaseElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement : string -&gt; Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" Usage="new Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fc659-103">この構成要素を一意に識別する名前。</span><span class="sxs-lookup"><span data-stu-id="fc659-103">A name that uniquely identifies this configuration element.</span></span></param>
        <summary><span data-ttu-id="fc659-104">指定した名前を使用して、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc659-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement" /> class with the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingBaseElement.InitializeFrom binding" />
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
        <param name="binding"> <span data-ttu-id="fc659-105">バインディング。</span><span class="sxs-lookup"><span data-stu-id="fc659-105">A binding.</span></span></param>
        <summary><span data-ttu-id="fc659-106">このバインド構成要素を、指定されたバインディングの内容で初期化します。</span><span class="sxs-lookup"><span data-stu-id="fc659-106">Initializes this binding configuration element with the content of the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.IsDynamic" />
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
        <summary><span data-ttu-id="fc659-107">取得またはバインドの基本要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="fc659-107">Gets or sets whether the binding base element is dynamic.</span></span></summary>
        <value><span data-ttu-id="fc659-108">バインドの基本要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="fc659-108">true if the binding base element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="fc659-109">取得または設定によって処理されるメッセージを保存するバッファー プールの最大サイズ、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-109">Gets or sets the maximum size of the buffer pool that stores messages processed by the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="fc659-110">によって処理されるメッセージを格納するバッファー プールの最大サイズ、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-110">The maximum size of the buffer pool that stores messages processed by the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span> <span data-ttu-id="fc659-111">既定では 524, 288 バイトです。</span><span class="sxs-lookup"><span data-stu-id="fc659-111">The default is 524288 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="fc659-112">取得または設定で構成されるチャネルで受信したメッセージの最大サイズ、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-112">Gets or sets the maximum size for messages received on a channel configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="fc659-113">構成されるチャネルで受信したメッセージの最大サイズ、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-113">The maximum size for messages received on a channel configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span> <span data-ttu-id="fc659-114">既定値は 65536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="fc659-114">The default is 65536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("messageEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fc659-115">SOAP メッセージのエンコードに MTOM または Text/XML が使用されるかどうかを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="fc659-115">Gets or sets whether MTOM or Text/XML is used to encode SOAP messages.</span></span></summary>
        <value><span data-ttu-id="fc659-116">SOAP メッセージのエンコードに MTOM または TEXT/XML が使用されるかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="fc659-116">Indicates whether MTOM or Text/XML is used to encode SOAP messages.</span></span> <span data-ttu-id="fc659-117">既定値は、TEXT/XML です。</span><span class="sxs-lookup"><span data-stu-id="fc659-117">The default is Text/XML.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="wSHttpRelayBindingBaseElement.OnApplyConfiguration binding" />
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
        <param name="binding"> <span data-ttu-id="fc659-118">設定を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="fc659-118">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="fc659-119">指定されたバインディングには、この構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="fc659-119">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fc659-120">このバインディング構成要素のプロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fc659-120">Gets a collection of properties of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="fc659-121">このバインディング構成要素のプロパティのコレクション。</span><span class="sxs-lookup"><span data-stu-id="fc659-121">A collection of properties of this binding configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ProxyAddress" />
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
        <summary><span data-ttu-id="fc659-122">HTTP プロキシの URI アドレスを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="fc659-122">Gets or sets the URI address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="fc659-123">HTTP プロキシの URI アドレス。</span><span class="sxs-lookup"><span data-stu-id="fc659-123">The URI address of the HTTP proxy.</span></span> <span data-ttu-id="fc659-124">既定値は null です。</span><span class="sxs-lookup"><span data-stu-id="fc659-124">The default is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="fc659-125">構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を取得、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-125">Gets constraints on the complexity of SOAP messages that can be processed by endpoints configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="fc659-126">構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-126">Constraints on the complexity of SOAP messages that can be processed by endpoints configured with the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("reliableSession")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fc659-127">取得、 <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> ws-reliablemessaging で定義されているため、オプションの構成設定を表す構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-127">Gets a <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> configuration element that represents an optional configuration setting for WS-Reliable messaging defined in the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
        <value><span data-ttu-id="fc659-128">A <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> ws-reliablemessaging で定義されているため、オプションの構成設定を表す構成要素、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="fc659-128">A <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> configuration element that represents an optional configuration setting for WS-Reliable messaging defined in the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.TextEncoding" />
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
          <AttributeName>System.Configuration.ConfigurationProperty("textEncoding", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="fc659-129">メッセージ テキストに使用される文字エンコーディングを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="fc659-129">Gets or sets the character encoding that is used for the message text.</span></span></summary>
        <value><span data-ttu-id="fc659-130">文字エン コードは、メッセージ テキストに使用されます。</span><span class="sxs-lookup"><span data-stu-id="fc659-130">The character encoding that is used for the message text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelayBindingBaseElement.UseDefaultWebProxy" />
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
        <summary><span data-ttu-id="fc659-131">使用できる場合にシステムの自動構成される HTTP プロキシを使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="fc659-131">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used, if available.</span></span></summary>
        <value><span data-ttu-id="fc659-132">使用可能な場合、システムの自動設定 HTTP プロキシを使用する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="fc659-132">true if the auto-configured HTTP proxy of the system should be used, if available; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>