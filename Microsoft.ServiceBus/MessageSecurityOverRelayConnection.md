<Type Name="MessageSecurityOverRelayConnection" FullName="Microsoft.ServiceBus.MessageSecurityOverRelayConnection">
  <TypeSignature Language="C#" Value="public sealed class MessageSecurityOverRelayConnection" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageSecurityOverRelayConnection extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageSecurityOverRelayConnection" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayConnection = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>メッセージ セキュリティ バインディングのリレー接続について説明します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayConnection.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayConnection.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>設定または SOAP レベルでメッセージ セキュリティのために使用されるアルゴリズム スイートを取得します。 </summary>
        <value>返します、<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />アルゴリズム スイートを格納しています。 既定値は、Base256 です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayConnection.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayConnection.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはクライアントの認証に使用されるクライアント資格情報の種類を設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageCredentialType" />資格情報を含むです。 既定は Windows です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>