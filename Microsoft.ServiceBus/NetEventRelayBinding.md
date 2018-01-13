<Type Name="NetEventRelayBinding" FullName="Microsoft.ServiceBus.NetEventRelayBinding">
  <TypeSignature Language="C#" Value="public class NetEventRelayBinding : Microsoft.ServiceBus.NetOnewayRelayBinding, System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetEventRelayBinding extends Microsoft.ServiceBus.NetOnewayRelayBinding implements class System.ServiceModel.Channels.IBindingRuntimePreferences" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetEventRelayBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class NetEventRelayBinding&#xA;Inherits NetOnewayRelayBinding&#xA;Implements IBindingRuntimePreferences" />
  <TypeSignature Language="F#" Value="type NetEventRelayBinding = class&#xA;    inherit NetOnewayRelayBinding&#xA;    interface IBindingRuntimePreferences" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.NetOnewayRelayBinding</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.ServiceModel.Channels.IBindingRuntimePreferences</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>イベント発行元およびイベントのコンシューマーは、同じエンドポイントで rendezvous の任意の数をイベントの一方向のマルチキャストをサポートしているバインディングを表します。 </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configurationName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : string -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding configurationName" />
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
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />クラス、指定された構成を使用します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetEventRelayBinding (Microsoft.ServiceBus.EndToEndSecurityMode securityMode, Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType relayClientAuthenticationType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.ServiceBus.EndToEndSecurityMode securityMode, valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType relayClientAuthenticationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (securityMode As EndToEndSecurityMode, relayClientAuthenticationType As RelayEventSubscriberAuthenticationType)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : Microsoft.ServiceBus.EndToEndSecurityMode * Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding (securityMode, relayClientAuthenticationType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="securityMode" Type="Microsoft.ServiceBus.EndToEndSecurityMode" />
        <Parameter Name="relayClientAuthenticationType" Type="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType" />
      </Parameters>
      <Docs>
        <param name="securityMode">SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類。 </param>
        <param name="relayClientAuthenticationType">クライアントで使用される認証の種類。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />クラス、指定したセキュリティ モードとリレー クライアント認証の種類を使用します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NetEventRelayBinding (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, Microsoft.ServiceBus.NetOnewayRelaySecurity security);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class Microsoft.ServiceBus.NetOnewayRelaySecurity security) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.#ctor(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,Microsoft.ServiceBus.NetOnewayRelaySecurity)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (transport As RelayedOnewayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, security As NetOnewayRelaySecurity)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NetEventRelayBinding : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * Microsoft.ServiceBus.NetOnewayRelaySecurity -&gt; Microsoft.ServiceBus.NetEventRelayBinding" Usage="new Microsoft.ServiceBus.NetEventRelayBinding (transport, encoding, security)" />
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
        <param name="transport"> トランスポートを使用します。 </param>
        <param name="encoding"> 使用するエンコーディング。 </param>
        <param name="security"> SOAP メッセージと共に、およびクライアントに対して使用されるセキュリティの種類。 </param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />クラス、指定されたトランスポート、エンコーディング、およびセキュリティ要素を使用します。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyConfiguration">
      <MemberSignature Language="C#" Value="protected override void ApplyConfiguration (string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ApplyConfiguration(string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.ApplyConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ApplyConfiguration (configurationName As String)" />
      <MemberSignature Language="F#" Value="override this.ApplyConfiguration : string -&gt; unit" Usage="netEventRelayBinding.ApplyConfiguration configurationName" />
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
    <Member MemberName="IsBindingElementsMatch">
      <MemberSignature Language="C#" Value="protected bool IsBindingElementsMatch (Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, System.ServiceModel.Channels.ReliableSessionBindingElement session);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance bool IsBindingElementsMatch(class Microsoft.ServiceBus.RelayedOnewayTransportBindingElement transport, class System.ServiceModel.Channels.BinaryMessageEncodingBindingElement encoding, class System.ServiceModel.Channels.ReliableSessionBindingElement session) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NetEventRelayBinding.IsBindingElementsMatch(Microsoft.ServiceBus.RelayedOnewayTransportBindingElement,System.ServiceModel.Channels.BinaryMessageEncodingBindingElement,System.ServiceModel.Channels.ReliableSessionBindingElement)" />
      <MemberSignature Language="VB.NET" Value="Protected Function IsBindingElementsMatch (transport As RelayedOnewayTransportBindingElement, encoding As BinaryMessageEncodingBindingElement, session As ReliableSessionBindingElement) As Boolean" />
      <MemberSignature Language="F#" Value="override this.IsBindingElementsMatch : Microsoft.ServiceBus.RelayedOnewayTransportBindingElement * System.ServiceModel.Channels.BinaryMessageEncodingBindingElement * System.ServiceModel.Channels.ReliableSessionBindingElement -&gt; bool" Usage="netEventRelayBinding.IsBindingElementsMatch (transport, encoding, session)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transport" Type="Microsoft.ServiceBus.RelayedOnewayTransportBindingElement" />
        <Parameter Name="encoding" Type="System.ServiceModel.Channels.BinaryMessageEncodingBindingElement" />
        <Parameter Name="session" Type="System.ServiceModel.Channels.ReliableSessionBindingElement" />
      </Parameters>
      <Docs>
        <param name="transport"> 現在のインスタンスと照合するトランスポート。 </param>
        <param name="encoding"> 現在のインスタンスと照合するエンコーディング。 </param>
        <param name="session"> 現在のインスタンスと照合するセッションです。</param>
        <summary>指定されたバインド要素が、現在のインスタンスを一致するかどうかを決定する値を取得します。 </summary>
        <returns>バインドが一致する場合、true を返しますそれ以外の場合は false です。 </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>