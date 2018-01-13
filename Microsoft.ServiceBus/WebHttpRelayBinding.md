<Type Name="WebHttpRelayBinding" FullName="Microsoft.ServiceBus.WebHttpRelayBinding">
  <TypeSignature Language="C#" Value="public class WebHttpRelayBinding : System.ServiceModel.Channels.Binding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebHttpRelayBinding extends System.ServiceModel.Channels.Binding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WebHttpRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class WebHttpRelayBinding&#xA;Inherits Binding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type WebHttpRelayBinding = class&#xA;    inherit Binding&#xA;    interface IBindingRuntimePreferences" />
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
    <summary>SOAP メッセージに代わって HTTP 要求を介して公開される Web サービスのエンドポイントを構成するために使用するバインディング。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> クラスの新しいインスタンスを初期化します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WebHttpRelayBinding : string -&gt; Microsoft.ServiceBus.WebHttpRelayBinding" Usage="new Microsoft.ServiceBus.WebHttpRelayBinding configurationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configurationName">使用する構成。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />クラスの指定された構成名を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebHttpRelayBinding (Microsoft.ServiceBus.EndToEndWebHttpSecurityMode securityMode, Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayClientAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndWebHttpSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.WebHttpRelayBinding : Microsoft.ServiceBus.EndToEndWebHttpSecurityMode * Microsoft.ServiceBus.RelayClientAuthenticationType -&gt; Microsoft.ServiceBus.WebHttpRelayBinding" Usage="new Microsoft.ServiceBus.WebHttpRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayClientAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode">バインディングで使用されるセキュリティの種類。</param>
        <param name="relayClientAuthenticationType">リレーで使用されるクライアント認証の種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />クラスの指定した型のセキュリティとリレー クライアントの認証を使用します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowCookies">
      <MemberSignature Language="C#" Value="public bool AllowCookies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AllowCookies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.AllowCookies" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowCookies As Boolean" />
      <MemberSignature Language="F#" Value="member this.AllowCookies : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.AllowCookies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定を介して送信されるメッセージでクッキーを許可するかどうかを指定する値、<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />です。</summary>
        <value>Cookie が使用できる場合は true を返しますそれ以外の場合は false です。 既定値は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentTypeMapper">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Channels.WebContentTypeMapper ContentTypeMapper { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Channels.WebContentTypeMapper ContentTypeMapper" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ContentTypeMapper" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentTypeMapper As WebContentTypeMapper" />
      <MemberSignature Language="F#" Value="member this.ContentTypeMapper : System.ServiceModel.Channels.WebContentTypeMapper with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ContentTypeMapper" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Channels.WebContentTypeMapper</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>コンテンツ タイプ マッパーを取得または設定します。</summary>
        <value>コンテンツ タイプ マッパー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBindingElements">
      <MemberSignature Language="C#" Value="public override System.ServiceModel.Channels.BindingElementCollection CreateBindingElements ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.ServiceModel.Channels.BindingElementCollection CreateBindingElements() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.WebHttpRelayBinding.CreateBindingElements" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CreateBindingElements () As BindingElementCollection" />
      <MemberSignature Language="F#" Value="override this.CreateBindingElements : unit -&gt; System.ServiceModel.Channels.BindingElementCollection" Usage="webHttpRelayBinding.CreateBindingElements " />
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
        <summary>バインド用のバインド要素でコレクションを作成します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />によって使用されるバインド要素の順序付けられたスタックを含む、<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvelopeVersion">
      <MemberSignature Language="C#" Value="public System.ServiceModel.EnvelopeVersion EnvelopeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.EnvelopeVersion EnvelopeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.EnvelopeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvelopeVersion As EnvelopeVersion" />
      <MemberSignature Language="F#" Value="member this.EnvelopeVersion : System.ServiceModel.EnvelopeVersion" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.EnvelopeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.EnvelopeVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>SOAP エンベロープのバージョンを取得します。 </summary>
        <value><see cref="T:System.ServiceModel.EnvelopeVersion" /> を返します。 以降、 <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> SOAP、常にこの EnvelopeVersion.None を返しますを使用しません。<see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> ない可能性があります、バインドの SOAP を使用している必要がありますメッセージングです。 ただし、Service Bus は SOAP をサポートします。 </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameComparisonMode">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HostNameComparisonMode HostNameComparisonMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HostNameComparisonMode HostNameComparisonMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.HostNameComparisonMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameComparisonMode As HostNameComparisonMode" />
      <MemberSignature Language="F#" Value="member this.HostNameComparisonMode : System.ServiceModel.HostNameComparisonMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.HostNameComparisonMode" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.IsDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDynamic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDynamic : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.IsDynamic" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferPoolSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferPoolSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxBufferPoolSize : int64 with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferPoolSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトランスポートによって使用される最大バッファー プール サイズを設定します。</summary>
        <value>最大バッファー プール サイズを返します。 既定では 524, 288 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxBufferSize">
      <MemberSignature Language="C#" Value="public int MaxBufferSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxBufferSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxBufferSize As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxBufferSize : int with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxBufferSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはトランスポートによってサポートされている最大バッファー サイズを設定します。 </summary>
        <value>最大バッファー サイズを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReceivedMessageSize">
      <MemberSignature Language="C#" Value="public long MaxReceivedMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxReceivedMessageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReceivedMessageSize As Long" />
      <MemberSignature Language="F#" Value="member this.MaxReceivedMessageSize : int64 with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.MaxReceivedMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>受信できる最大メッセージ サイズを取得または設定します。</summary>
        <value>メッセージの最大サイズを返します。 既定のサイズは 65,536 バイトです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProxyAddress">
      <MemberSignature Language="C#" Value="public Uri ProxyAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ProxyAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ProxyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyAddress As Uri" />
      <MemberSignature Language="F#" Value="member this.ProxyAddress : Uri with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ProxyAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>HTTP 要求に使用するプロキシのアドレスを格納する URI を取得または設定します。</summary>
        <value>返します、 <see cref="T:System.Uri" /> HTTP 要求に使用するプロキシのアドレスを格納しています。 既定値は NULL です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReaderQuotas">
      <MemberSignature Language="C#" Value="public System.Xml.XmlDictionaryReaderQuotas ReaderQuotas { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Xml.XmlDictionaryReaderQuotas ReaderQuotas" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.ReaderQuotas" />
      <MemberSignature Language="VB.NET" Value="Public Property ReaderQuotas As XmlDictionaryReaderQuotas" />
      <MemberSignature Language="F#" Value="member this.ReaderQuotas : System.Xml.XmlDictionaryReaderQuotas with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.ReaderQuotas" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.XmlDictionaryReaderQuotas</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または処理されるメッセージで xml リーダーのクォータを設定します。</summary>
        <value>返します、<see cref="T:System.Xml.XmlDictionaryReaderQuotas" />リーダーのクォータを格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheme">
      <MemberSignature Language="C#" Value="public override string Scheme { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Scheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.Scheme" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Scheme As String" />
      <MemberSignature Language="F#" Value="member this.Scheme : string" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.Scheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>バインディングで使用されるエンドポイントのスキームを取得します。</summary>
        <value>スキームを返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Security">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.WebHttpRelaySecurity Security { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.WebHttpRelaySecurity Security" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.Security" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Security As WebHttpRelaySecurity" />
      <MemberSignature Language="F#" Value="member this.Security : Microsoft.ServiceBus.WebHttpRelaySecurity" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.Security" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.WebHttpRelaySecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>現在のインスタンスのセキュリティ設定を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.WebHttpRelaySecurity" />セキュリティ設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously">
      <MemberSignature Language="C#" Value="bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.System#ServiceModel#Channels#IBindingRuntimePreferences#ReceiveSynchronously" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property ReceiveSynchronously As Boolean Implements IBindingRuntimePreferences.ReceiveSynchronously" />
      <MemberSignature Language="F#" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.System.ServiceModel.Channels.IBindingRuntimePreferences.ReceiveSynchronously" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.TransferMode" />
      <MemberSignature Language="VB.NET" Value="Public Property TransferMode As TransferMode" />
      <MemberSignature Language="F#" Value="member this.TransferMode : System.ServiceModel.TransferMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.TransferMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.TransferMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>転送モードを取得または設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />転送モードを格納しています。 既定値はバッファーです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDefaultWebProxy">
      <MemberSignature Language="C#" Value="public bool UseDefaultWebProxy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDefaultWebProxy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.UseDefaultWebProxy" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDefaultWebProxy As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDefaultWebProxy : bool with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.UseDefaultWebProxy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>ユーザー固有の設定ではなく、コンピューター全体のプロキシ設定を使用するかどうかを示す値を取得または設定します。</summary>
        <value>コンピューター全体のプロキシ設定を使用する場合は true。 それ以外の場合は false。 既定値は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEncoding">
      <MemberSignature Language="C#" Value="public System.Text.Encoding WriteEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Text.Encoding WriteEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelayBinding.WriteEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteEncoding As Encoding" />
      <MemberSignature Language="F#" Value="member this.WriteEncoding : System.Text.Encoding with get, set" Usage="Microsoft.ServiceBus.WebHttpRelayBinding.WriteEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Text.Encoding</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージ テキストの書き込みに使用される文字エンコーディングを取得または設定します。</summary>
        <value>返します、<see cref="T:System.Text.Encoding" />エンコードを含むです。 既定値は、utf8encoding です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>