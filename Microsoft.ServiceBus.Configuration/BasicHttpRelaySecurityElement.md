<Type Name="BasicHttpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type BasicHttpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>基本 HTTP リレー バインドのセキュリティを構成する構成要素を表します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BasicHttpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.#ctor" />
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
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As BasicHttpRelayMessageSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Message" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>メッセージ レベルのセキュリティ設定を指定する構成要素を取得、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。</summary>
        <value>返します、<see cref="T:Microsoft.ServiceBus.Configuration.BasicHttpRelayMessageSecurityElement" />セキュリティ設定を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndBasicHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Mode" />
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
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または設定のセキュリティ モード、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。</summary>
        <value>値を返します、<see cref="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />列挙します。 既定値は none です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Configuration.ConfigurationPropertyCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プロパティのコレクションを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.RelayClientAuthenticationType" />
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
        <summary>取得または、この構成要素で指定された認証の種類を設定します。</summary>
        <value>値を返します<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />バインド要素に適用されて、現在のインスタンスによって使用される認証の種類を格納しています。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.BasicHttpRelaySecurityElement.Transport" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>トランスポート レベルのセキュリティ設定を指定する構成要素を取得、<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />バインドします。</summary>
        <value>返します、 <see cref="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" /> HTTP トランスポートの認証パラメーターを制御するプロパティを格納します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>