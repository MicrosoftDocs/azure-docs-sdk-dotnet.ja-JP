<Type Name="NetTcpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="364bb-101">Azure Service Bus リレーを介してコンピューター間通信に適した、セキュリティで保護された信頼できるバインディングを説明する構成要素。</span><span class="sxs-lookup"><span data-stu-id="364bb-101">A configuration element that describes a secure, reliable binding suitable for cross-machine communication through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="364bb-102"><see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="364bb-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="364bb-103">バインド構成の名前。</span><span class="sxs-lookup"><span data-stu-id="364bb-103">The binding configuration name.</span></span></param>
        <summary><span data-ttu-id="364bb-104">構成名を指定して、<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="364bb-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement" /> class with a specified configuration name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="364bb-105">この構成要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="364bb-105">Gets the type of this configuration element.</span></span> <span data-ttu-id="364bb-106">(StandardBindingElement.BindingElementType をオーバーライドします)。</span><span class="sxs-lookup"><span data-stu-id="364bb-106">(Overrides StandardBindingElement.BindingElementType.)</span></span></summary>
        <value><span data-ttu-id="364bb-107">返します、<see cref="T:System.Type" />構成要素の型を格納しています。</span><span class="sxs-lookup"><span data-stu-id="364bb-107">Returns a <see cref="T:System.Type" /> that contains the configuration element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="364bb-108">取得または、この構成用の App.config ファイルに格納されている接続モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-108">Gets or sets the connection mode stored in the App.config file for this configuration.</span></span></summary>
        <value><span data-ttu-id="364bb-109">返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />既定値が転送される接続モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="364bb-109">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode The default is Relayed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"> <span data-ttu-id="364bb-110">初期化するためにバインドします。</span><span class="sxs-lookup"><span data-stu-id="364bb-110">The binding to initialize from.</span></span></param>
        <summary><span data-ttu-id="364bb-111">指定したバインディングのプロパティ値からこのバインド構成要素の内容を初期化します。</span><span class="sxs-lookup"><span data-stu-id="364bb-111">Initializes the contents of this binding configuration element from the property values of a specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.IsDynamic" />
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
        <summary><span data-ttu-id="364bb-112">取得またはリレー バインドが動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-112">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="364bb-113">リレー バインドは、動的; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="364bb-113">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ListenBacklog" />
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
        <summary><span data-ttu-id="364bb-114">取得またはリスナーで受け入れられるを待機できるチャネルの最大数を指定する App.config ファイルで値を設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-114">Gets or sets a value in the App.config file that specifies the maximum number of channels that can wait to be accepted on the listener.</span></span></summary>
        <value><span data-ttu-id="364bb-115">保留可能なキュー内の接続要求の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="364bb-115">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="364bb-116">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="364bb-116">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="364bb-117">取得または、バインディングによって処理される TCP メッセージを格納するバッファー プールの最大サイズを含む App.config ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-117">Gets or sets a value from the App.config file that contains the maximum size for a buffer pool that stores TCP messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="364bb-118">バインディングによって処理されるメッセージを格納するバッファー プールに入力できる最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="364bb-118">Returns the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span> <span data-ttu-id="364bb-119">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="364bb-119">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="364bb-120">取得またはメッセージをメモリに格納するために使用するバッファーのバイト単位で最大のサイズを指定する App.config ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-120">Gets or sets a value from the App.config file that specifies the maximum size, in bytes, of the buffer used to store messages in memory.</span></span></summary>
        <value><span data-ttu-id="364bb-121">メモリ内でメッセージの保存に使用されるバッファーの最大サイズ (バイト単位)。</span><span class="sxs-lookup"><span data-stu-id="364bb-121">The maximum size, in bytes, of the buffer used to store messages in memory.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxConnections" />
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
        <summary><span data-ttu-id="364bb-122">取得またはサービスを作成および受け入れる発信/着信接続の最大数を指定する App.config ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-122">Gets or sets a value from the App.config file that specifies the maximum number of outbound and inbound connections the service creates and accepts respectively.</span></span></summary>
        <value><span data-ttu-id="364bb-123">クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="364bb-123">On the client, returns the maximum number of connections to be pooled for subsequent reuse; on the server, returns the maximum number of connections allowed to be pending dispatch.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="364bb-124">取得または、このバインディングで構成されるチャネルで受信可能なメッセージの最大サイズを含む App.config ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-124">Gets or sets a value from the App.config file that contains the maximum size of a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="364bb-125">(バイト単位) は、バインディングによって処理されるメッセージの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="364bb-125">Returns maximum size, in bytes, for a message that is processed by the binding.</span></span> <span data-ttu-id="364bb-126">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="364bb-126">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="netTcpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"> <span data-ttu-id="364bb-127">設定を更新するバインディング。</span><span class="sxs-lookup"><span data-stu-id="364bb-127">The binding to update the settings of.</span></span></param>
        <summary><span data-ttu-id="364bb-128">指定されたバインド要素をこの構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="364bb-128">Applies the settings of this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="364bb-129">属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納する ConfigurationPropertyCollection インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="364bb-129">Gets a ConfigurationPropertyCollection instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span> <span data-ttu-id="364bb-130">(StandardBindingElement.Properties をオーバーライドします)。</span><span class="sxs-lookup"><span data-stu-id="364bb-130">(Overrides StandardBindingElement.Properties.)</span></span></summary>
        <value><span data-ttu-id="364bb-131">属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクション。</span><span class="sxs-lookup"><span data-stu-id="364bb-131">A collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="364bb-132">このバインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を課すを App.config ファイルから値を取得します。</span><span class="sxs-lookup"><span data-stu-id="364bb-132">Gets a value from the App.config file that puts constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="364bb-133">返します、<see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" />交換される SOAP メッセージに対する複雑さの制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="364bb-133">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that specifies the complexity constraints on SOAP messages exchanged.</span></span> <span data-ttu-id="364bb-134">これらの制約の既定値については、後の「解説」で説明します。</span><span class="sxs-lookup"><span data-stu-id="364bb-134">The default values for these constraints are provided in the following Remarks section.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As StandardBindingOptionalReliableSessionElement" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.ReliableSession" />
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
        <summary><span data-ttu-id="364bb-135">チャネルのエンドポイント間に信頼できるセッションを確立するかどうかを指定する構成要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="364bb-135">Gets a configuration element that specifies whether reliable sessions are established between channel endpoints.</span></span></summary>
        <value><span data-ttu-id="364bb-136">返します、<see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" />チャネルのエンドポイント間に WS-RM 信頼できるセッションが確立するかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="364bb-136">Returns a <see cref="T:System.ServiceModel.Configuration.StandardBindingOptionalReliableSessionElement" /> that indicates whether a WS-RM reliable session is established between channel endpoints.</span></span> <span data-ttu-id="364bb-137">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="364bb-137">The default value is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="364bb-138">このバインディングで使用されるセキュリティの種類を決定する App.config ファイルから値を取得します。</span><span class="sxs-lookup"><span data-stu-id="364bb-138">Gets a value from the App.config file that determines the type of security to be used with this binding.</span></span></summary>
        <value><span data-ttu-id="364bb-139">返します、<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />関連付けられているバインディングのセキュリティ設定を格納しています。</span><span class="sxs-lookup"><span data-stu-id="364bb-139">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> that contains the security settings for the associated binding.</span></span> <span data-ttu-id="364bb-140">既定値は none です。<see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />関連付けられているから取得する、NetTcpRelayBinding でバインドが直接作成されます。</span><span class="sxs-lookup"><span data-stu-id="364bb-140">The default value is none.The <see cref="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" /> you retrieve from the associated binding is created indirectly with a NetTcpRelayBinding.</span></span> <span data-ttu-id="364bb-141">そのため、バインドを作成すると後も、新しいバインディングを作成しない限り、新しいオブジェクトにこのオブジェクトを置き換えることはできません。</span><span class="sxs-lookup"><span data-stu-id="364bb-141">As such, after the binding is created, you cannot replace this object with a new object unless you also create a new binding.</span></span> <span data-ttu-id="364bb-142">ただし、WebHttpRelaySecurity の多くのメンバーは、セキュリティのプロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="364bb-142">However, many members of WebHttpRelaySecurity can be set through security property.</span></span> <span data-ttu-id="364bb-143">バインディングのセキュリティの詳細については、セキュリティと保護のセクションを参照してください。</span><span class="sxs-lookup"><span data-stu-id="364bb-143">For more information on binding security, see the Security and Protection section.</span></span> <span data-ttu-id="364bb-144">と共に、トランスポートとエンコードの種類は、セキュリティ設定は、このバインディングを定義する 3 つの主要なプロパティのいずれかを表します。</span><span class="sxs-lookup"><span data-stu-id="364bb-144">Along with the type of transport and encoding, the Security settings represent one of the three main properties that define this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" />
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
        <summary><span data-ttu-id="364bb-145">取得またはメッセージをバッファリングまたはストリームするかどうか、または要求を指定する App.config ファイルから値を設定または応答します。</span><span class="sxs-lookup"><span data-stu-id="364bb-145">Gets or sets a value from the App.config file that specifies whether messages are buffered or streamed or a request or response.</span></span></summary>
        <value><span data-ttu-id="364bb-146">返します、<see cref="T:System.ServiceModel.TransferMode" />を格納しているサービスをストリームまたはバッファー内のバインドを使用して (または両方) が構成されているかどうかを示すメッセージ転送のモード。</span><span class="sxs-lookup"><span data-stu-id="364bb-146">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="364bb-147">使用可能な値は次のとおり: BufferedStreamedStreamedRequestStreamedResponseThe 既定値は Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> Streamed に StreamedRequest と StreamedResponse の両方を意味します。</span><span class="sxs-lookup"><span data-stu-id="364bb-147">The possible values are as follows: BufferedStreamedStreamedRequestStreamedResponseThe default value is Buffered.Specifying <see cref="P:Microsoft.ServiceBus.Configuration.NetTcpRelayBindingElement.TransferMode" /> to Streamed implies both StreamedRequest and StreamedResponse.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>