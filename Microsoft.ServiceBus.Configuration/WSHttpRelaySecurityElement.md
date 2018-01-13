<Type Name="WSHttpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class WSHttpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WSHttpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WSHttpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type WSHttpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Azure Service Bus リレーを通じた WS HTTP サービスのセキュリティを構成する構成要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WSHttpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As NonDualMessageSecurityOverRelayHttpElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージのセキュリティ設定を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.NonDualMessageSecurityOverRelayHttpElement" />メッセージのセキュリティ設定を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("mode", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または HTTP 要求を受信するように構成エンドポイントによって使用されるセキュリティのモードを設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />適用されるセキュリティの種類を指定します。 既定値は Message です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("relayClientAuthenticationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはサービス クライアントによって使用されるリレー クライアント認証の種類を設定します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />認証の種類を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As WSHttpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.WSHttpRelaySecurityElement.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("transport")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トランスポートのセキュリティ設定を取得します。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" />トランスポートのセキュリティ設定を指定します。使用して、<see cref="T:Microsoft.ServiceBus.Configuration.WSHttpRelayTransportSecurityElement" />トランスポートのセキュリティ パラメーターを設定するには、このプロパティによって返されるオブジェクト、<see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" />です。 によって、TransportCredentialOnly 値が指定されている場合<see cref="M:Microsoft.ServiceBus.WSHttpRelayBinding.#ctor(Microsoft.ServiceBus.EndToEndSecurityMode,Microsoft.ServiceBus.RelayClientAuthenticationType,System.Boolean)" />トランスポートのプロパティによって指定される設定がサービス エンドポイントで有効になります。 このプロパティの値として設定できますコンス トラクターでのみ、明示的なパラメーターと、バインディング インスタンスが作成された後に、その値をもう一度設定することはできません。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>