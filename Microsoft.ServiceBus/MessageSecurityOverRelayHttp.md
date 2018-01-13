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
    <summary><see cref="T:Microsoft.ServiceBus.WSHttpRelayBinding" /> バインドのメッセージレベル セキュリティのプロパティを設定できます。</summary>
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
        <summary>SOAP レベルでのセキュリティ メッセージに使用されるアルゴリズム スイートを指定します。 </summary>
        <value><see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> を返します。</value>
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
        <summary>クライアント認証に使用されるクライアント資格情報の種類を指定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageCredentialType" />アルゴリズム スイートを格納しています。 既定値は Basic256 です。</value>
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
        <summary>派生したクラスのインスタンスかどうかを示すために、機能拡張シナリオでのみ使用<see cref="T:Microsoft.ServiceBus.MessageSecurityOverRelayHttp" />セキュリティで保護されたメッセージ交換を実行するように構成します。</summary>
        <returns>常に true を返します、派生クラスでオーバーライドされない限り、します。</returns>
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
        <summary>サービス資格情報がクライアントの帯域外で提供されるか、またはネゴシエーションのプロセスによってサービスからクライアントに取得されるかを示す値を取得または設定します。</summary>
        <value>サービス資格情報がネゴシエーション; のプロセスによって取得された場合、true を返しますそれ以外の場合は false です。 既定値は true です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>