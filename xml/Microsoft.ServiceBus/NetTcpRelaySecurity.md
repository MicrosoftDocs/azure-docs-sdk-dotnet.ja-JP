<Type Name="NetTcpRelaySecurity" FullName="Microsoft.ServiceBus.NetTcpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class NetTcpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NetTcpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NetTcpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NetTcpRelaySecurity" />
  <TypeSignature Language="F#" Value="type NetTcpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="bd5d2-101"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントで使用される、トランスポート レベルとメッセージ レベルのセキュリティの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-101">Specifies the types of transport-level and message-level security used by an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.MessageSecurityOverRelayConnection Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As MessageSecurityOverRelayConnection" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.ServiceBus.MessageSecurityOverRelayConnection" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.MessageSecurityOverRelayConnection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5d2-102"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたサービスの、メッセージ レベルのセキュリティ要件の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-102">Gets the type of message-level security requirements for a service configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span> </summary>
        <value><span data-ttu-id="bd5d2-103">返します、<see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" />エンドポイントのメッセージ レベルのセキュリティ要件の種類を示すです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-103">Returns a <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayConnection" /> that indicates the type of message-level security requirements for an endpoint.</span></span> <span data-ttu-id="bd5d2-104">既定のセキュリティ設定は、:、; ユーザー名の ClientCredentialTypeAlgorithmSuite Basic256 のです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-104">The default security settings are: a ClientCredentialType of UserName; and an AlgorithmSuite of Basic256.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndSecurityMode with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5d2-105"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントで使用されるセキュリティ レベル (メッセージ レベルまたはトランスポート レベル) を取得するかどうかを設定します。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-105">Gets or sets whether message-level and transport-level security are used by an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="bd5d2-106">返します、<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />エンドポイントによるメッセージ レベルまたはトランスポート レベルのセキュリティが使用されるかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-106">Returns an <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> that indicates whether message-level or transport-level security is used by an endpoint.</span></span> <span data-ttu-id="bd5d2-107">既定値は、Transport です。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-107">The default value is Transport.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="bd5d2-108">値が有効な<see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" />フィールドです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-108">The value is not a valid <see cref="T:Microsoft.ServiceBus.EndToEndSecurityMode" /> field.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5d2-109">取得またはリレー クライアントの認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-109">Gets or sets the relay client authentication type.</span></span></summary>
        <value><span data-ttu-id="bd5d2-110">返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-110">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="bd5d2-111">値が有効な<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />フィールドです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-111">The value is not a valid <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> field.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.TcpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.TcpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As TcpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.TcpRelayTransportSecurity" Usage="Microsoft.ServiceBus.NetTcpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="bd5d2-112"><see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" /> を使用して構成されたエンドポイントの、メッセージ レベルのセキュリティ要件の種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-112">Gets the type of message-level security requirements for an endpoint configured with a <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="bd5d2-113">返します、<see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" />エンドポイントのトランスポート レベルのセキュリティ要件の種類を示すです。</span><span class="sxs-lookup"><span data-stu-id="bd5d2-113">Returns a <see cref="T:Microsoft.ServiceBus.TcpRelayTransportSecurity" /> that indicates the type of transport-level security requirements for an endpoint.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>