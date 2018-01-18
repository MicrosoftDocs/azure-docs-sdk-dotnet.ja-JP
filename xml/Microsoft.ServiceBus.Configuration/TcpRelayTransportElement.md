<Type Name="TcpRelayTransportElement" FullName="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement">
  <TypeSignature Language="C#" Value="public sealed class TcpRelayTransportElement : Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TcpRelayTransportElement extends Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TcpRelayTransportElement&#xA;Inherits ConnectionOrientedTransportElement" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportElement = class&#xA;    inherit ConnectionOrientedTransportElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Configuration.ConnectionOrientedTransportElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="1dcf8-101">チャネルがカスタム バインドに含まれているときに TCP トランスポートでメッセージを転送する構成要素を指定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-101">Specifies a configuration element that causes a channel to transfer messages on the TCP transport when it is included in a custom binding.</span></span> <span data-ttu-id="1dcf8-102">このクラスは継承できません。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="1dcf8-103"><see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-103">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="public override void ApplyConfiguration (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyConfiguration(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ApplyConfiguration(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.ApplyConfiguration bindingElement" />
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
        <param name="bindingElement"> <span data-ttu-id="1dcf8-104">設定を更新するバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-104">The binding element to update the settings of.</span></span></param>
        <summary><span data-ttu-id="1dcf8-105">指定されたバインド要素をこの構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-105">Applies the settings of this configuration element to the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BindingElementType">
      <MemberSignature Language="C#" Value="public override Type BindingElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type BindingElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property BindingElementType As Type" />
      <MemberSignature Language="F#" Value="member this.BindingElementType : Type" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.BindingElementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1dcf8-106">このバインド要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-106">Gets the type of this binding element.</span></span></summary>
        <value><span data-ttu-id="1dcf8-107">返します、<see cref="T:System.Type" />バインディング要素の型を格納します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-107">Returns a <see cref="T:System.Type" /> containing a binding element type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionMode" />
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
        <summary><span data-ttu-id="1dcf8-108">取得または、この構成用の App.config ファイルに格納されている接続モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-108">Gets or sets the connection mode stored in the App.config file for this configuration.</span></span></summary>
        <value><span data-ttu-id="1dcf8-109">返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />接続モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-109">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode.</span></span> <span data-ttu-id="1dcf8-110">既定の設定を転送します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-110">The default setting is Relayed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPoolSettings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement ConnectionPoolSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionPoolSettings As SocketConnectionPoolSettingsElement" />
      <MemberSignature Language="F#" Value="member this.ConnectionPoolSettings : Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ConnectionPoolSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("connectionPoolSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="1dcf8-111">取得または現在のインスタンスの接続プール設定を記述する XML 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-111">Gets or sets an XML value that describes the connection pool settings for the current instance.</span></span></summary>
        <value><span data-ttu-id="1dcf8-112">返します、<see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" />に現在のインスタンスを適用するバインド要素によって使用される接続プールの設定を格納しています。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-112">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.SocketConnectionPoolSettingsElement" /> that contains the connection pool settings used by the binding element that the current instance is applied to.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyFrom">
      <MemberSignature Language="C#" Value="public override void CopyFrom (System.ServiceModel.Configuration.ServiceModelExtensionElement from);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void CopyFrom(class System.ServiceModel.Configuration.ServiceModelExtensionElement from) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CopyFrom(System.ServiceModel.Configuration.ServiceModelExtensionElement)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub CopyFrom (from As ServiceModelExtensionElement)" />
      <MemberSignature Language="F#" Value="override this.CopyFrom : System.ServiceModel.Configuration.ServiceModelExtensionElement -&gt; unit" Usage="tcpRelayTransportElement.CopyFrom from" />
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
        <param name="from"> <span data-ttu-id="1dcf8-113">コピーする構成要素。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-113">The configuration elements to be copied.</span></span></param>
        <summary><span data-ttu-id="1dcf8-114">指定された構成要素の内容をこの構成要素にコピーします。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-114">Copies the content of the specified configuration element to this configuration element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefaultBindingElement">
      <MemberSignature Language="C#" Value="protected override System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.ServiceModel.Channels.TransportBindingElement CreateDefaultBindingElement() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.CreateDefaultBindingElement" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateDefaultBindingElement () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateDefaultBindingElement : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="tcpRelayTransportElement.CreateDefaultBindingElement " />
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
        <summary><span data-ttu-id="1dcf8-115">この構成要素の設定からバインド要素を作成します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-115">Creates a binding element from the settings in this configuration element.</span></span></summary>
        <returns><span data-ttu-id="1dcf8-116">返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />既定のバインド要素を格納しています。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-116">Returns a <see cref="T:System.ServiceModel.Channels.TransportBindingElement" /> that contains the default binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeFrom">
      <MemberSignature Language="C#" Value="protected override void InitializeFrom (System.ServiceModel.Channels.BindingElement bindingElement);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void InitializeFrom(class System.ServiceModel.Channels.BindingElement bindingElement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.InitializeFrom(System.ServiceModel.Channels.BindingElement)" />
      <MemberSignature Language="F#" Value="override this.InitializeFrom : System.ServiceModel.Channels.BindingElement -&gt; unit" Usage="tcpRelayTransportElement.InitializeFrom bindingElement" />
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
        <param name="bindingElement"><span data-ttu-id="1dcf8-117">初期化するためにバインド要素。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-117">The binding element to initialize from.</span></span></param>
        <summary><span data-ttu-id="1dcf8-118">このバインド構成要素を、指定されたバインド要素の内容で初期化します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-118">Initializes this binding configuration element with the content of the specified binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.IsDynamic" />
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
        <summary><span data-ttu-id="1dcf8-119">取得またはリレー バインドが動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-119">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="1dcf8-120">リレー バインドは、動的; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-120">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.ListenBacklog" />
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
        <summary><span data-ttu-id="1dcf8-121">取得または保留可能なキューに置かれた接続要求の最大数を表す XML 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-121">Gets or sets an XML value containing the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="1dcf8-122">保留可能なキュー内の接続要求の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-122">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="1dcf8-123">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-123">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dcf8-124">プロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-124">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportElement.RelayClientAuthenticationType" />
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
        <summary><span data-ttu-id="1dcf8-125">取得またはリレー クライアントの認証の種類を表す XML 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-125">Gets or sets an XML value that contains the relay client authentication type.</span></span></summary>
        <value><span data-ttu-id="1dcf8-126">返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-126">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span> <span data-ttu-id="1dcf8-127">既定値は、RelayClientAuthenticationType.RelayAccessToken です。</span><span class="sxs-lookup"><span data-stu-id="1dcf8-127">The default is RelayClientAuthenticationType.RelayAccessToken.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>