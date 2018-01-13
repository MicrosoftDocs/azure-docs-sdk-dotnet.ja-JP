<Type Name="NetTcpRelayBindingBase" FullName="Microsoft.ServiceBus.NetTcpRelayBindingBase">
  <TypeSignature Language="C#" Value="public abstract class NetTcpRelayBindingBase : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NetTcpRelayBindingBase extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NetTcpRelayBindingBase&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetTcpRelayBindingBase = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ServiceModel.Channels.Binding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary><span data-ttu-id="dc29b-101">一般的な方法の基本クラス、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />バインドします。</span><span class="sxs-lookup"><span data-stu-id="dc29b-101">The base class for common methods for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> binding.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="dc29b-102"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-102">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : string -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName"><span data-ttu-id="dc29b-103">バインド構成の名前。</span><span class="sxs-lookup"><span data-stu-id="dc29b-103">The binding configuration name.</span></span></param>
        <summary><span data-ttu-id="dc29b-104">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定された構成名を使用します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> class, using the specified configuration name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase (securityMode, relayClientAuthenticationType)" />
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
        <param name="securityMode"><span data-ttu-id="dc29b-105">バインディングで使用されるセキュリティの種類。</span><span class="sxs-lookup"><span data-stu-id="dc29b-105">The type of security used with the binding.</span></span></param>
        <param name="relayClientAuthenticationType"><span data-ttu-id="dc29b-106">使用するリレー認証の種類。</span><span class="sxs-lookup"><span data-stu-id="dc29b-106">The type of relay authentication used.</span></span></param>
        <summary><span data-ttu-id="dc29b-107">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定したセキュリティ モードとリレー認証の種類を使用します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-107">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> class, using the specified security mode and relay authentication type.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetTcpRelayBindingBase (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, Microsoft.ServiceBus.NetTcpRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class Microsoft.ServiceBus.NetTcpRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.#ctor(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,Microsoft.ServiceBus.NetTcpRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, security As NetTcpRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetTcpRelayBindingBase : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * Microsoft.ServiceBus.NetTcpRelaySecurity -&gt; Microsoft.ServiceBus.NetTcpRelayBindingBase" Usage="new Microsoft.ServiceBus.NetTcpRelayBindingBase (transport, encoding, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.TcpRelayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetTcpRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport"> <span data-ttu-id="dc29b-108">トランスポート。</span><span class="sxs-lookup"><span data-stu-id="dc29b-108">The transport.</span></span></param>
        <param name="encoding"> <span data-ttu-id="dc29b-109">エンコーディング。</span><span class="sxs-lookup"><span data-stu-id="dc29b-109">The encoding.</span></span></param>
        <param name="security"> <span data-ttu-id="dc29b-110">セキュリティ。</span><span class="sxs-lookup"><span data-stu-id="dc29b-110">The security.</span></span></param>
        <summary><span data-ttu-id="dc29b-111">新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定されたトランスポート、エンコーディング、およびセキュリティを使用します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-111">Initializes a new instance of the<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> class, using the specified transport, encoding, and security.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected virtual void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="abstract member ApplyConfiguration : string -&gt; unit&#xA;override this.ApplyConfiguration : string -&gt; unit" Usage="netTcpRelayBindingBase.ApplyConfiguration configurationName" />
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
        <param name="configurationName"><span data-ttu-id="dc29b-112">設定を実行する構成要素の名前。</span><span class="sxs-lookup"><span data-stu-id="dc29b-112">The name of the configuration element to take the settings from.</span></span></param>
        <summary><span data-ttu-id="dc29b-113">このバインド要素の現在のインスタンスに指定した名前を対応する構成要素の設定を適用します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-113">Applies the settings from the configuration element that corresponds to the specified name to the current instance of this binding element.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException"><span data-ttu-id="dc29b-114">入力構成の名前、構成で指定されたバインド要素を見つけることができませんでした。</span><span class="sxs-lookup"><span data-stu-id="dc29b-114">Did not find the binding element specified by the input configuration name in the configuration.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ConnectionMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.TcpRelayConnectionMode ConnectionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ConnectionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionMode As TcpRelayConnectionMode" />
      <MemberSignature Language="F#" Value="member this.ConnectionMode : Microsoft.ServiceBus.TcpRelayConnectionMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ConnectionMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-115">接続モード取得または設定します。<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />または<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-115">Gets or sets the connection mode: <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" /> or <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />.</span></span></summary>
        <value><span data-ttu-id="dc29b-116">返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />接続を格納しているモードです。 いずれかの<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />または<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-116">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" /> that contains the connection mode; either <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" /> or <see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />.</span></span> <span data-ttu-id="dc29b-117">既定値は中継されます。</span><span class="sxs-lookup"><span data-stu-id="dc29b-117">The default is Relayed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netTcpRelayBindingBase.CreateBindingElements " />
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
        <summary><span data-ttu-id="dc29b-118">現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-118">Retrieves an ordered collection of binding elements contained in the current binding.</span></span></summary>
        <returns><span data-ttu-id="dc29b-119">返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />バインディングを構成します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-119">Returns a <see cref="T:System.ServiceModel.Channels.BindingElementCollection" /> that makes up the binding.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected internal abstract System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected Friend MustOverride Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="netTcpRelayBindingBase.CreateMessageSecurity " />
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
        <summary><span data-ttu-id="dc29b-120">現在のインスタンスのセキュリティ バインド要素を作成します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-120">Creates the security binding element for the current instance.</span></span></summary>
        <returns><span data-ttu-id="dc29b-121">返します、<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />セキュリティ バインド要素を格納しています。</span><span class="sxs-lookup"><span data-stu-id="dc29b-121">Returns a <see cref="T:System.ServiceModel.Channels.SecurityBindingElement" /> that contains the security binding element.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="encoding">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetTcpRelayBindingBase.encoding" />
      <MemberSignature Language="VB.NET" Value="Protected Friend encoding As BinaryMessageEncodingBindingElement " />
      <MemberSignature Language="F#" Value="val mutable encoding : System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.encoding" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BinaryMessageEncodingBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-122">現在のインスタンスのエンコード要素。セキュリティとトランスポートの設定と共に、エンコーディング バインディングの次の 3 つの主要プロパティを形成します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-122">The encoding element for the current instance.Along with the security and transport settings, the encoding forms the three core properties of a binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-123">このバインディングによって処理されるメッセージで使用される SOAP のバージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-123">Gets the version of SOAP that is used for messages processed by this binding.</span></span></summary>
        <value><span data-ttu-id="dc29b-124">返します、<see cref="T:System.ServiceModel.EnvelopeVersion" />このバインドで使用されるエンベロープ バージョンを格納しています。</span><span class="sxs-lookup"><span data-stu-id="dc29b-124">Returns a <see cref="T:System.ServiceModel.EnvelopeVersion" /> that contains the envelope version used for this binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-125">取得または使用するホスト名比較モードを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-125">Gets or sets the comparison mode used on the hostname.</span></span></summary>
        <value><span data-ttu-id="dc29b-126">使用するホスト名比較モード。</span><span class="sxs-lookup"><span data-stu-id="dc29b-126">The comparison mode used on the hostname.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetTcpRelayBindingBase.IsBindingElementsMatch(Microsoft.ServiceBus.TcpRelayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As TcpRelayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBindingElementsMatch : Microsoft.ServiceBus.TcpRelayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement -&gt; bool" Usage="netTcpRelayBindingBase.IsBindingElementsMatch (transport, encoding)" />
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
      </Parameters>
      <Docs>
        <param name="transport"> <span data-ttu-id="dc29b-127">トランスポート バインド要素。</span><span class="sxs-lookup"><span data-stu-id="dc29b-127">The transport binding element.</span></span></param>
        <param name="encoding"> <span data-ttu-id="dc29b-128">エンコーディング バインド要素。</span><span class="sxs-lookup"><span data-stu-id="dc29b-128">The encoding binding element.</span></span></param>
        <summary><span data-ttu-id="dc29b-129">指定されたバインド要素が、現在のインスタンス内のバインド要素の既定値に一致するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-129">Determines whether the specified binding elements match the default values of the binding elements in the current instance.</span></span></summary>
        <returns><span data-ttu-id="dc29b-130">要素が一致する場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-130">true if the elements match; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-131">取得またはリレー バインドが動的かどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-131">Gets or sets whether the relay binding is dynamic.</span></span></summary>
        <value><span data-ttu-id="dc29b-132">リレー バインドは、動的; 場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-132">true if the relay binding is dynamic; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-133">保留可能なキュー内の接続要求の最大数を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-133">Gets or sets the maximum number of queued connection requests that can be pending.</span></span></summary>
        <value><span data-ttu-id="dc29b-134">保留可能なキュー内の接続要求の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-134">Returns the maximum number of queued connection requests that can be pending.</span></span> <span data-ttu-id="dc29b-135">既定値は 10 です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-135">The default is 10.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-136">取得または、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-136">Gets or sets the maximum size allowed for a buffer pool that stores messages processed by the binding.</span></span></summary>
        <value><span data-ttu-id="dc29b-137">(バイト単位)、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-137">Returns the maximum size, in bytes, allowed for a buffer pool that stores messages processed by the binding.</span></span> <span data-ttu-id="dc29b-138">既定値は 65,536 です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-138">The default value is 65,536.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-139">取得またはメモリにメッセージを格納するために使用するバッファーの最大サイズを指定する値を設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-139">Gets or sets a value that specifies the maximum size of the buffer used to store messages in memory.</span></span></summary>
        <value><span data-ttu-id="dc29b-140">(バイト単位) をメモリにメッセージを保存するために使用するバッファーの最大サイズを返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-140">Returns the maximum size, in bytes, of the buffer used to store messages in memory.</span></span> <span data-ttu-id="dc29b-141">既定値は 65,536 です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-141">The default value is 65,536.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-142">クライアント上で後で再使用するためにプールできる接続の最大数と、サーバー上でディスパッチを保留できる接続の最大数を制御する値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-142">Gets or sets a value that controls the maximum number of connections to be pooled for subsequent reuse on the client and the maximum number of connections allowed to be pending dispatch on the server.</span></span></summary>
        <value><span data-ttu-id="dc29b-143">クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-143">On the client, returns the maximum number of connections to be pooled for subsequent reuse; on the server, returns the maximum number of connections allowed to be pending dispatch.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-144">このバインドで処理される受信メッセージの最大サイズを取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-144">Gets or sets the maximum size for a received message that is processed by the binding.</span></span></summary>
        <value><span data-ttu-id="dc29b-145">バインディングによって処理される受信メッセージのバイト単位で最大のサイズを返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-145">Returns the maximum size, in bytes, for a received message that is processed by the binding.</span></span> <span data-ttu-id="dc29b-146">既定値は 65,536 です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-146">The default value is 65,536.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSecurityVersion">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.MessageSecurityVersion MessageSecurityVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.MessageSecurityVersion MessageSecurityVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.MessageSecurityVersion" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property MessageSecurityVersion As MessageSecurityVersion" />
      <MemberSignature Language="F#" Value="member this.MessageSecurityVersion : System.ServiceModel.MessageSecurityVersion" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.MessageSecurityVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageSecurityVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-147">メッセージ セキュリティ バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-147">Gets the message security version.</span></span></summary>
        <value><span data-ttu-id="dc29b-148">返します、<see cref="T:System.ServiceModel.MessageSecurityVersion" />メッセージ セキュリティ バージョンを格納しています。</span><span class="sxs-lookup"><span data-stu-id="dc29b-148">Returns a <see cref="T:System.ServiceModel.MessageSecurityVersion" /> that contains the message security version.</span></span> <span data-ttu-id="dc29b-149">これは現在常に返されます MessageSecurityVersion..:: です。Wssecurity11wstrustfebruary2005wssecureconversationfebruary2005wssecuritypolicy11 でします。</span><span class="sxs-lookup"><span data-stu-id="dc29b-149">This currently always returns MessageSecurityVersion..::.WSSecurity11WSTrustFebruary2005WSSecureConversationFebruary2005WSSecurityPolicy11.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-150">このバインディングを使用して設定されるエンドポイントにより処理可能な、SOAP メッセージの複雑さに対する制約を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-150">Gets or sets constraints on the complexity of SOAP messages that can be processed by endpoints configured with this binding.</span></span> <span data-ttu-id="dc29b-151">このプロパティを null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="dc29b-151">This property cannot be null.</span></span></summary>
        <value><span data-ttu-id="dc29b-152">返します、<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />交換される soap メッセージに対する複雑さの制約を指定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-152">Returns a <see cref="T:System.Xml.XmlDictionaryReaderQuotas" /> that specifies the complexity constraints on soap messages exchanged.</span></span> <span data-ttu-id="dc29b-153">これらの制約の既定値については、後の「解説」で説明します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-153">The default values for these constraints are provided in the following Remarks section.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> <span data-ttu-id="dc29b-154">ある ReaderQuotas が null の場合</span><span class="sxs-lookup"><span data-stu-id="dc29b-154">if ReaderQuotas is null</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-155">トランスポートの URI スキームを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-155">Gets the URI scheme for the transport.</span></span></summary>
        <value><span data-ttu-id="dc29b-156">トランスポートの URI スキームを返します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-156">Returns the URI scheme for the transport.</span></span> <span data-ttu-id="dc29b-157">既定値は、"sb"です。</span><span class="sxs-lookup"><span data-stu-id="dc29b-157">The default is “sb”.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NetTcpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NetTcpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetTcpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.NetTcpRelaySecurity" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NetTcpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-158">この要素を使用して構成されたサービスで使用されるセキュリティの種類を指定するオブジェクトを取得します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-158">Gets an object that specifies the type of security used with services configured with this binding.</span></span></summary>
        <value><span data-ttu-id="dc29b-159">返します<see cref="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />、このバインディングで使用されるセキュリティの種類が含まれています。</span><span class="sxs-lookup"><span data-stu-id="dc29b-159">Returns <see cref="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />, which contains the types of security used with this binding.</span></span> <span data-ttu-id="dc29b-160">セキュリティの既定のモードは、トランスポートです。</span><span class="sxs-lookup"><span data-stu-id="dc29b-160">The default mode of security is Transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dc29b-161">受信要求が非同期的に処理されることを示します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-161">Indicates that incoming requests are handled asynchronously.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransferMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.TransferMode TransferMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.TransferMode TransferMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelayBindingBase.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-162">このバインディングを使用して構成されたサービスが、メッセージ転送のストリーミング モードまたはバッファー モード (あるいは両方のモード) を使用するかどうかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-162">Gets or sets a value that indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span></summary>
        <value><span data-ttu-id="dc29b-163">返します、<see cref="T:System.ServiceModel.TransferMode" />ストリームまたはバッファー内のバインドを使用して (または両方) でサービスが構成されているかどうかを示すメッセージ転送のモード。</span><span class="sxs-lookup"><span data-stu-id="dc29b-163">Returns a <see cref="T:System.ServiceModel.TransferMode" />  that indicates whether the service configured with the binding uses streamed or buffered (or both) modes of message transfer.</span></span> <span data-ttu-id="dc29b-164">既定では、HTTP、TCP/IP、および名前付きパイプ トランスポートは、バッファー内のメッセージ転送を使用します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-164">By default, the HTTP, TCP/IP, and named pipe transports use buffered message transfers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="transport">
      <MemberSignature Language="C#" Value="protected internal Microsoft.ServiceBus.TcpRelayTransportBindingElement transport;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class Microsoft.ServiceBus.TcpRelayTransportBindingElement transport" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetTcpRelayBindingBase.transport" />
      <MemberSignature Language="VB.NET" Value="Protected Friend transport As TcpRelayTransportBindingElement " />
      <MemberSignature Language="F#" Value="val mutable transport : Microsoft.ServiceBus.TcpRelayTransportBindingElement" Usage="Microsoft.ServiceBus.NetTcpRelayBindingBase.transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayTransportBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dc29b-165">現在のインスタンスのトランスポート要素。と共に、エンコーディング、セキュリティは、トランスポート設定は、バインディングの主要プロパティを形成します。</span><span class="sxs-lookup"><span data-stu-id="dc29b-165">The transport element for the current instance.Along with the encoding and security, the transport setting forms the core properties of a binding.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>