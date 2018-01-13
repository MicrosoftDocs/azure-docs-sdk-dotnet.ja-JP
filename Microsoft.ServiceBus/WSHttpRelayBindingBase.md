<Type Name="WSHttpRelayBindingBase" FullName="Microsoft.ServiceBus.WSHttpRelayBindingBase">
  <TypeSignature Language="C#" Value="public abstract class WSHttpRelayBindingBase : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit WSHttpRelayBindingBase extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class WSHttpRelayBindingBase&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type WSHttpRelayBindingBase = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
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
    <summary>共通するメンバーを持つ基本クラスを提供、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />です。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected WSHttpRelayBindingBase (bool reliableSessionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(bool reliableSessionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.#ctor(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (reliableSessionEnabled As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WSHttpRelayBindingBase : bool -&gt; Microsoft.ServiceBus.WSHttpRelayBindingBase" Usage="new Microsoft.ServiceBus.WSHttpRelayBindingBase reliableSessionEnabled" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="reliableSessionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="reliableSessionEnabled">信頼できるセッションが有効である場合は true。それ以外の場合は false です。</param>
        <summary>信頼できるセッションが有効かどうかを示す値を使用して、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="wSHttpRelayBindingBase.CreateBindingElements " />
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
        <summary>Azure Service Bus の現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを返します。 </summary>
        <returns>返します<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />です。バインドのオブジェクトが含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMessageSecurity">
      <MemberSignature Language="C#" Value="protected abstract System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.SecurityBindingElement CreateMessageSecurity() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.CreateMessageSecurity" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateMessageSecurity () As SecurityBindingElement" />
      <MemberSignature Language="F#" Value="abstract member CreateMessageSecurity : unit -&gt; System.ServiceModel.Channels.SecurityBindingElement" Usage="wSHttpRelayBindingBase.CreateMessageSecurity " />
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
        <summary>派生クラスとして実装された場合は、Azure Service Bus の現在のバインドからセキュリティ バインド要素を返します。 </summary>
        <returns>返します<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />です。Azure Service Bus の現在のバインドからセキュリティ バインド要素が含まれています。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインドによって処理されるメッセージに使用される SOAP のバージョンを取得します。 </summary>
        <value>返します<see cref="T:System.ServiceModel.EnvelopeVersion" />です。この Azure Service Bus バインディングで使用されるエンベロープ バージョンの値。 値は、常に SOAP 1.2 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTransport">
      <MemberSignature Language="C#" Value="protected abstract System.ServiceModel.Channels.TransportBindingElement GetTransport ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.ServiceModel.Channels.TransportBindingElement GetTransport() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WSHttpRelayBindingBase.GetTransport" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function GetTransport () As TransportBindingElement" />
      <MemberSignature Language="F#" Value="abstract member GetTransport : unit -&gt; System.ServiceModel.Channels.TransportBindingElement" Usage="wSHttpRelayBindingBase.GetTransport " />
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
        <summary>派生クラスとして実装された場合は、Azure Service Bus の現在のバインドからトランスポート バインド要素を返します。 </summary>
        <returns>返します<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />です。Azure Service Bus の現在のバインドからトランスポート バインド要素が含まれています。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または使用するホスト名比較モードを設定します。</summary>
        <value>ホスト名を使用する比較モード。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDynamic">
      <MemberSignature Language="C#" Value="public bool IsDynamic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDynamic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.IsDynamic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはリレー バインドが動的かどうかを設定します。</summary>
        <value>リレー バインドは、動的; 場合は true。それ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはこの Azure Service Bus のバインドを使用してエンドポイントによって必要とするバッファーを管理するバッファー マネージャーに割り当てられたメモリの最大量を設定します。 </summary>
        <value>返します<see cref="T:System.Int64" />です。このバインディングで構成されるエンドポイントによって使用されるバッファーのプールのバイト単位で最大サイズ。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または Azure Service Bus バインディングにより処理可能なメッセージの最大サイズを設定します。 </summary>
        <value>返します<see cref="T:System.Int64" />です。最大サイズ (バイト単位)、Azure Service Bus バインディングによって処理されるメッセージ。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageEncoding">
      <MemberSignature Language="C#" Value="public System.ServiceModel.WSMessageEncoding MessageEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.WSMessageEncoding MessageEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.MessageEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageEncoding As WSMessageEncoding" />
      <MemberSignature Language="F#" Value="member this.MessageEncoding : System.ServiceModel.WSMessageEncoding with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.MessageEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.WSMessageEncoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>SOAP メッセージのエンコードに MTOM または Text/XML が使用されるかどうかを取得または設定します。 </summary>
        <value>返します<see cref="T:System.ServiceModel.WSMessageEncoding" />です。SOAP メッセージのエンコードに MTOM または TEXT/XML が使用されるかどうかを示します。 既定値は、TEXT/XML です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>HTTP プロキシの URI アドレスを取得または設定します。 </summary>
        <value>返します<see cref="T:System.Uri" />です。HTTP プロキシのアドレスとして機能します。 既定値は NULL です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、このセキュリティ バス バインディングで構成されるエンドポイントにより処理可能な SOAP メッセージの複雑さに対する制約を設定します。 </summary>
        <value>返します<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />です。複雑さの制約を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliableSession">
      <MemberSignature Language="C#" Value="public System.ServiceModel.OptionalReliableSession ReliableSession { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.OptionalReliableSession ReliableSession" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.ReliableSession" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReliableSession As OptionalReliableSession" />
      <MemberSignature Language="F#" Value="member this.ReliableSession : System.ServiceModel.OptionalReliableSession" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.ReliableSession" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.OptionalReliableSession</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>システム指定のバインディングのいずれかを使用するときに使用できる信頼性の高い Azure Service Bus セッションをバインド要素のプロパティに簡単にアクセスを提供するオブジェクトを取得します。 </summary>
        <value>返します<see cref="T:System.ServiceModel.OptionalReliableSession" />です。システム指定のバインディングのいずれかを使用するときに使用できる信頼性の高い Azure Service Bus セッションをバインド要素のプロパティに簡単にアクセスを提供します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングで構成されたチャネルとリスナーのための URI トランスポート スキームを取得します。 </summary>
        <value>返します<see cref="T:System.String" />を表す URI トランスポート スキーム。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
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
            受信要求が非同期的に処理されることを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding TextEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding TextEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.TextEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property TextEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.TextEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.TextEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージ テキストに使用される文字エンコーディングを取得または設定します。</summary>
        <value>文字エン コードは、メッセージ テキストに使用されます。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WSHttpRelayBindingBase.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.WSHttpRelayBindingBase.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>使用できる場合にシステムの自動構成される HTTP プロキシを使用するかどうかを示す値を取得または設定します。</summary>
        <value>使用可能な場合、システムの自動設定 HTTP プロキシを使用する場合は trueそれ以外の場合は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>