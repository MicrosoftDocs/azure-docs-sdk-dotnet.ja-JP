<Type Name="NetTcpRelayBinding" FullName="Microsoft.ServiceBus.NetTcpRelayBinding">
  <TypeSignature Language="C#" Value="public class NetTcpRelayBinding : Microsoft.ServiceBus.NetTcpRelayBindingBase, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetTcpRelayBinding extends Microsoft.ServiceBus.NetTcpRelayBindingBase implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class NetTcpRelayBinding&#xA;Inherits NetTcpRelayBindingBase&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBinding = class&#xA;    inherit NetTcpRelayBindingBase&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.NetTcpRelayBindingBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="3b815-101">コンピューター間通信に適した、セキュリティで保護された、信頼性の高いバインドを提供します。</span><span class="sxs-lookup"><span data-stu-id="3b815-101">Provides a secure, reliable binding suitable for cross-computer communication.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3b815-102"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="3b815-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : string -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="3b815-103">使用する構成。</span><span class="sxs-lookup"><span data-stu-id="3b815-103">The configuration to use.</span></span></param>
        <summary><span data-ttu-id="3b815-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />指定された XML 構成を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3b815-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> class with a specified XML configuration.</span></span> </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="3b815-105">バインディングで使用されるセキュリティの種類。</span><span class="sxs-lookup"><span data-stu-id="3b815-105">The type of security used with the binding.</span></span> </param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="3b815-106">リレーで使用されるクライアント認証の種類。</span><span class="sxs-lookup"><span data-stu-id="3b815-106">The type of client authentication used on the relay.</span></span> </param>
        <summary><span data-ttu-id="3b815-107">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />クラスに使用されるセキュリティの種類とリレー クライアントの認証を指定します。</span><span class="sxs-lookup"><span data-stu-id="3b815-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> class with the type of security used and relay client authentication specified.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType, bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType * bool -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (securityMode, relayClientAuthenticationType, reliableSessionEnabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="securityMode"><span data-ttu-id="3b815-108">Azure Service Bus のバインドで使用されるセキュリティの種類。</span><span class="sxs-lookup"><span data-stu-id="3b815-108">The type of security used with the Azure Service Bus binding.</span></span></param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="3b815-109">リレーで使用されるクライアント認証の種類。</span><span class="sxs-lookup"><span data-stu-id="3b815-109">The type of client authentication used on the relay.</span></span> </param>
        <param name="reliableSessionEnabled"><span data-ttu-id="3b815-110">信頼できるセッションが有効な場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="3b815-110">true if reliable sessions are enabled; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="3b815-111">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />使用されるセキュリティの種類、クライアント認証の種類、および信頼できるセッションが明示的に有効にするかどうかを示す値を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3b815-111">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> class with the type of security used, the type of client authentication, and a value that indicates whether reliable sessions are explicitly enabled.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBinding (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session, Microsoft.ServiceBus.NetTcpRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session, class Microsoft.ServiceBus.NetTcpRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement,Microsoft.ServiceBus.NetTcpRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement, security As NetTcpRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBinding : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement * Microsoft.ServiceBus.NetTcpRelaySecurity -&gt; Microsoft.ServiceBus.NetTcpRelayBinding" Usage="new Microsoft.ServiceBus.NetTcpRelayBinding (transport, encoding, session, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetTcpRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport"><span data-ttu-id="3b815-112">使用するトランスポート バインド要素。</span><span class="sxs-lookup"><span data-stu-id="3b815-112">The transport binding element to use.</span></span></param>
        <param name="encoding"><span data-ttu-id="3b815-113">使用するエンコーディング。</span><span class="sxs-lookup"><span data-stu-id="3b815-113">The encoding to use.</span></span></param>
        <param name="session"><span data-ttu-id="3b815-114">信頼できるセッション バインド要素。</span><span class="sxs-lookup"><span data-stu-id="3b815-114">The reliable session binding element.</span></span></param>
        <param name="security"><span data-ttu-id="3b815-115">セキュリティ バインド要素。</span><span class="sxs-lookup"><span data-stu-id="3b815-115">The security binding element.</span></span></param>
        <summary>
            <span data-ttu-id="3b815-116">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />指定されたトランスポート、エンコーダー、信頼できるセッション バインド要素、および使用されるセキュリティの種類を持つクラス。</span><span class="sxs-lookup"><span data-stu-id="3b815-116">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> class with the given transport, encoder, reliable session binding element and type of security used.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : string -&gt; unit" Usage="netTcpRelayBinding.ApplyConfiguration configurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="3b815-117">設定を実行する構成要素の名前。</span><span class="sxs-lookup"><span data-stu-id="3b815-117">The name of the configuration element to take the settings from.</span></span></param>
        <summary><span data-ttu-id="3b815-118">このバインド要素の現在のインスタンスに指定した名前を対応する構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="3b815-118">Applies the settings from the configuration element that corresponds to the specified name to the current instance of this binding element.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netTcpRelayBinding.CreateBindingElements " />
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
        <summary><span data-ttu-id="3b815-119">バインド用のバインド要素でコレクションを作成します。</span><span class="sxs-lookup"><span data-stu-id="3b815-119">Creates a collection with the binding elements for the binding.</span></span> </summary>
        <returns><span data-ttu-id="3b815-120">返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />バインド要素の順序付けられたスタックを格納しています。</span><span class="sxs-lookup"><span data-stu-id="3b815-120">Returns a <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> that contains the ordered stack of binding elements.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected internal override System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overrides Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="override this.CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="netTcpRelayBinding.CreateMessageSecurity " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.SecurityBindingElement</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="3b815-121">現在のインスタンスのメッセージのセキュリティ トークンを作成します。</span><span class="sxs-lookup"><span data-stu-id="3b815-121">Creates the message security token for the current instance.</span></span> </summary>
        <returns><span data-ttu-id="3b815-122">返します<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />です。メッセージのセキュリティ トークンが含まれています。</span><span class="sxs-lookup"><span data-stu-id="3b815-122">Returns <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />.Contains the message security token.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBinding.IsBindingElementsMatch(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBindingElementsMatch : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement -&gt; bool" Usage="netTcpRelayBinding.IsBindingElementsMatch (transport, encoding, session)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
      </Parameters>
      <Docs>
        <param name="transport"> <span data-ttu-id="3b815-123">一致するようにトランスポート。</span><span class="sxs-lookup"><span data-stu-id="3b815-123">The transport to match.</span></span> </param>
        <param name="encoding"> <span data-ttu-id="3b815-124">一致するようにエンコードします。</span><span class="sxs-lookup"><span data-stu-id="3b815-124">The encoding to match.</span></span> </param>
        <param name="session"> <span data-ttu-id="3b815-125">一致するセッションです。</span><span class="sxs-lookup"><span data-stu-id="3b815-125">The session to match.</span></span> </param>
        <summary><span data-ttu-id="3b815-126">指定したオブジェクトが一致するバインド要素を持つかどうかを決定する値を返します。</span><span class="sxs-lookup"><span data-stu-id="3b815-126">Returns a value that determines whether the specified objects have matching binding elements.</span></span> </summary>
        <returns><span data-ttu-id="3b815-127">返します<see cref="T:System.Boolean" />.true オブジェクトが一致する場合は、それ以外の場合は false。</span><span class="sxs-lookup"><span data-stu-id="3b815-127">Returns<see cref="T:System.Boolean" />.true if the objects match; otherwise, false.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.OptionalReliableSession ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.OptionalReliableSession ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBinding.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As OptionalReliableSession" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.OptionalReliableSession" Usage="Microsoft.ServiceBus.NetTcpRelayBinding.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.OptionalReliableSession</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3b815-128">Azure サービス バスのチャネルのエンドポイント間に信頼できるセッションを確立するかどうかを示すオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="3b815-128">Gets an object that indicates whether a reliable session is established between Azure Service Bus channel endpoints.</span></span> </summary>
        <value><span data-ttu-id="3b815-129">返します<see cref="T:System.ServiceModel.OptionalReliableSession" />です。チャネルのエンドポイント間に WS-RM 信頼できるセッションが確立するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="3b815-129">Returns <see cref="T:System.ServiceModel.OptionalReliableSession" />.Indicates whether a WS-RM reliable session is established between channel endpoints.</span></span> <span data-ttu-id="3b815-130">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="3b815-130">The default is false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>