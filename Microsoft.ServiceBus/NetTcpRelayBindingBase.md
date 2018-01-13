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
    <summary>一般的な方法の基本クラス、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />バインドします。</summary>
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
        <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <param name="configurationName">バインド構成の名前。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定された構成名を使用します。</summary>
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
        <param name="securityMode">バインディングで使用されるセキュリティの種類。</param>
        <param name="relayClientAuthenticationType">使用するリレー認証の種類。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定したセキュリティ モードとリレー認証の種類を使用します。</summary>
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
        <param name="transport"> トランスポート。</param>
        <param name="encoding"> エンコーディング。</param>
        <param name="security"> セキュリティ。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBindingBase" />クラス、指定されたトランスポート、エンコーディング、およびセキュリティを使用します。</summary>
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
        <param name="configurationName">設定を実行する構成要素の名前。</param>
        <summary>このバインド要素の現在のインスタンスに指定した名前を対応する構成要素の設定を適用します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Configuration.ConfigurationErrorsException">入力構成の名前、構成で指定されたバインド要素を見つけることができませんでした。</exception>
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
        <summary>接続モード取得または設定します。<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />または<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />です。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />接続を格納しているモードです。 いずれかの<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />または<see cref="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />です。 既定値は中継されます。</value>
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
        <summary>現在のバインディングに含まれるバインディング要素の順序付けられたコレクションを取得します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />バインディングを構成します。</returns>
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
        <summary>現在のインスタンスのセキュリティ バインド要素を作成します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />セキュリティ バインド要素を格納しています。</returns>
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
        <summary>現在のインスタンスのエンコード要素。セキュリティとトランスポートの設定と共に、エンコーディング バインディングの次の 3 つの主要プロパティを形成します。</summary>
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
        <summary>このバインディングによって処理されるメッセージで使用される SOAP のバージョンを取得します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.EnvelopeVersion" />このバインドで使用されるエンベロープ バージョンを格納しています。</value>
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
        <summary>取得または使用するホスト名比較モードを設定します。</summary>
        <value>使用するホスト名比較モード。</value>
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
        <param name="transport"> トランスポート バインド要素。</param>
        <param name="encoding"> エンコーディング バインド要素。</param>
        <summary>指定されたバインド要素が、現在のインスタンス内のバインド要素の既定値に一致するかどうかを判断します。</summary>
        <returns>要素が一致する場合は true。それ以外の場合は false です。</returns>
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
        <summary>取得またはリレー バインドが動的かどうかを設定します。</summary>
        <value>リレー バインドは、動的; 場合は true。それ以外の場合は false です。</value>
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
        <summary>保留可能なキュー内の接続要求の最大数を取得または設定します。</summary>
        <value>保留可能なキュー内の接続要求の最大数を返します。 既定値は 10 です。</value>
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
        <summary>取得または、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを設定します。</summary>
        <value>(バイト単位)、バインディングによって処理されるメッセージを格納するバッファー プールの最大サイズを返します。 既定値は 65,536 です。</value>
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
        <summary>取得またはメモリにメッセージを格納するために使用するバッファーの最大サイズを指定する値を設定します。</summary>
        <value>(バイト単位) をメモリにメッセージを保存するために使用するバッファーの最大サイズを返します。 既定値は 65,536 です。</value>
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
        <summary>クライアント上で後で再使用するためにプールできる接続の最大数と、サーバー上でディスパッチを保留できる接続の最大数を制御する値を取得または設定します。</summary>
        <value>クライアントでは、後続の再利用をプールできる接続の最大数を返しますサーバー上でディスパッチを保留できる接続の最大数を返します。</value>
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
        <summary>このバインドで処理される受信メッセージの最大サイズを取得または設定します。</summary>
        <value>バインディングによって処理される受信メッセージのバイト単位で最大のサイズを返します。 既定値は 65,536 です。</value>
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
        <summary>メッセージ セキュリティ バージョンを取得します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageSecurityVersion" />メッセージ セキュリティ バージョンを格納しています。 これは現在常に返されます MessageSecurityVersion..:: です。Wssecurity11wstrustfebruary2005wssecureconversationfebruary2005wssecuritypolicy11 でします。 </value>
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
        <summary>このバインディングを使用して設定されるエンドポイントにより処理可能な、SOAP メッセージの複雑さに対する制約を取得または設定します。 このプロパティを null にすることはできません。</summary>
        <value>返します、<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />交換される soap メッセージに対する複雑さの制約を指定します。 これらの制約の既定値については、後の「解説」で説明します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"> ある ReaderQuotas が null の場合</exception>
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
        <summary>トランスポートの URI スキームを取得します。</summary>
        <value>トランスポートの URI スキームを返します。 既定値は、"sb"です。</value>
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
        <summary>この要素を使用して構成されたサービスで使用されるセキュリティの種類を指定するオブジェクトを取得します。</summary>
        <value>返します<see cref="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />、このバインディングで使用されるセキュリティの種類が含まれています。 セキュリティの既定のモードは、トランスポートです。</value>
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
            受信要求が非同期的に処理されることを示します。
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
        <summary>このバインディングを使用して構成されたサービスが、メッセージ転送のストリーミング モードまたはバッファー モード (あるいは両方のモード) を使用するかどうかを示す値を取得または設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />ストリームまたはバッファー内のバインドを使用して (または両方) でサービスが構成されているかどうかを示すメッセージ転送のモード。 既定では、HTTP、TCP/IP、および名前付きパイプ トランスポートは、バッファー内のメッセージ転送を使用します。</value>
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
        <summary>現在のインスタンスのトランスポート要素。と共に、エンコーディング、セキュリティは、トランスポート設定は、バインディングの主要プロパティを形成します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>