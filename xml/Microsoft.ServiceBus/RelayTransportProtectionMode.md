<Type Name="RelayTransportProtectionMode" FullName="Microsoft.ServiceBus.RelayTransportProtectionMode">
  <TypeSignature Language="C#" Value="public enum RelayTransportProtectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayTransportProtectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayTransportProtectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayTransportProtectionMode" />
  <TypeSignature Language="F#" Value="type RelayTransportProtectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RelayTransportProtectionMode", Namespace="http://schemas.microsoft.com/netservices/2009/05/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="f8a23-101">トランスポートのリレーの保護の種類を説明します。</span><span class="sxs-lookup"><span data-stu-id="f8a23-101">Describes the types of protection on a transport relay.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EndToEnd">
      <MemberSignature Language="C#" Value="EndToEnd" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayTransportProtectionMode EndToEnd = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayTransportProtectionMode.EndToEnd" />
      <MemberSignature Language="VB.NET" Value="EndToEnd" />
      <MemberSignature Language="F#" Value="EndToEnd = 2" Usage="Microsoft.ServiceBus.RelayTransportProtectionMode.EndToEnd" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayTransportProtectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="f8a23-102">サービス アプリケーションとクライアント アプリケーションの両方には、セキュリティがある場合があります。</span><span class="sxs-lookup"><span data-stu-id="f8a23-102">Both the service application and client application must have security.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="ListenerOnly">
      <MemberSignature Language="C#" Value="ListenerOnly" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayTransportProtectionMode ListenerOnly = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayTransportProtectionMode.ListenerOnly" />
      <MemberSignature Language="VB.NET" Value="ListenerOnly" />
      <MemberSignature Language="F#" Value="ListenerOnly = 1" Usage="Microsoft.ServiceBus.RelayTransportProtectionMode.ListenerOnly" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayTransportProtectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="f8a23-103">サービス アプリケーションのセキュリティをいる必要があります。クライアント アプリケーションは、いずれかが必要はありません。</span><span class="sxs-lookup"><span data-stu-id="f8a23-103">The service application must have security; a client application is not required to have any.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayTransportProtectionMode None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayTransportProtectionMode.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.ServiceBus.RelayTransportProtectionMode.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayTransportProtectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="f8a23-104">セキュリティを無効にします。</span><span class="sxs-lookup"><span data-stu-id="f8a23-104">Security is disabled.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>