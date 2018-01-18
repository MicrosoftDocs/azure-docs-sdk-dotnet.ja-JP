<Type Name="TcpRelayTransportSecurityElement" FullName="Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement">
  <TypeSignature Language="C#" Value="public sealed class TcpRelayTransportSecurityElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TcpRelayTransportSecurityElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TcpRelayTransportSecurityElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type TcpRelayTransportSecurityElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="02b4d-101">Azure Service Bus リレーを通じた TCP トランスポートのサービスのセキュリティを構成する構成要素を表します。</span><span class="sxs-lookup"><span data-stu-id="02b4d-101">Represents a configuration element that configures the security for a TCP transport service through the Azure Service Bus relay.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TcpRelayTransportSecurityElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement.#ctor" />
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
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement.Properties" />
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
            <span data-ttu-id="02b4d-102">プロパティのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="02b4d-102">Gets the collection of properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Net.Security.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.Security.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Net.Security.ProtectionLevel with get, set" Usage="Microsoft.ServiceBus.Configuration.TcpRelayTransportSecurityElement.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Configuration.ConfigurationProperty("protectionLevel", DefaultValue=Mono.Cecil.CustomAttributeArgument)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Security.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="02b4d-103">取得または TCP リレーのトランスポート セキュリティ レベルを含む XML 値を設定します。</span><span class="sxs-lookup"><span data-stu-id="02b4d-103">Gets or sets an XML value containing the transport security level for a TCP relay.</span></span></summary>
        <value><span data-ttu-id="02b4d-104">返します、<see cref="T:System.Net.Security.ProtectionLevel" />トランスポートのセキュリティ レベルを格納しています。</span><span class="sxs-lookup"><span data-stu-id="02b4d-104">Returns a <see cref="T:System.Net.Security.ProtectionLevel" /> that contains the transport security level.</span></span> <span data-ttu-id="02b4d-105">既定値は EncryptAndSign です。</span><span class="sxs-lookup"><span data-stu-id="02b4d-105">The default value is EncryptAndSign.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>