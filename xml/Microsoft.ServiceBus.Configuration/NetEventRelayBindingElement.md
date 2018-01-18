<Type Name="NetEventRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetEventRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetEventRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetEventRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetEventRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3dffc-101">構成設定について説明する構成要素、<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="3dffc-101">A configuration element that describes configuration settings for the <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3dffc-102"><see cref="T:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3dffc-103">バインディング名は、構成で設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-103">The binding name set in the configuration.</span></span></param>
        <summary><span data-ttu-id="3dffc-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" />クラス、指定した名前を使用します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement" /> class, using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3dffc-105">この構成要素を表すバインディングの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-105">Gets the type of binding that this configuration element represents.</span></span></summary>
        <value><span data-ttu-id="3dffc-106">返します、<see cref="T:System.Type" />バインドの種類を格納しているの種類は<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-106">Returns a <see cref="T:System.Type" /> that contains the binding type, which is the type of <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netEventRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> <span data-ttu-id="3dffc-107">設定のコピーをバインドします。</span><span class="sxs-lookup"><span data-stu-id="3dffc-107">The binding to copy the settings from.</span></span></param>
        <summary><span data-ttu-id="3dffc-108">指定したバインディングのプロパティの値からこの XML 構成要素の内容を初期化します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-108">Initializes the contents of this XML configuration element from the property values of a specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("listenBacklog", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3dffc-109">保留可能なキュー内の接続要求の最大数を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-109">Gets or sets the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="3dffc-110">保留可能なキュー内の接続要求の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-110">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="3dffc-111">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="3dffc-111">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="3dffc-112">取得または、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-112">Gets or sets the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="3dffc-113">バインディングによって処理されるメッセージを格納するバッファー プールに入力できる最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-113">Returns the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span> <span data-ttu-id="3dffc-114">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="3dffc-114">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="3dffc-115">取得またはメッセージをメモリに格納するために使用するバッファーのバイト単位で最大のサイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-115">Gets or sets the maximum size, in bytes, of the buffer used to store messages in memory.</span></span></summary>
        <value><span data-ttu-id="3dffc-116">(バイト単位) をメモリにメッセージを保存するために使用するバッファーの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-116">Returns the maximum size, in bytes, of the buffer used to store messages in memory.</span></span> <span data-ttu-id="3dffc-117">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="3dffc-117">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3dffc-118">取得またはクライアント上の後続の再利用のためにプールできる接続の最大数と、サーバー上でディスパッチを保留できる接続の最大数を設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-118">Gets or sets the maximum number of connections to be pooled for subsequent reuse on the client and the maximum number of connections allowed to be pending dispatch on the server.</span></span></summary>
        <value><span data-ttu-id="3dffc-119">クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-119">On the client, returns the maximum number of connections to be pooled for subsequent reuse; on the server, returns the maximum number of connections allowed to be pending dispatch.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="3dffc-120">このバインドで処理される受信メッセージの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-120">Gets or sets the maximum size for a received message that is processed by the binding.</span></span></summary>
        <value><span data-ttu-id="3dffc-121">バインディングによって処理される受信メッセージのバイト単位で最大のサイズを返します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-121">Returns the maximum size, in bytes, for a received message that is processed by the binding.</span></span> <span data-ttu-id="3dffc-122">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="3dffc-122">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netEventRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> <span data-ttu-id="3dffc-123">設定を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="3dffc-123">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="3dffc-124">指定されたバインディングには、この構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-124">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3dffc-125">コレクションを取得する属性を保持できるオブジェクト、またはこのバインディング構成要素の構成要素のオブジェクトが含まれています。</span><span class="sxs-lookup"><span data-stu-id="3dffc-125">Gets a collection that contains objects that can be attributes or configuration element objects of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="3dffc-126">返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="3dffc-126">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="3dffc-127">取得または設定をこのバインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を含む XML 要素。</span><span class="sxs-lookup"><span data-stu-id="3dffc-127">Gets or sets an XML element that contains the constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="3dffc-128">返します、 <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> SOAP メッセージに対する複雑さの制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-128">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that specifies the complexity constraints on SOAP messages.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetOnewayRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetEventRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3dffc-129">Azure Service Bus net イベント リレー バインドのセキュリティ オプションを格納する構成要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="3dffc-129">Gets a configuration element that contains the security options for an Azure Service Bus net event relay binding.</span></span></summary>
        <value><span data-ttu-id="3dffc-130">返します、<see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" />セキュリティ オプションの説明です。</span><span class="sxs-lookup"><span data-stu-id="3dffc-130">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.NetOnewayRelaySecurityElement" /> that describes the security options.</span></span> <span data-ttu-id="3dffc-131">既定値は、トランスポートです。</span><span class="sxs-lookup"><span data-stu-id="3dffc-131">The default is Transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>