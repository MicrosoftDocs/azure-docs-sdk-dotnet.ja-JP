<Type Name="NetTcpRelaySecurityElement" FullName="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement">
  <TypeSignature Language="C#" Value="public sealed class NetTcpRelaySecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetTcpRelaySecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetTcpRelaySecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type NetTcpRelaySecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="54f60-101">Azure Service Bus リレーを通じた net TCP サービスのセキュリティを構成する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="54f60-101">Represents a configuration element that configures the security for a net TCP service through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetTcpRelaySecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.#ctor" />
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
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayConnectionElement" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Message" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="54f60-102">メッセージのセキュリティ設定を表す構成要素を取得、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="54f60-102">Gets a configuration element that represents the message security settings for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="54f60-103">返します、<see cref="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" />メッセージを格納しています。</span><span class="sxs-lookup"><span data-stu-id="54f60-103">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayConnectionElement" /> that contains the message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Mode" />
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
        <summary><span data-ttu-id="54f60-104">取得または設定で構成されているエンドポイントでメッセージ レベルまたはトランスポート レベルのセキュリティを使用するかどうかを記述する XML 値<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="54f60-104">Gets or sets an XML value that describes whether message-level or transport-level security is used by an endpoint configured with <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="54f60-105">返します、<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />セキュリティ モードを格納しています。</span><span class="sxs-lookup"><span data-stu-id="54f60-105">Returns a <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> that contains the security mode.</span></span> <span data-ttu-id="54f60-106">既定値は、Transport です。</span><span class="sxs-lookup"><span data-stu-id="54f60-106">The default value is Transport.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Properties" />
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
            <span data-ttu-id="54f60-107">プロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="54f60-107">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.RelayClientAuthenticationType" />
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
        <summary><span data-ttu-id="54f60-108">取得またはクライアントがメッセージを送信するときに、Azure Service Bus に表示するために必要な認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="54f60-108">Gets or sets the authentication type required for the client to present to the Azure Service Bus when sending messages.</span></span></summary>
        <value><span data-ttu-id="54f60-109">返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />認証の種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="54f60-109">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the authentication type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As TcpRelayTransportSecurityElement" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" Usage="Microsoft.ServiceBus.Configuration.NetTcpRelaySecurityElement.Transport" />
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
        <ReturnType>Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="54f60-110">トランスポート セキュリティ設定を取得、<see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="54f60-110">Gets the transport security setting for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="54f60-111">返します、<see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" />リレー バインドを格納しています。</span><span class="sxs-lookup"><span data-stu-id="54f60-111">Returns a <see cref="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" /> that contains the relay binding.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>