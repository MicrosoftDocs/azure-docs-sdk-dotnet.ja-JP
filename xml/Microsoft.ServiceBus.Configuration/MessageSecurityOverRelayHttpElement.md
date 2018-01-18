<Type Name="MessageSecurityOverRelayHttpElement" FullName="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement">
  <TypeSignature Language="C#" Value="public class MessageSecurityOverRelayHttpElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageSecurityOverRelayHttpElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageSecurityOverRelayHttpElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayHttpElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="87c94-101">HTTP トランスポート メカニズムを使用して、Azure Service Bus リレー経由でメッセージ セキュリティを説明する構成要素。</span><span class="sxs-lookup"><span data-stu-id="87c94-101">A configuration element that describes the message security over the Azure Service Bus relay, using an HTTP transport mechanism.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.TypeConverter(typeof(Microsoft.ServiceBus.Configuration.SecurityAlgorithmSuiteConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("algorithmSuite", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87c94-102">取得または設定、構成ファイル、メッセージの暗号化とキー ラップ アルゴリズムを HTTP メッセージをセキュリティで保護するために使用します。</span><span class="sxs-lookup"><span data-stu-id="87c94-102">Gets or sets from the configuration file the message encryption and key-wrap algorithms used to secure an HTTP message.</span></span></summary>
        <value><span data-ttu-id="87c94-103">メッセージの暗号化とキー ラップ アルゴリズムを HTTP メッセージをセキュリティで保護するために使用します。</span><span class="sxs-lookup"><span data-stu-id="87c94-103">The message encryption and key-wrap algorithms used to secure an HTTP message.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("clientCredentialType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87c94-104">取得または構成ファイルからメッセージ ベースのセキュリティまたは TransportWithMessageCredential を使用してクライアント認証を実行するときに使用される資格情報の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="87c94-104">Gets or sets from the configuration file the type of credential to be used when performing client authentication using message-based security or TransportWithMessageCredential.</span></span></summary>
        <value><span data-ttu-id="87c94-105">返します、<see cref="T:System.ServiceModel.MessageCredentialType" />メッセージ資格情報の種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="87c94-105">Returns a <see cref="T:System.ServiceModel.MessageCredentialType" /> that contains the message credential type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NegotiateServiceCredential">
      <MemberSignature Language="C#" Value="public bool NegotiateServiceCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NegotiateServiceCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.NegotiateServiceCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property NegotiateServiceCredential As Boolean" />
      <MemberSignature Language="F#" Value="member this.NegotiateServiceCredential : bool with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayHttpElement.NegotiateServiceCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("negotiateServiceCredential", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="87c94-106">取得または構成ファイルからサービスの資格情報が、クライアントのアウトバンドで提供されるか、ネゴシエーションのプロセスを使用してクライアントにサービスから取得されるかどうかを指定するブール値を設定します。</span><span class="sxs-lookup"><span data-stu-id="87c94-106">Gets or sets from the configuration file a Boolean value that specifies whether the service credential is provisioned at the client out-of-band, or is obtained from the service to the client through a process of negotiation.</span></span></summary>
        <value><span data-ttu-id="87c94-107">サービス資格情報が、クライアントのアウトバンドで提供されるか、ネゴシエーション; のプロセスを使用してクライアントにサービスから取得される場合は true。それ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="87c94-107">true if the service credential is provisioned at the client out-of-band, or is obtained from the service to the client through a process of negotiation; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>