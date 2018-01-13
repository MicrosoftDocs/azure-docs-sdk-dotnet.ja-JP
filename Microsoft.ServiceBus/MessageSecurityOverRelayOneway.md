<Type Name="MessageSecurityOverRelayOneway" FullName="Microsoft.ServiceBus.MessageSecurityOverRelayOneway">
  <TypeSignature Language="C#" Value="public sealed class MessageSecurityOverRelayOneway" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MessageSecurityOverRelayOneway extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.MessageSecurityOverRelayOneway" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessageSecurityOverRelayOneway" />
  <TypeSignature Language="F#" Value="type MessageSecurityOverRelayOneway = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Azure Service Bus リレーを経由する一方向接続のメッセージ セキュリティ。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayOneway.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または SOAP レベルでメッセージを保護するために使用するアルゴリズム スイートを設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />アルゴリズム スイートを格納します。 既定では Basic256 で、対称暗号化アルゴリズムとして 256 ビット高度暗号化標準 (AES) を指定します。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">値、<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.MessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.MessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As MessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.MessageCredentialType with get, set" Usage="Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.MessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または SOAP レベルのサービスに対する認証にクライアントを使用して、クライアント資格情報の種類を設定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.MessageCredentialType" />資格情報の種類を格納しています。 既定値は、証明書です。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException"><see cref="P:Microsoft.ServiceBus.MessageSecurityOverRelayOneway.ClientCredentialType" /> の値が有効な <see cref="T:System.ServiceModel.MessageCredentialType" /> ではありません。</exception>
      </Docs>
    </Member>
  </Members>
</Type>