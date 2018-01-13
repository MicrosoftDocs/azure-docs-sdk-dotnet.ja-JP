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
    <summary>コンピューター間通信に適した、セキュリティで保護された、信頼性の高いバインドを提供します。</summary>
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
        <summary><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> クラスの新しいインスタンスを初期化します。</summary>
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
        <param name="configurationName">使用する構成。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />指定された XML 構成を持つクラス。 </summary>
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
        <param name="securityMode">バインディングで使用されるセキュリティの種類。 </param>
        <param name="relayClientAuthenticationType">リレーで使用されるクライアント認証の種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />クラスに使用されるセキュリティの種類とリレー クライアントの認証を指定します。 
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
        <param name="securityMode">Azure Service Bus のバインドで使用されるセキュリティの種類。</param>
        <param name="relayClientAuthenticationType">リレーで使用されるクライアント認証の種類。 </param>
        <param name="reliableSessionEnabled">信頼できるセッションが有効な場合は true。それ以外の場合は false です。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />使用されるセキュリティの種類、クライアント認証の種類、および信頼できるセッションが明示的に有効にするかどうかを示す値を持つクラス。</summary>
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
        <param name="transport">使用するトランスポート バインド要素。</param>
        <param name="encoding">使用するエンコーディング。</param>
        <param name="session">信頼できるセッション バインド要素。</param>
        <param name="security">セキュリティ バインド要素。</param>
        <summary>
            新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />指定されたトランスポート、エンコーダー、信頼できるセッション バインド要素、および使用されるセキュリティの種類を持つクラス。
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
        <param name="configurationName">設定を実行する構成要素の名前。</param>
        <summary>このバインド要素の現在のインスタンスに指定した名前を対応する構成要素の設定を適用します。</summary>
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
        <summary>バインド用のバインド要素でコレクションを作成します。 </summary>
        <returns>返します、<see cref="T:System.ServiceModel.Channels.BindingElementCollection" />バインド要素の順序付けられたスタックを格納しています。</returns>
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
        <summary>現在のインスタンスのメッセージのセキュリティ トークンを作成します。 </summary>
        <returns>返します<see cref="T:System.ServiceModel.Channels.SecurityBindingElement" />です。メッセージのセキュリティ トークンが含まれています。 </returns>
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
        <param name="transport"> 一致するようにトランスポート。 </param>
        <param name="encoding"> 一致するようにエンコードします。 </param>
        <param name="session"> 一致するセッションです。 </param>
        <summary>指定したオブジェクトが一致するバインド要素を持つかどうかを決定する値を返します。 </summary>
        <returns>返します<see cref="T:System.Boolean" />.true オブジェクトが一致する場合は、それ以外の場合は false。 </returns>
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
        <summary>Azure サービス バスのチャネルのエンドポイント間に信頼できるセッションを確立するかどうかを示すオブジェクトを取得します。 </summary>
        <value>返します<see cref="T:System.ServiceModel.OptionalReliableSession" />です。チャネルのエンドポイント間に WS-RM 信頼できるセッションが確立するかどうかを示します。 既定値は false です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>