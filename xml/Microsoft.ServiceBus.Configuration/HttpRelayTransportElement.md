<Type Name="HttpRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement">
  <TypeSignature Language="C#" Value="public class HttpRelayTransportElement : System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HttpRelayTransportElement extends System.ServiceModel.Configuration.TransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public Class HttpRelayTransportElement&#xA;Inherits TransportElement" />
  <TypeSignature Language="F#" Value="type HttpRelayTransportElement = class&#xA;    inherit TransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Configuration.TransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="8ce19-101">SOAP メッセージ送信用 HTTP トランスポートを指定する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-101">Represents a configuration element that specifies an HTTP transport for transmitting SOAP messages.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="8ce19-102"><see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.AllowCookies" />
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
        <summary><span data-ttu-id="8ce19-103">取得またはクライアントが cookie を受け入れ、それらを今後の要求に反映させるかどうかを示す構成ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-103">Gets or sets a value from the configuration file that indicates whether the client accepts cookies and propagates them on future requests.</span></span></summary>
        <value><span data-ttu-id="8ce19-104">cookie を許可する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-104">true if cookies are allowed; otherwise, false.</span></span> <span data-ttu-id="8ce19-105">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-105">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="httpRelayTransportElement.ApplyConfiguration bindingElement" />
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
        <param name="bindingElement"> <span data-ttu-id="8ce19-106">設定を更新するバインド要素。</span><span class="sxs-lookup"><span data-stu-id="8ce19-106">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="8ce19-107">指定されたバインド要素をこの構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-107">Applies the settings of this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8ce19-108">バインディングの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-108">Gets the type of binding.</span></span> <span data-ttu-id="8ce19-109">(BindingElementExtensionElement.BindingElementType をオーバーライドします)。</span><span class="sxs-lookup"><span data-stu-id="8ce19-109">(Overrides BindingElementExtensionElement.BindingElementType.)</span></span></summary>
        <value><span data-ttu-id="8ce19-110">返します、<see cref="T:System.Type" />バインドの種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="8ce19-110">Returns a <see cref="T:System.Type" /> that contains the binding type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="httpRelayTransportElement.CopyFrom from" />
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
        <param name="from"> <span data-ttu-id="8ce19-111">拡張機能の要素をコピーするプロパティを持つ。</span><span class="sxs-lookup"><span data-stu-id="8ce19-111">The extension element whose properties to copy.</span></span></param>
        <summary><span data-ttu-id="8ce19-112">この構成要素に指定された拡張要素のプロパティをコピーします。</span><span class="sxs-lookup"><span data-stu-id="8ce19-112">Copies the properties of the specified extension element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="httpRelayTransportElement.CreateDefaultBindingElement " />
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
        <summary><span data-ttu-id="8ce19-113">この構成要素の設定からバインド要素を作成します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-113">Creates a binding element from the settings in this configuration element.</span></span></summary>
        <returns><span data-ttu-id="8ce19-114">返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />既定のバインド要素を格納しています。</span><span class="sxs-lookup"><span data-stu-id="8ce19-114">Returns a <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> that contains the default binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="httpRelayTransportElement.InitializeFrom bindingElement" />
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
        <param name="bindingElement"> <span data-ttu-id="8ce19-115">初期化するためにバインド要素。</span><span class="sxs-lookup"><span data-stu-id="8ce19-115">The binding element to initialize from.</span></span></param>
        <summary><span data-ttu-id="8ce19-116">このバインド構成要素を、指定されたバインド要素の内容で初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-116">Initializes this binding configuration element with the content of the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.IsDynamic" />
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
        <summary><span data-ttu-id="8ce19-117">取得またはリレー バインドが動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-117">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="8ce19-118">リレー バインドは、動的; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-118">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeepAliveEnabled">
      <MemberSignature Language="C#" Value="public bool KeepAliveEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool KeepAliveEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.KeepAliveEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property KeepAliveEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.KeepAliveEnabled : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.KeepAliveEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("keepAliveEnabled", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8ce19-119">取得またはインターネット リソースへ永続的な接続を作成するかどうかを示す構成ファイルからブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-119">Gets or sets a Boolean value from the configuration file that indicates whether to make a persistent connection to the internet resource.</span></span></summary>
        <value><span data-ttu-id="8ce19-120">インターネット リソースへ永続的な接続が維持される場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-120">true if a persistent connection to the internet resource is maintained; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.MaxBufferSize" />
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
        <summary><span data-ttu-id="8ce19-121">取得または構成ファイルからバッファー プールの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-121">Gets or sets the maximum size of the buffer pool from the configuration file.</span></span></summary>
        <value><span data-ttu-id="8ce19-122">バッファーの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-122">Returns the maximum buffer size.</span></span> <span data-ttu-id="8ce19-123">既定値は 65,536 です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-123">The default value is 65,536.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8ce19-124">取得、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="8ce19-124">Gets a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> instance that contains a collection of ConfigurationProperty objects that can be attributes or ConfigurationElement objects of this configuration element.</span></span> <span data-ttu-id="8ce19-125">(TransportElement.Properties をオーバーライドします)。</span><span class="sxs-lookup"><span data-stu-id="8ce19-125">(Overrides TransportElement.Properties.)</span></span></summary>
        <value><span data-ttu-id="8ce19-126">返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />現在のインスタンスのプロパティを格納します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-126">Returns a <see cref="T:System.Configuration.ConfigurationPropertyCollection" /> that contains the properties of the current instance.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.ProxyAddress" />
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
        <summary><span data-ttu-id="8ce19-127">取得または HTTP 要求に使用するプロキシのアドレスを格納する構成ファイルの URI を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-127">Gets or sets a URI in the configuration file that contains the address of the proxy to use for HTTP requests.</span></span></summary>
        <value><span data-ttu-id="8ce19-128">返します、 <see cref="T:System.Uri" /> URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-128">Returns a <see cref="T:System.Uri" /> that contains the URI.</span></span> <span data-ttu-id="8ce19-129">既定値は null です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-129">The default is null.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAuthenticationScheme">
      <MemberSignature Language="C#" Value="public System.Net.AuthenticationSchemes ProxyAuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.AuthenticationSchemes ProxyAuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.ProxyAuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAuthenticationScheme As AuthenticationSchemes" />
      <MemberSignature Language="F#" Value="member this.ProxyAuthenticationScheme : System.Net.AuthenticationSchemes with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.ProxyAuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyAuthenticationScheme", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.AuthenticationSchemes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8ce19-130">取得または HTTP プロキシによって処理されるクライアント要求の認証に使用する認証方式を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-130">Gets or sets the authentication scheme used to authenticate client requests that are processed by the HTTP proxy.</span></span></summary>
        <value><span data-ttu-id="8ce19-131">HTTP プロキシによって処理されるクライアント要求を認証するために使用する認証方式です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-131">The authentication scheme used to authenticate client requests that are processed by the HTTP proxy.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="8ce19-132">取得または構成ファイルに格納されているリレー クライアント認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-132">Gets or sets the relay client authentication type stored in the configuration file.</span></span></summary>
        <value><span data-ttu-id="8ce19-133"><see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-133">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.TransferMode" />
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
        <summary><span data-ttu-id="8ce19-134">取得またはメッセージをバッファリングまたは要求または応答のストリーム配信されるかどうかを指定する構成ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-134">Gets or sets a value from the configuration file that specifies whether messages are buffered or streamed on a request or response.</span></span></summary>
        <value><span data-ttu-id="8ce19-135">返します、<see cref="T:System.ServiceModel.TransferMode" />メッセージをバッファリングまたは要求または応答のストリーム配信されるかどうかを指定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-135">Returns a <see cref="T:System.ServiceModel.TransferMode" /> that specifies whether messages are buffered or streamed on a request or response.</span></span> <span data-ttu-id="8ce19-136">既定では、HTTP、TCP/IP、および名前付きパイプ トランスポートは、バッファー内のメッセージ転送を使用します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-136">By default, the HTTP, TCP/IP, and named pipe transports use buffered message transfers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportElement.UseDefaultWebProxy" />
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
        <summary><span data-ttu-id="8ce19-137">取得またはユーザー固有の設定ではなく、コンピューター全体のプロキシ設定が使用されるかどうかを示す構成ファイルから値を設定します。</span><span class="sxs-lookup"><span data-stu-id="8ce19-137">Gets or sets a value from the configuration file that indicates whether the machine-wide proxy settings are used rather than the user-specific settings.</span></span></summary>
        <value><span data-ttu-id="8ce19-138">System.Net の既定のプロキシ設定が使用される場合は trueそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-138">true if the System.Net default proxy settings are used; otherwise, false.</span></span> <span data-ttu-id="8ce19-139">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="8ce19-139">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>