<Type Name="EndToEndBasicHttpSecurityMode" FullName="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode">
  <TypeSignature Language="C#" Value="public enum EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EndToEndBasicHttpSecurityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum EndToEndBasicHttpSecurityMode" />
  <TypeSignature Language="F#" Value="type EndToEndBasicHttpSecurityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="52317-101">使用できるセキュリティのモードを指定する列挙型<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="52317-101">An enumeration type that specifies the modes of security that can be used with <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="Message" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Message = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Message" />
      <MemberSignature Language="VB.NET" Value="Message" />
      <MemberSignature Language="F#" Value="Message = 2" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Message" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="52317-102">Ws-security の SOAP メッセージ セキュリティを使用してセキュリティが提供されます。</span><span class="sxs-lookup"><span data-stu-id="52317-102">Security is provided using WS-Security SOAP message security.</span></span> <span data-ttu-id="52317-103"><see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> でシステムは、サーバー証明書を個別にクライアントに提供するように要求します。</span><span class="sxs-lookup"><span data-stu-id="52317-103">For the <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />, the system requires that the server certificate be provided to the client separately.</span></span> <span data-ttu-id="52317-104">このバインディングの有効なクライアント資格情報の種類は、ユーザー名と証明書です。</span><span class="sxs-lookup"><span data-stu-id="52317-104">The valid client credential types for this binding are UserName and Certificate.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="52317-105">メッセージは、転送中はセキュリティで保護されません。</span><span class="sxs-lookup"><span data-stu-id="52317-105">Messages are not secured during transfer.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="Transport" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode Transport = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Transport" />
      <MemberSignature Language="VB.NET" Value="Transport" />
      <MemberSignature Language="F#" Value="Transport = 1" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.Transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="52317-106">セキュリティは、HTTPS を使用して確保されます。</span><span class="sxs-lookup"><span data-stu-id="52317-106">Security is provided using HTTPS.</span></span> <span data-ttu-id="52317-107">サービスは、SSL 証明書を使用して構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="52317-107">The service must be configured with SSL certificates.</span></span> <span data-ttu-id="52317-108">SOAP メッセージは、HTTPS を使用して、全体として保護されます。</span><span class="sxs-lookup"><span data-stu-id="52317-108">The SOAP message is protected as a whole using HTTPS.</span></span> <span data-ttu-id="52317-109">サービスは、サービスの SSL 証明書を使用して、クライアントによって認証されます。</span><span class="sxs-lookup"><span data-stu-id="52317-109">The service is authenticated by the client using the service’s SSL certificate.</span></span> <span data-ttu-id="52317-110">クライアントの認証は、ClientCredentialType を通じて制御されます。</span><span class="sxs-lookup"><span data-stu-id="52317-110">The client authentication is controlled through the ClientCredentialType.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="TransportWithMessageCredential">
      <MemberSignature Language="C#" Value="TransportWithMessageCredential" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode TransportWithMessageCredential = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.TransportWithMessageCredential" />
      <MemberSignature Language="VB.NET" Value="TransportWithMessageCredential" />
      <MemberSignature Language="F#" Value="TransportWithMessageCredential = 3" Usage="Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode.TransportWithMessageCredential" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndBasicHttpSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="52317-111">整合性、機密性、およびサーバー認証は、HTTPS によって提供されます。</span><span class="sxs-lookup"><span data-stu-id="52317-111">Integrity, confidentiality and server authentication are provided by HTTPS.</span></span> <span data-ttu-id="52317-112">サービスは、証明書を使用して構成する必要があります。</span><span class="sxs-lookup"><span data-stu-id="52317-112">The service must be configured with a certificate.</span></span> <span data-ttu-id="52317-113">クライアント認証は、SOAP メッセージ セキュリティで提供されます。</span><span class="sxs-lookup"><span data-stu-id="52317-113">Client authentication is provided by means of SOAP message security.</span></span> <span data-ttu-id="52317-114">このモードは、ユーザーが資格情報 (ユーザー名または証明書) を使用して認証を行い、メッセージ転送をセキュリティで保護するために既存の HTTP が配置されている場合に適用できます。</span><span class="sxs-lookup"><span data-stu-id="52317-114">This mode is applicable when the user is authenticating with a UserName or Certificate credential and there is an existing HTTPS deployment for securing message transfer.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>