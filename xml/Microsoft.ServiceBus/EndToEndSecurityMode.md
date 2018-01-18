<Type Name="EndToEndSecurityMode" FullName="Microsoft.ServiceBus.EndToEndSecurityMode">
  <TypeSignature Language="C#" Value="public enum EndToEndSecurityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed EndToEndSecurityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.EndToEndSecurityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum EndToEndSecurityMode" />
  <TypeSignature Language="F#" Value="type EndToEndSecurityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="478c2-101">Azure Service Bus バインドのセキュリティ設定を決定し、クライアントとサービス エンドポイント間のセキュリティ関係を説明します。</span><span class="sxs-lookup"><span data-stu-id="478c2-101">Determines the security settings for an Azure Service Bus binding and describes the security relationship between the client and the service endpoint.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="Message" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndSecurityMode Message = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndSecurityMode.Message" />
      <MemberSignature Language="VB.NET" Value="Message" />
      <MemberSignature Language="F#" Value="Message = 2" Usage="Microsoft.ServiceBus.EndToEndSecurityMode.Message" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="478c2-102">セキュリティは、SOAP メッセージ セキュリティを使用して確保されます。</span><span class="sxs-lookup"><span data-stu-id="478c2-102">Security is provided using SOAP message security.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndSecurityMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndSecurityMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceBus.EndToEndSecurityMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="478c2-103">セキュリティを無効にします。</span><span class="sxs-lookup"><span data-stu-id="478c2-103">Security is disabled.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="Transport" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndSecurityMode Transport = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndSecurityMode.Transport" />
      <MemberSignature Language="VB.NET" Value="Transport" />
      <MemberSignature Language="F#" Value="Transport = 1" Usage="Microsoft.ServiceBus.EndToEndSecurityMode.Transport" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="478c2-104">トランスポート セキュリティ、通常の SSL を使用してセキュリティが提供されます。</span><span class="sxs-lookup"><span data-stu-id="478c2-104">Security is provided using a transport security, typically SSL.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="TransportWithMessageCredential">
      <MemberSignature Language="C#" Value="TransportWithMessageCredential" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.EndToEndSecurityMode TransportWithMessageCredential = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.EndToEndSecurityMode.TransportWithMessageCredential" />
      <MemberSignature Language="VB.NET" Value="TransportWithMessageCredential" />
      <MemberSignature Language="F#" Value="TransportWithMessageCredential = 3" Usage="Microsoft.ServiceBus.EndToEndSecurityMode.TransportWithMessageCredential" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="478c2-105">セキュア トランスポート (HTTPS など) は整合性、機密性、および認証を提供し、SOAP メッセージ セキュリティはクライアント認証を提供します。</span><span class="sxs-lookup"><span data-stu-id="478c2-105">A secure transport (for example, HTTPS) provides integrity, confidentiality, and authentication while SOAP message security provides client authentication.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>