<Type Name="RelayEventSubscriberAuthenticationType" FullName="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType">
  <TypeSignature Language="C#" Value="public enum RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayEventSubscriberAuthenticationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayEventSubscriberAuthenticationType" />
  <TypeSignature Language="F#" Value="type RelayEventSubscriberAuthenticationType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="76a23-101">について説明するかどうかのサブスクライバー、<see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" />メッセージを送信するときに、Azure Service Bus サービスに、Azure アクセス制御サービスによって発行されたセキュリティ トークンを提示する必要があります。</span><span class="sxs-lookup"><span data-stu-id="76a23-101">Describes whether subscribers to a <see cref="T:Microsoft.ServiceBus.NetEventRelayBinding" /> are required to present a security token issued by the Azure Access Control service to the Azure Service Bus service when sending messages.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="76a23-102">NetEventRelay サブスクライバーで指定された、クライアントはリレー アクセス トークンを指定する必要ありません。</span><span class="sxs-lookup"><span data-stu-id="76a23-102">If specified by a NetEventRelay subscriber, the client will not be required to provide a relay access token.</span></span> <span data-ttu-id="76a23-103">これは、使用するリスナーはエンドポイントで Azure アクセス制御の保護を放棄し、独自のアクセス制御を実行のオプトアウト メカニズムを表します。</span><span class="sxs-lookup"><span data-stu-id="76a23-103">This represents an opt-out mechanism with which listeners can waive the Azure Access Control protection on the endpoint and perform their own access control.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="RelayAccessToken">
      <MemberSignature Language="C#" Value="RelayAccessToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType RelayAccessToken = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.RelayAccessToken" />
      <MemberSignature Language="VB.NET" Value="RelayAccessToken" />
      <MemberSignature Language="F#" Value="RelayAccessToken = 0" Usage="Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType.RelayAccessToken" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RelayEventSubscriberAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="76a23-104">NetEventRelay リスナーによって指定した場合、クライアントはリレー アクセス トークンを指定するために必要です。</span><span class="sxs-lookup"><span data-stu-id="76a23-104">If specified by a NetEventRelay listener, the client is required to provide a relay access token.</span></span> </summary>
      </Docs>
    </Member>
  </Members>
</Type>