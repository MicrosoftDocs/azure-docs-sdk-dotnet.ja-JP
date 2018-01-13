<Type Name="MessageSecurityOverRelayOnewayElement" FullName="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement">
  <TypeSignature Language="C#" Value="public sealed class MessageSecurityOverRelayOnewayElement : System.Configuration.ConfigurationElement" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageSecurityOverRelayOnewayElement extends System.Configuration.ConfigurationElement" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageSecurityOverRelayOnewayElement&#xA;Inherits ConfigurationElement" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayOnewayElement = class&#xA;    inherit ConfigurationElement" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Configuration.ConfigurationElement</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Azure Service Bus のリレーに一方向のメッセージのメッセージ セキュリティについて説明する構成要素。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MessageSecurityOverRelayOnewayElement ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.#ctor" />
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
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.AlgorithmSuite" />
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
        <summary>取得または設定の構成ファイル、メッセージの暗号化とキー ラップ アルゴリズムが一方向のメッセージをセキュリティで保護するために使用します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />アルゴリズム スイートを格納しています。 既定値は、Base256 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.ClientCredentialType" />
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
        <summary>取得または構成ファイルからメッセージ ベースのセキュリティまたは TransportWithMessageCredential を使用してクライアント認証を実行するときに使用される資格情報の種類を設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageCredentialType" />メッセージ資格情報の種類を格納しています。 既定は Windows です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="protected override System.Configuration.ConfigurationPropertyCollection Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Configuration.ConfigurationPropertyCollection Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.Properties" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides ReadOnly Property Properties As ConfigurationPropertyCollection" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Configuration.ConfigurationPropertyCollection" Usage="Microsoft.ServiceBus.Configuration.MessageSecurityOverRelayOnewayElement.Properties" />
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
  </Members>
</Type>