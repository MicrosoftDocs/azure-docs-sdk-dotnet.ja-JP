<Type Name="HttpRelayTransportSecurityElement" FullName="Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement">
  <TypeSignature Language="C#" Value="public sealed class HttpRelayTransportSecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpRelayTransportSecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpRelayTransportSecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type HttpRelayTransportSecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="3fbb1-101">HTTP トランスポートの認証パラメーターを制御する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="3fbb1-101">Represents a configuration element that controls authentication parameters for the HTTP transport.</span></span> <span data-ttu-id="3fbb1-102">このクラスは継承できません。</span><span class="sxs-lookup"><span data-stu-id="3fbb1-102">This class cannot be inherited.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HttpRelayTransportSecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.#ctor" />
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
    <Member MemberName="ProxyCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.HttpProxyCredentialType ProxyCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.HttpProxyCredentialType ProxyCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.ProxyCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ProxyCredentialType As HttpProxyCredentialType" />
      <MemberSignature Language="F#" Value="member this.ProxyCredentialType : System.ServiceModel.HttpProxyCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.HttpRelayTransportSecurityElement.ProxyCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("proxyCredentialType", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.ServiceModel.HttpProxyCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="3fbb1-103">取得またはプロキシに対する認証に使用するクライアントの資格情報の種類を構成ファイルから設定します。</span><span class="sxs-lookup"><span data-stu-id="3fbb1-103">Gets or sets from the configuration file the type of client credential to be used for authentication against the proxy.</span></span></summary>
        <value><span data-ttu-id="3fbb1-104">返します、<see cref="T:System.ServiceModel.HttpProxyCredentialType" />プロキシ型を格納します。</span><span class="sxs-lookup"><span data-stu-id="3fbb1-104">Returns a <see cref="T:System.ServiceModel.HttpProxyCredentialType" /> that contains the proxy type.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>