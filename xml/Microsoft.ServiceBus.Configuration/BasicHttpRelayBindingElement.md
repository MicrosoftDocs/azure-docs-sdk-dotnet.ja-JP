<Type Name="BasicHttpRelayBindingElement" FullName="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement">
  <TypeSignature Language="C#" Value="public class BasicHttpRelayBindingElement : System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BasicHttpRelayBindingElement extends System.ServiceModel.Configuration.StandardBindingElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" />
  <TypeSignature Language="VB.NET" Value="Public Class BasicHttpRelayBindingElement&#xA;Inherits StandardBindingElement" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayBindingElement = class&#xA;    inherit StandardBindingElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.StandardBindingElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="5e4b2-101">WS との通信に使用されるバインディングを指定する構成要素を表す-基本プロファイル 1.1 に適合する Web サービス ASMX ベースのサービスと同様に、または Azure Service Bus を通じて ASMX ベースのクライアントからのメッセージを受け入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-101">Represents a configuration element that specifies a binding used to communicate with WS-I Basic Profile 1.1-conformant Web Services like ASMX-based services or to accept messages from ASMX-based clients through the Azure Service Bus.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="5e4b2-102"><see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelayBindingElement (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement : string -&gt; Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" Usage="new Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5e4b2-103">バインド要素の名前。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-103">The name of the binding element.</span></span></param>
        <summary><span data-ttu-id="5e4b2-104">指定された名前を使用して、<see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement" /> class using the specified name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.AllowCookies" />
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
        <summary><span data-ttu-id="5e4b2-105">取得またはクライアントが cookie を受け入れ、それらを今後の要求に反映させるかどうかを示すブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-105">Gets or sets a Boolean value that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="5e4b2-106">クライアントが cookie を受け入れ、それらを今後の要求に反映させる場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-106">true if the client accepts cookies and propagates them on future requests; otherwise, false.</span></span> <span data-ttu-id="5e4b2-107">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-107">The default value is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="protected override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5e4b2-108">このバインド要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-108">Gets the type of this binding element.</span></span></summary>
        <value><span data-ttu-id="5e4b2-109">返します、<see cref="T:System.Type" />バインディング要素の型を格納しています。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-109">Returns a <see cref="T:System.Type" /> that contains the binding element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.InitializeFrom(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.Binding -&gt; unit" Usage="basicHttpRelayBindingElement.InitializeFrom binding" />
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
        <param name="binding"><span data-ttu-id="5e4b2-110">初期化するためにバインドします。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-110">The Binding to initialize from.</span></span></param>
        <summary><span data-ttu-id="5e4b2-111">このバインド構成要素を指定されたバインディング コレクションの内容で初期化します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-111">Initializes this binding configuration element with the content of the specified binding collection.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.IsDynamic" />
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
        <summary><span data-ttu-id="5e4b2-112">取得またはバインド要素が動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-112">Gets or sets whether the binding element is dynamic.</span></span></summary>
        <value><span data-ttu-id="5e4b2-113">バインド要素が動的; 場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-113">true if the binding element is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferPoolSize" />
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
        <summary><span data-ttu-id="5e4b2-114">バインディングによって処理されるメッセージを保存するバッファー プールの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-114">Gets or sets the maximum size for a buffer pool that stores messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-115">返します、<see cref="T:System.Int64" />バッファー プール サイズを格納しています。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-115">Returns an <see cref="T:System.Int64" /> that contains the buffer pool size.</span></span> <span data-ttu-id="5e4b2-116">既定値は 512\*1024 バイトです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-116">The default value is 512\*1024 bytes.</span></span> <span data-ttu-id="5e4b2-117">最小値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-117">The minimum value is 0.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="5e4b2-118">取得または設定がこのバインディングで構成されたエンドポイントに対して処理されるときにメッセージを格納するバッファーの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-118">Gets or sets the maximum size of a buffer that stores messages while they are processed for an endpoint configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-119">バッファーの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-119">Returns the maximum buffer size.</span></span> <span data-ttu-id="5e4b2-120">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-120">The default value is 65,536 bytes.</span></span> <span data-ttu-id="5e4b2-121">最小値は、1 バイトです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-121">The minimum value is 1 byte.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MaxReceivedMessageSize" />
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
        <summary><span data-ttu-id="5e4b2-122">取得または (バイト単位) をこのバインディングで構成されるチャネルで受信可能なメッセージのヘッダーを含む最大メッセージ サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-122">Gets or sets the maximum message size, in bytes, including headers, for a message that can be received on a channel configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-123">受信したメッセージの最大サイズ。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-123">The maximum received message size.</span></span> <span data-ttu-id="5e4b2-124">既定値は 65,536 バイトです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-124">The default value is 65,536 bytes.</span></span> <span data-ttu-id="5e4b2-125">最小値は、1 バイトです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-125">The minimum value is 1 byte.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.MessageEncoding" />
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
        <summary><span data-ttu-id="5e4b2-126">取得または設定、メッセージを SOAP メッセージのエンコードに MTOM または TEXT/XML が使用されるかどうかを示すをエンコードします。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-126">Gets or sets the messaging encoding that indicates whether MTOM or text/XML is used to encode the SOAP message.</span></span></summary>
        <value><span data-ttu-id="5e4b2-127">返します、<see cref="T:System.ServiceModel.WSMessageEncoding" />テキスト/XML または MTOM のいずれかを格納しています。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-127">Returns a <see cref="T:System.ServiceModel.WSMessageEncoding" /> that contains either Text/XML or MTOM.</span></span> <span data-ttu-id="5e4b2-128">既定値はテキストです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-128">The default value is Text.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void OnApplyConfiguration (System.ServiceModel.Channels.Binding binding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnApplyConfiguration(class System.ServiceModel.Channels.Binding binding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.OnApplyConfiguration(System.ServiceModel.Channels.Binding)" />
      <MemberSignature Language="F#" Value="override this.OnApplyConfiguration : System.ServiceModel.Channels.Binding -&gt; unit" Usage="basicHttpRelayBindingElement.OnApplyConfiguration binding" />
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
        <param name="binding"><span data-ttu-id="5e4b2-129">この構成を適用するバインディング。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-129">The Binding to apply this configuration to.</span></span></param>
        <summary><span data-ttu-id="5e4b2-130">指定されたバインディングには、この構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-130">Applies the settings of this configuration element to the specified binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5e4b2-131">属性を保持できるオブジェクト、またはこのバインディング構成要素の構成要素オブジェクトのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-131">Gets a collection of objects that can be attributes or configuration element objects of this binding configuration element.</span></span></summary>
        <value><span data-ttu-id="5e4b2-132">返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />現在のインスタンスのプロパティを格納します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-132">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains the properties of the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ProxyAddress" />
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
        <summary><span data-ttu-id="5e4b2-133">取得または HTTP プロキシのアドレスを記述する URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-133">Gets or sets the URI that describes the address of the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="5e4b2-134">返します、 <see cref="T:System.Uri" /> URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-134">Returns a <see cref="T:System.Uri" /> that contains the URI.</span></span> <span data-ttu-id="5e4b2-135">既定値は null です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-135">The default is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReaderQuotas As XmlDictionaryReaderQuotasElement" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.ReaderQuotas" />
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
        <summary><span data-ttu-id="5e4b2-136">取得または、このバインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を配置する XML 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-136">Gets or sets an XML value that places constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-137">返します、<see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" />リーダーのクォータを格納しています。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-137">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.XmlDictionaryReaderQuotasElement" /> that contains the reader quotas.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As BasicHttpRelaySecurityElement" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.Security" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="5e4b2-138">バインディングに使用されるセキュリティの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-138">Gets the type of security to be used for the binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-139">返します、<see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" />バインディングで使用されるセキュリティの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-139">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" /> that specifies the type of security to be used with the binding.</span></span> <span data-ttu-id="5e4b2-140">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-140">The default value is None.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TextEncoding" />
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
        <summary><span data-ttu-id="5e4b2-141">バインディングでメッセージの発行に使用される文字セット エンコーディングを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-141">Gets or sets the character set encoding to be used for emitting messages on the binding.</span></span></summary>
        <value><span data-ttu-id="5e4b2-142">返します、<see cref="T:System.Text.Encoding" />テキスト エンコードを含むです。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-142">Returns a <see cref="T:System.Text.Encoding" /> that contains the text encoding.</span></span> <span data-ttu-id="5e4b2-143">既定値は UTF8 です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-143">The default value is UTF8.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.TransferMode" />
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
        <summary><span data-ttu-id="5e4b2-144">取得またはメッセージをバッファリングまたはストリーム要求または応答であるかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-144">Gets or sets whether messages are buffered or streamed on a request or response.</span></span></summary>
        <value><span data-ttu-id="5e4b2-145">返します、<see cref="T:System.ServiceModel.TransferMode" />転送モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-145">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that contains the transfer mode.</span></span> <span data-ttu-id="5e4b2-146">既定値は、transfermode.buffered の場合です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-146">The default value is TransferMode.Buffered.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelayBindingElement.UseDefaultWebProxy" />
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
        <summary><span data-ttu-id="5e4b2-147">使用できる場合にシステムの自動構成される HTTP プロキシを使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-147">Gets or sets a value that indicates whether the auto-configured HTTP proxy of the system should be used, if available.</span></span></summary>
        <value><span data-ttu-id="5e4b2-148">http プロキシを使用する場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-148">true to use the http proxy; otherwise, false.</span></span> <span data-ttu-id="5e4b2-149">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="5e4b2-149">The default value is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>