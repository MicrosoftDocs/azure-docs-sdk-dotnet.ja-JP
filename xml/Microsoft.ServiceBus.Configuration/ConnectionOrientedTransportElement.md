<Type Name="ConnectionOrientedTransportElement" FullName="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement">
  <TypeSignature Language="C#" Value="public abstract class ConnectionOrientedTransportElement : System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ConnectionOrientedTransportElement extends System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ConnectionOrientedTransportElement&#xA;Inherits TransportElement" />
  <TypeSignature Language="F#" Value="type ConnectionOrientedTransportElement = class&#xA;    inherit TransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.TransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="41d01-101">TCP や名前付きパイプなどの接続指向トランスポート バインド要素に、追加の構成設定を提供する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="41d01-101">Represents the configuration element that provides additional configuration settings to connection-oriented transport binding elements, such as TCP and named pipes.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="connectionOrientedTransportElement.ApplyConfiguration bindingElement" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="bindingElement" Type="System.ServiceModel.Channels.BindingElement" />
      </Parameters>
      <Docs>
        <param name="bindingElement"><span data-ttu-id="41d01-102">設定を更新するバインド要素。</span><span class="sxs-lookup"><span data-stu-id="41d01-102">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="41d01-103">この構成要素の設定を指定した <see cref="T:System.ServiceModel.Channels.BindingElement" /> に適用します。</span><span class="sxs-lookup"><span data-stu-id="41d01-103">Applies the settings of this configuration element to the specified <see cref="T:System.ServiceModel.Channels.BindingElement" />.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChannelInitializationTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan ChannelInitializationTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan ChannelInitializationTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ChannelInitializationTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.ChannelInitializationTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ChannelInitializationTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("channelInitializationTimeout", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-104">接続が切断されるまでのチャネルの初期化ステータスの最大時間を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-104">Gets or sets the maximum time the channel can be in the initialization status before being disconnected.</span></span></summary>
        <value><span data-ttu-id="41d01-105">最大時間をチャネルが切断されるまで初期化状態にすることができます。</span><span class="sxs-lookup"><span data-stu-id="41d01-105">The maximum time the channel can be in the initialization status before being disconnected.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionBufferSize">
      <MemberSignature Language="C#" Value="public int ConnectionBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ConnectionBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ConnectionBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.ConnectionBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionBufferSize", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-106">クライアントまたはサービスからネットワークでシリアル化されたメッセージの一部を転送するために使用されるバッファーのサイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-106">Gets or sets the size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span></summary>
        <value><span data-ttu-id="41d01-107">返します、<see cref="T:System.Int32" />クライアントまたはサービスからネットワークでシリアル化されたメッセージの一部を転送するために使用するバッファーのサイズを格納します。</span><span class="sxs-lookup"><span data-stu-id="41d01-107">Returns a <see cref="T:System.Int32" /> that contains the size of the buffer used to transmit a part of the serialized message on the wire from the client or service.</span></span> <span data-ttu-id="41d01-108">既定値は、8 K です。</span><span class="sxs-lookup"><span data-stu-id="41d01-108">The default value is 8K.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="connectionOrientedTransportElement.CopyFrom from" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="from" Type="System.ServiceModel.Configuration.ServiceModelExtensionElement" />
      </Parameters>
      <Docs>
        <param name="from"><span data-ttu-id="41d01-109">コピーされる構成要素。</span><span class="sxs-lookup"><span data-stu-id="41d01-109">The configuration element to be copied.</span></span></param>
        <summary><span data-ttu-id="41d01-110">指定された構成要素の内容をこの構成要素にコピーします。</span><span class="sxs-lookup"><span data-stu-id="41d01-110">Copies the content of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("hostNameComparisonMode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-111">URI で一致する場合にサービスに到達するためにホスト名を使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-111">Gets or sets a value that indicates whether the hostname is used to reach the service when matching on the URI.</span></span></summary>
        <value><span data-ttu-id="41d01-112">受信要求をエンドポイント URI にルーティングするときに、ホスト名が含まれるかどうかを示す有効な HostnameComparisonMode 値です。</span><span class="sxs-lookup"><span data-stu-id="41d01-112">A valid HostnameComparisonMode value that indicates whether the hostname is included when routing incoming requests to an endpoint URI.</span></span> <span data-ttu-id="41d01-113">既定値は、StrongWildcard で、一致しているホスト名を無視します。</span><span class="sxs-lookup"><span data-stu-id="41d01-113">The default value is StrongWildcard, which ignores the hostname in the match.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="41d01-114">使用するバッファーの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-114">Gets or sets the maximum size of the buffer to use.</span></span></summary>
        <value><span data-ttu-id="41d01-115">メモリ内で入力メッセージのバッファーに使用される最大バイト数。</span><span class="sxs-lookup"><span data-stu-id="41d01-115">The maximum number of bytes that are used to buffer incoming messages in memory.</span></span> <span data-ttu-id="41d01-116">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="41d01-116">The default value is 65,536 bytes.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxOutputDelay">
      <MemberSignature Language="C#" Value="public TimeSpan MaxOutputDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan MaxOutputDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxOutputDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.MaxOutputDelay : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxOutputDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.TimeSpanOrInfiniteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxOutputDelay", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-117">メッセージの一部または完全なメッセージを、送信前にメモリ内のバッファーに残したままにできる最長期間を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-117">Gets or sets the maximum interval of time that a part of a message or a full message can remain buffered in memory before being sent out.</span></span></summary>
        <value><span data-ttu-id="41d01-118">最大間隔になる前にメモリにバッファーされるメッセージまたは完全なメッセージの一部を保持できる時間の送信。既定値は、2 秒です。</span><span class="sxs-lookup"><span data-stu-id="41d01-118">The maximum interval of time that a part of a message or a full message can remain buffered in memory before being sent out. The default value is 2 seconds.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingAccepts">
      <MemberSignature Language="C#" Value="public int MaxPendingAccepts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingAccepts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingAccepts As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingAccepts : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingAccepts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingAccepts", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-119">サービスでの着信接続処理に使用できる、保留中の非同期受け入れスレッドの最大数を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-119">Gets or sets the maximum number of pending asynchronous accept threads that are available for processing incoming connections on the service.</span></span></summary>
        <value><span data-ttu-id="41d01-120">サービスが許可する保留状態のメッセージの最大数。</span><span class="sxs-lookup"><span data-stu-id="41d01-120">The maximum number of pending messages the service can accept.</span></span> <span data-ttu-id="41d01-121">既定値は 1 です。</span><span class="sxs-lookup"><span data-stu-id="41d01-121">The default value is 1.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPendingConnections">
      <MemberSignature Language="C#" Value="public int MaxPendingConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxPendingConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPendingConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxPendingConnections : int with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.MaxPendingConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("maxPendingConnections", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.IntegerValidator(MinValue=1)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-122">保留する最大接続数を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-122">Gets or sets the maximum number of pending connections.</span></span></summary>
        <value><span data-ttu-id="41d01-123">保留状態の接続の最大数。</span><span class="sxs-lookup"><span data-stu-id="41d01-123">The maximum number of pending connections.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="41d01-124">属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納する ConfigurationPropertyCollection インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="41d01-124">Gets a ConfigurationPropertyCollection instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></summary>
        <value><span data-ttu-id="41d01-125">返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="41d01-125">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement.TransferMode" />
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
        <summary><span data-ttu-id="41d01-126">接続指向のトランスポートでメッセージをバッファーするか、ストリーム配信するかを指定する値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="41d01-126">Gets or sets a value that specifies whether the messages are buffered or streamed with the connection-oriented transport.</span></span></summary>
        <value><span data-ttu-id="41d01-127">有効な返します<see cref="T:System.ServiceModel.TransferMode" />チャネルを使用するかどうかを指定する値がストリームまたはバッファー内のメッセージ転送のモード。</span><span class="sxs-lookup"><span data-stu-id="41d01-127">Returns a valid <see cref="T:System.ServiceModel.TransferMode" /> value that specifies whether a channel uses streamed or buffered modes of message transfer.</span></span> <span data-ttu-id="41d01-128">既定値はバッファーです。</span><span class="sxs-lookup"><span data-stu-id="41d01-128">The default is Buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>