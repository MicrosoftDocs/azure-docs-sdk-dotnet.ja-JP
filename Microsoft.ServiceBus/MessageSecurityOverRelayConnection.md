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
    <summary><span data-ttu-id="fe80b-101">メッセージ セキュリティ バインディングのリレー接続について説明します。</span><span class="sxs-lookup"><span data-stu-id="fe80b-101">Describes the message security on a relay connection for a binding.</span></span></summary>
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
        <summary><span data-ttu-id="fe80b-102">設定または SOAP レベルでメッセージ セキュリティのために使用されるアルゴリズム スイートを取得します。</span><span class="sxs-lookup"><span data-stu-id="fe80b-102">Sets or gets the algorithm suite used for Message Security at the SOAP level.</span></span> </summary>
        <value><span data-ttu-id="fe80b-103">返します、<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />アルゴリズム スイートを格納しています。</span><span class="sxs-lookup"><span data-stu-id="fe80b-103">Returns a <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> that contains the algorithm suite.</span></span> <span data-ttu-id="fe80b-104">既定値は、Base256 です。</span><span class="sxs-lookup"><span data-stu-id="fe80b-104">The default value is Base256.</span></span></value>
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
        <summary><span data-ttu-id="fe80b-105">取得またはクライアントの認証に使用されるクライアント資格情報の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="fe80b-105">Gets or sets the type of client credential used for client authentication.</span></span></summary>
        <value><span data-ttu-id="fe80b-106">返します、<see cref="T:System.ServiceModel.MessageCredentialType" />資格情報を含むです。</span><span class="sxs-lookup"><span data-stu-id="fe80b-106">Returns a <see cref="T:System.ServiceModel.MessageCredentialType" /> that contains the credentials.</span></span> <span data-ttu-id="fe80b-107">既定は Windows です。</span><span class="sxs-lookup"><span data-stu-id="fe80b-107">The default is Windows.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>