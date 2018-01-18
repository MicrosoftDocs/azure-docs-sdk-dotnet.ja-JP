<Type Name="WebHttpRelaySecurity" FullName="Microsoft.ServiceBus.WebHttpRelaySecurity">
  <TypeSignature Language="C#" Value="public sealed class WebHttpRelaySecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WebHttpRelaySecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.WebHttpRelaySecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WebHttpRelaySecurity" />
  <TypeSignature Language="F#" Value="type WebHttpRelaySecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="c7d04-101">HTTP 要求を受信するために構成するサービス エンドポイントで使用できるセキュリティの種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="c7d04-101">Specifies the types of security available to a service endpoint configured to receive HTTP requests.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Mode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.EndToEndWebHttpSecurityMode Mode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberSignature Language="VB.NET" Value="Public Property Mode As EndToEndWebHttpSecurityMode" />
      <MemberSignature Language="F#" Value="member this.Mode : Microsoft.ServiceBus.EndToEndWebHttpSecurityMode with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Mode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.EndToEndWebHttpSecurityMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c7d04-102"><see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" /> を伴う HTTP 要求を受信するために構成されるエンドポイントによって使用されるセキュリティのモードを、取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="c7d04-102">Gets or sets the mode of security that is used by an endpoint configured to receive HTTP requests with a <see cref="T:Microsoft.ServiceBus.WebHttpRelayBinding" />.</span></span></summary>
        <value><span data-ttu-id="c7d04-103">返します、<see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" />エンドポイントによってトランスポート レベルのセキュリティ、資格情報専用、またはセキュリティが使用されるかどうかを示すです。</span><span class="sxs-lookup"><span data-stu-id="c7d04-103">Returns a <see cref="T:Microsoft.ServiceBus.EndToEndWebHttpSecurityMode" /> that indicates whether transport-level security, credential only, or no security is used by an endpoint.</span></span> <span data-ttu-id="c7d04-104">既定値は None です。</span><span class="sxs-lookup"><span data-stu-id="c7d04-104">The default value is None.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><span data-ttu-id="c7d04-105">値は、有効な EndToEndWebHttpSecurityMode ではありません。</span><span class="sxs-lookup"><span data-stu-id="c7d04-105">The value is not a valid EndToEndWebHttpSecurityMode.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RelayClientAuthenticationType">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayClientAuthenticationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberSignature Language="VB.NET" Value="Public Property RelayClientAuthenticationType As RelayClientAuthenticationType" />
      <MemberSignature Language="F#" Value="member this.RelayClientAuthenticationType : Microsoft.ServiceBus.RelayClientAuthenticationType with get, set" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.RelayClientAuthenticationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c7d04-106">取得またはサービス クライアントによって使用されるリレー クライアント認証の種類を設定します。</span><span class="sxs-lookup"><span data-stu-id="c7d04-106">Gets or sets the relay client authentication type used by the service client.</span></span></summary>
        <value><span data-ttu-id="c7d04-107">返します、<see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />リレー クライアントの認証の種類を格納しています。</span><span class="sxs-lookup"><span data-stu-id="c7d04-107">Returns a <see cref="T:Microsoft.ServiceBus.RelayClientAuthenticationType" /> that contains the relay client authentication type.</span></span> <span data-ttu-id="c7d04-108">既定値は、RelayClientAuthenticationType.RelayAccessToken です。</span><span class="sxs-lookup"><span data-stu-id="c7d04-108">The default value is RelayClientAuthenticationType.RelayAccessToken.</span></span> </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transport">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.HttpRelayTransportSecurity Transport { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.HttpRelayTransportSecurity Transport" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Transport As HttpRelayTransportSecurity" />
      <MemberSignature Language="F#" Value="member this.Transport : Microsoft.ServiceBus.HttpRelayTransportSecurity" Usage="Microsoft.ServiceBus.WebHttpRelaySecurity.Transport" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.HttpRelayTransportSecurity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="c7d04-109">取得または、バインディングのトランスポート レベルのセキュリティ設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="c7d04-109">Gets or sets the Transport-level security settings for a binding.</span></span></summary>
        <value><span data-ttu-id="c7d04-110">返します、<see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" />バインディングを格納しています。</span><span class="sxs-lookup"><span data-stu-id="c7d04-110">Returns a <see cref="T:Microsoft.ServiceBus.HttpRelayTransportSecurity" /> that contains the binding.</span></span> <span data-ttu-id="c7d04-111">既定値の設定は、ClientCredentialType が [なし]、ProxyCredentialType が [なし]、およびレルム =""です。</span><span class="sxs-lookup"><span data-stu-id="c7d04-111">The default values set are a ClientCredentialType of None, a ProxyCredentialType of None, and Realm = "".</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>