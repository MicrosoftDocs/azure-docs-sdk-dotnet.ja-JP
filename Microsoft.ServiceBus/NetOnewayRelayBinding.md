<Type Name="NetOnewayRelayBinding" FullName="Microsoft.ServiceBus.NetOnewayRelayBinding">
  <TypeSignature Language="C#" Value="public class NetOnewayRelayBinding : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetOnewayRelayBinding extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class NetOnewayRelayBinding&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetOnewayRelayBinding = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
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
    <summary>クラウドを介して、セキュリティで保護された、一方向の接続のバインドを表します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetOnewayRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetOnewayRelayBinding (Microsoft.ServiceBus.NetOnewayRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NetOnewayRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor(Microsoft.ServiceBus.NetOnewayRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (security As NetOnewayRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetOnewayRelayBinding : Microsoft.ServiceBus.NetOnewayRelaySecurity -&gt; Microsoft.ServiceBus.NetOnewayRelayBinding" Usage="new Microsoft.ServiceBus.NetOnewayRelayBinding security" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetOnewayRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="security">セキュリティ設定。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />クラス、指定されたセキュリティ設定を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetOnewayRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetOnewayRelayBinding : string -&gt; Microsoft.ServiceBus.NetOnewayRelayBinding" Usage="new Microsoft.ServiceBus.NetOnewayRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">使用する構成の名前。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />クラスの指定の構成を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetOnewayRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetOnewayRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetOnewayRelayBinding" Usage="new Microsoft.ServiceBus.NetOnewayRelayBinding (securityMode, relayClientAuthenticationType)" />
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
        <param name="securityMode">セキュリティ モード。 </param>
        <param name="relayClientAuthenticationType">認証の種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />クラス、指定したセキュリティ モードと認証の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetOnewayRelayBinding (Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode, Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.RelayedOnewayConnectionMode connectionMode, valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor(Microsoft.ServiceBus.RelayedOnewayConnectionMode,Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetOnewayRelayBinding : Microsoft.ServiceBus.RelayedOnewayConnectionMode * Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.NetOnewayRelayBinding" Usage="new Microsoft.ServiceBus.NetOnewayRelayBinding (connectionMode, securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionMode" Type="Microsoft.ServiceBus.RelayedOnewayConnectionMode" />
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="connectionMode">接続モードです。 </param>
        <param name="securityMode">SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類。 </param>
        <param name="relayClientAuthenticationType">クライアントで使用される認証の種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />クラス、指定された接続とセキュリティのモードだけでなく、認証の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetOnewayRelayBinding (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, Microsoft.ServiceBus.NetOnewayRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class Microsoft.ServiceBus.NetOnewayRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.#ctor(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,Microsoft.ServiceBus.NetOnewayRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As RelayedOnewayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, security As NetOnewayRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetOnewayRelayBinding : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * Microsoft.ServiceBus.NetOnewayRelaySecurity -&gt; Microsoft.ServiceBus.NetOnewayRelayBinding" Usage="new Microsoft.ServiceBus.NetOnewayRelayBinding (transport, encoding, security)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="security" Type="Microsoft.ServiceBus.NetOnewayRelaySecurity" />
      </Parameters>
      <Docs>
        <param name="transport"> トランスポート要素は、中核となるトランスポート設定を含むです。</param>
        <param name="encoding"> エンコード要素です。</param>
        <param name="security"> セキュリティ設定。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetOnewayRelayBinding" />クラス、指定されたトランスポート、エンコーディング、およびセキュリティを使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected virtual void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="abstract member ApplyConfiguration : string -&gt; unit&#xA;override this.ApplyConfiguration : string -&gt; unit" Usage="netOnewayRelayBinding.ApplyConfiguration configurationName" />
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
        <param name="configurationName">設定を実行する構成要素の名前。</param>
        <summary>このバインド要素の現在のインスタンスに指定した名前を対応する構成要素の設定を適用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetOnewayRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="netOnewayRelayBinding.CreateBindingElements " />
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
        <summary>バインド要素のセットを作成します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />バインディング要素を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="encoding">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetOnewayRelayBinding.encoding" />
      <MemberSignature Language="VB.NET" Value="Protected Friend encoding As BinaryMessageEncodingBindingElement " />
      <MemberSignature Language="F#" Value="val mutable encoding : System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.encoding" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.BinaryMessageEncodingBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バインディングのエンコーディングを表します。およびセキュリティ設定とトランスポートの種類、エンコーディング バインディングの次の 3 つの主要プロパティを表します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングによって処理されるメッセージで使用される SOAP のバージョンを取得します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.EnvelopeVersion" />エンベロープ バージョンを格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.HostNameComparisonMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HostNameComparisonMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            URI が一致した場合にサービスに到達するためにホスト名を使用するかどうかを示す値を取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenBacklog">
      <MemberSignature Language="C#" Value="public int ListenBacklog { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ListenBacklog" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.ListenBacklog" />
      <MemberSignature Language="VB.NET" Value="Public Property ListenBacklog As Integer" />
      <MemberSignature Language="F#" Value="member this.ListenBacklog : int with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.ListenBacklog" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>保留可能なキュー内の接続要求の最大数を取得または設定します。</summary>
        <value>保留可能なキュー内の接続要求の最大数を返します。 既定値は 10 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferPoolSize">
      <MemberSignature Language="C#" Value="public long MaxBufferPoolSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxBufferPoolSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを設定します。</summary>
        <value>バインディングによって処理されるメッセージを格納するバッファー プールに入力できる最大サイズを返します。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージをメモリに保存するために使用するバッファーの最大サイズをバイト単位で指定する値を取得または設定します。</summary>
        <value>(バイト単位) をメモリにメッセージを保存するために使用するバッファーの最大サイズを返します。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnections">
      <MemberSignature Language="C#" Value="public int MaxConnections { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.MaxConnections" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnections As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnections : int with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.MaxConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアント上で後で再使用するためにプールできる接続の最大数と、サーバー上でディスパッチを保留できる接続の最大数を制御する値を取得または設定します。</summary>
        <value>クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインドで処理される受信メッセージの最大サイズを取得または設定します。</summary>
        <value>バインディングによって処理される受信メッセージのバイト単位で最大のサイズを返します。 既定値は 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessageSecurityVersion">
      <MemberSignature Language="C#" Value="protected internal System.ServiceModel.MessageSecurityVersion MessageSecurityVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.MessageSecurityVersion MessageSecurityVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.MessageSecurityVersion" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property MessageSecurityVersion As MessageSecurityVersion" />
      <MemberSignature Language="F#" Value="member this.MessageSecurityVersion : System.ServiceModel.MessageSecurityVersion" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.MessageSecurityVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageSecurityVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージ セキュリティ バージョンを取得します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageSecurityVersion" />メッセージ セキュリティ バージョンを格納しています。 現在 MessageSecurityVersion が返されます..:: です。Wssecurity11wstrustfebruary2005wssecureconversationfebruary2005wssecuritypolicy11 でします。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>このバインディングを使用して設定されるエンドポイントにより処理可能な、SOAP メッセージの複雑さに対する制約を取得または設定します。</summary>
        <value>返します、<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />インスタンスが交換される SOAP メッセージに対する複雑さの制約を指定します。 これらの制約の既定値については、後の「解説」で説明します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トランスポートの URI スキームを取得します。</summary>
        <value>トランスポートの URI スキームを返します。 既定値は、"sb"、Azure Service Bus を示すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NetOnewayRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NetOnewayRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As NetOnewayRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.NetOnewayRelaySecurity" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NetOnewayRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>この要素を使用して構成されたサービスで使用されるセキュリティの種類を指定するオブジェクトを取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.NetOnewayRelaySecurity" />このバインディングで使用されるセキュリティの種類を格納するインスタンス。 この型には、メッセージ セキュリティ、エンド ツー エンド セキュリティ モード、リレー クライアントの認証の種類、およびトランスポートが含まれています。 セキュリティの設定。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetOnewayRelayBinding.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
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
    <Member MemberName="transport">
      <MemberSignature Language="C#" Value="protected internal Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport;" />
      <MemberSignature Language="ILAsm" Value=".field familyorassembly class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NetOnewayRelayBinding.transport" />
      <MemberSignature Language="VB.NET" Value="Protected Friend transport As RelayedOnewayTransportBindingElement " />
      <MemberSignature Language="F#" Value="val mutable transport : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" Usage="Microsoft.ServiceBus.NetOnewayRelayBinding.transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayedOnewayTransportBindingElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バインディングのトランスポートの種類を指定します。と共に、エンコードやセキュリティの設定は、トランスポートの種類は、バインディングの 3 つの主要プロパティを表します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>