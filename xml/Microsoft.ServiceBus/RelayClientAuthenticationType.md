<Type Name="RelayClientAuthenticationType" FullName="Microsoft.ServiceBus.RelayClientAuthenticationType">
  <TypeSignature Language="C#" Value="public enum RelayClientAuthenticationType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RelayClientAuthenticationType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RelayClientAuthenticationType" />
  <TypeSignature Language="VB.NET" Value="Public Enum RelayClientAuthenticationType" />
  <TypeSignature Language="F#" Value="type RelayClientAuthenticationType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="RelayClientAuthenticationType", Namespace="http://schemas.microsoft.com/netservices/2009/05/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="0e347-101">メッセージを送信するときに、Azure Service Bus に Azure アクセス制御によって発行されたセキュリティ トークンを提示するサービスのクライアントが必要かどうかについて説明します。</span><span class="sxs-lookup"><span data-stu-id="0e347-101">Describes whether clients of a service are required to present a security token issued by Azure Access Control to the Azure Service Bus when sending messages.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayClientAuthenticationType None = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayClientAuthenticationType.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 1" Usage="Microsoft.ServiceBus.RelayClientAuthenticationType.None" />
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
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="0e347-102">リスナーによって指定した場合、クライアントはセキュリティ トークンを指定するは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="0e347-102">If specified by a listener, the client will not be required to provide a security token.</span></span> <span data-ttu-id="0e347-103">これは、リスナーが、エンドポイントで Azure アクセス制御の保護を放棄するオプトアウト メカニズムを表します。</span><span class="sxs-lookup"><span data-stu-id="0e347-103">This represents an opt-out mechanism with which listeners can waive the Azure Access Control protection on the endpoint.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="RelayAccessToken">
      <MemberSignature Language="C#" Value="RelayAccessToken" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.RelayClientAuthenticationType RelayAccessToken = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />
      <MemberSignature Language="VB.NET" Value="RelayAccessToken" />
      <MemberSignature Language="F#" Value="RelayAccessToken = 0" Usage="Microsoft.ServiceBus.RelayClientAuthenticationType.RelayAccessToken" />
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
        <ReturnType>Microsoft.ServiceBus.RelayClientAuthenticationType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="0e347-104">リスナーによって指定した場合、クライアントがセキュリティ トークンを指定する必要です。</span><span class="sxs-lookup"><span data-stu-id="0e347-104">If specified by a listener, the client is required to provide a security token.</span></span> </summary>
      </Docs>
    </Member>
  </Members>
</Type>