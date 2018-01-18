<Type Name="SocketSecurityRole" FullName="Microsoft.ServiceBus.SocketSecurityRole">
  <TypeSignature Language="C#" Value="public enum SocketSecurityRole" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SocketSecurityRole extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.SocketSecurityRole" />
  <TypeSignature Language="VB.NET" Value="Public Enum SocketSecurityRole" />
  <TypeSignature Language="F#" Value="type SocketSecurityRole = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="e20c3-101">ソケットのセキュリティの役割について説明します。</span><span class="sxs-lookup"><span data-stu-id="e20c3-101">Describes the role for socket security.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole None = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 2" Usage="Microsoft.ServiceBus.SocketSecurityRole.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="e20c3-102">クライアントで設定すると、アプリケーションは暗号化されていないメッセージを送信します。</span><span class="sxs-lookup"><span data-stu-id="e20c3-102">When set on a client, the application will send unencrypted messages.</span></span> <span data-ttu-id="e20c3-103">サーバーで設定すると、アプリケーションで受け入れる両方が暗号化され、メッセージを暗号化します。</span><span class="sxs-lookup"><span data-stu-id="e20c3-103">When set on a server, the application will accept both encrypted and unencrypted messages.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="SslClient">
      <MemberSignature Language="C#" Value="SslClient" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole SslClient = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.SslClient" />
      <MemberSignature Language="VB.NET" Value="SslClient" />
      <MemberSignature Language="F#" Value="SslClient = 1" Usage="Microsoft.ServiceBus.SocketSecurityRole.SslClient" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="e20c3-104">アプリケーションは、つまり、アプリケーションが接続し、暗号化されたチャネルを使用してメッセージを送信しようとは、SSL クライアントとして識別されます。</span><span class="sxs-lookup"><span data-stu-id="e20c3-104">The application is identified as an SSL client, meaning the application will attempt to connect and send messages using an encrypted channel.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="SslServer">
      <MemberSignature Language="C#" Value="SslServer" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.SocketSecurityRole SslServer = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.SocketSecurityRole.SslServer" />
      <MemberSignature Language="VB.NET" Value="SslServer" />
      <MemberSignature Language="F#" Value="SslServer = 0" Usage="Microsoft.ServiceBus.SocketSecurityRole.SslServer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.SocketSecurityRole</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="e20c3-105">アプリケーションがセキュリティで保護されたトランスポートの接続のみを受け入れることを意味、SSL サーバーとしてアプリケーションを識別します。</span><span class="sxs-lookup"><span data-stu-id="e20c3-105">Identifies the application as an SSL server, meaning that the application will accept only a secure transport connection.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>