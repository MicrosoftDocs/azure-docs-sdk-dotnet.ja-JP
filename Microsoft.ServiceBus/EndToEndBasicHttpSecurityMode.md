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
    <summary>使用できるセキュリティのモードを指定する列挙型<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。 </summary>
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
        <summary>Ws-security の SOAP メッセージ セキュリティを使用してセキュリティが提供されます。 <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" /> でシステムは、サーバー証明書を個別にクライアントに提供するように要求します。 このバインディングの有効なクライアント資格情報の種類は、ユーザー名と証明書です。</summary>
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
        <summary>メッセージは、転送中はセキュリティで保護されません。 </summary>
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
        <summary>セキュリティは、HTTPS を使用して確保されます。 サービスは、SSL 証明書を使用して構成する必要があります。 SOAP メッセージは、HTTPS を使用して、全体として保護されます。 サービスは、サービスの SSL 証明書を使用して、クライアントによって認証されます。 クライアントの認証は、ClientCredentialType を通じて制御されます。</summary>
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
        <summary>整合性、機密性、およびサーバー認証は、HTTPS によって提供されます。 サービスは、証明書を使用して構成する必要があります。 クライアント認証は、SOAP メッセージ セキュリティで提供されます。 このモードは、ユーザーが資格情報 (ユーザー名または証明書) を使用して認証を行い、メッセージ転送をセキュリティで保護するために既存の HTTP が配置されている場合に適用できます。</summary>
      </Docs>
    </Member>
  </Members>
</Type>