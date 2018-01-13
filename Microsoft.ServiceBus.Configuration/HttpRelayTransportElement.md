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
    <summary>SOAP メッセージ送信用 HTTP トランスポートを指定する構成要素を表します。</summary>
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
        <summary><see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportElement" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <summary>取得またはクライアントが cookie を受け入れ、それらを今後の要求に反映させるかどうかを示す構成ファイルから値を設定します。</summary>
        <value>cookie を許可する場合は true。それ以外の場合は false です。 既定値は false です。</value>
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
        <param name="bindingElement"> 設定を更新するバインド要素。</param>
        <summary>指定されたバインド要素をこの構成要素の設定を適用します。</summary>
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
        <summary>バインディングの種類を取得します。 (BindingElementExtensionElement.BindingElementType をオーバーライドします)。</summary>
        <value>返します、<see cref="T:System.Type" />バインドの種類を格納しています。</value>
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
        <param name="from"> 拡張機能の要素をコピーするプロパティを持つ。</param>
        <summary>この構成要素に指定された拡張要素のプロパティをコピーします。</summary>
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
        <summary>この構成要素の設定からバインド要素を作成します。</summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.TransportBindingElement" />既定のバインド要素を格納しています。</returns>
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
        <param name="bindingElement"> 初期化するためにバインド要素。</param>
        <summary>このバインド構成要素を、指定されたバインド要素の内容で初期化します。</summary>
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
        <summary>取得またはリレー バインドが動的かどうかを設定します。</summary>
        <value>リレー バインドは、動的; 場合は true。それ以外の場合は false です。</value>
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
        <summary>取得またはインターネット リソースへ永続的な接続を作成するかどうかを示す構成ファイルからブール値を設定します。</summary>
        <value>インターネット リソースへ永続的な接続が維持される場合は true。それ以外の場合は false です。</value>
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
        <summary>取得または構成ファイルからバッファー プールの最大サイズを設定します。</summary>
        <value>バッファーの最大サイズを返します。 既定値は 65,536 です。</value>
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
        <summary>取得、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />属性を保持できる ConfigurationProperty オブジェクトまたはこの構成要素の ConfigurationElement オブジェクトのコレクションを格納するインスタンス。 (TransportElement.Properties をオーバーライドします)。</summary>
        <value>返します、<see cref="T:System.Configuration.ConfigurationPropertyCollection" />現在のインスタンスのプロパティを格納します。</value>
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
        <summary>取得または HTTP 要求に使用するプロキシのアドレスを格納する構成ファイルの URI を設定します。</summary>
        <value>返します、 <see cref="T:System.Uri" /> URI を格納します。 既定値は null です。</value>
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
        <summary>取得または HTTP プロキシによって処理されるクライアント要求の認証に使用する認証方式を設定します。</summary>
        <value>HTTP プロキシによって処理されるクライアント要求を認証するために使用する認証方式です。</value>
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
        <summary>取得または構成ファイルに格納されているリレー クライアント認証の種類を設定します。</summary>
        <value><see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> を返します。</value>
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
        <summary>取得またはメッセージをバッファリングまたは要求または応答のストリーム配信されるかどうかを指定する構成ファイルから値を設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.TransferMode" />メッセージをバッファリングまたは要求または応答のストリーム配信されるかどうかを指定します。 既定では、HTTP、TCP/IP、および名前付きパイプ トランスポートは、バッファー内のメッセージ転送を使用します。</value>
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
        <summary>取得またはユーザー固有の設定ではなく、コンピューター全体のプロキシ設定が使用されるかどうかを示す構成ファイルから値を設定します。</summary>
        <value>System.Net の既定のプロキシ設定が使用される場合は trueそれ以外の場合は false です。 既定値は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>