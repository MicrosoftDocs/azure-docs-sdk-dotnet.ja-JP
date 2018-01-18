<Type Name="MessageSecurityOverRelayHttp" FullName="Microsoft.ServiceBus.MessageSecurityOverRelayHttp">
  <TypeSignature Language="C#" Value="public class MessageSecurityOverRelayHttp" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MessageSecurityOverRelayHttp extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />
  <TypeSignature Language="VB.NET" Value="Public Class MessageSecurityOverRelayHttp" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayHttp = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="dce00-101"><see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> バインドのメッセージレベル セキュリティのプロパティを設定できます。</span><span class="sxs-lookup"><span data-stu-id="dce00-101">Enables setting message-level security properties on the <see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> binding.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dce00-102">SOAP レベルでのセキュリティ メッセージに使用されるアルゴリズム スイートを指定します。</span><span class="sxs-lookup"><span data-stu-id="dce00-102">Specifies the algorithm suite used for security messages at the SOAP level.</span></span> </summary>
        <value><span data-ttu-id="dce00-103"><see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="dce00-103">Returns <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dce00-104">クライアント認証に使用されるクライアント資格情報の種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="dce00-104">Specifies the type of client credential used for client authentication.</span></span></summary>
        <value><span data-ttu-id="dce00-105">返します、<see cref="T:System.ServiceModel.MessageCredentialType" />アルゴリズム スイートを格納しています。</span><span class="sxs-lookup"><span data-stu-id="dce00-105">Returns a <see cref="T:System.ServiceModel.MessageCredentialType" /> that contains the algorithm suite.</span></span> <span data-ttu-id="dce00-106">既定値は Basic256 です。</span><span class="sxs-lookup"><span data-stu-id="dce00-106">The default is Basic256.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSecureConversationEnabled">
      <MemberSignature Language="C#" Value="protected virtual bool IsSecureConversationEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsSecureConversationEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.IsSecureConversationEnabled" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function IsSecureConversationEnabled () As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecureConversationEnabled : unit -&gt; bool&#xA;override this.IsSecureConversationEnabled : unit -&gt; bool" Usage="messageSecurityOverRelayHttp.IsSecureConversationEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="dce00-107">派生したクラスのインスタンスかどうかを示すために、機能拡張シナリオでのみ使用<see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />セキュリティで保護されたメッセージ交換を実行するように構成します。</span><span class="sxs-lookup"><span data-stu-id="dce00-107">Only used in extensibility scenarios to indicate whether an instance of a class derived from <see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" /> is configured to perform secure conversation.</span></span></summary>
        <returns><span data-ttu-id="dce00-108">常に true を返します、派生クラスでオーバーライドされない限り、します。</span><span class="sxs-lookup"><span data-stu-id="dce00-108">Always returns true, unless overridden in a derived class.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NegotiateServiceCredential">
      <MemberSignature Language="C#" Value="public bool NegotiateServiceCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool NegotiateServiceCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayHttp.NegotiateServiceCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property NegotiateServiceCredential As Boolean" />
      <MemberSignature Language="F#" Value="member this.NegotiateServiceCredential : bool with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayHttp.NegotiateServiceCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="dce00-109">サービス資格情報がクライアントの帯域外で提供されるか、またはネゴシエーションのプロセスによってサービスからクライアントに取得されるかを示す値を取得または設定します。</span><span class="sxs-lookup"><span data-stu-id="dce00-109">Gets or sets a value that indicates whether the service credential is provisioned at the client out of band or is obtained from the service through a process of negotiation.</span></span></summary>
        <value><span data-ttu-id="dce00-110">サービス資格情報がネゴシエーション; のプロセスによって取得された場合、true を返しますそれ以外の場合は false です。</span><span class="sxs-lookup"><span data-stu-id="dce00-110">Returns true if service credential is obtained through a process of negotiation; otherwise, false.</span></span> <span data-ttu-id="dce00-111">既定値は true です。</span><span class="sxs-lookup"><span data-stu-id="dce00-111">The default is true.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>