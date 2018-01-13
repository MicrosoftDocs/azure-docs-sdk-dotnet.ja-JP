<Type Name="BasicHttpRelayMessageSecurity" FullName="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity">
  <TypeSignature Language="C#" Value="public sealed class BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BasicHttpRelayMessageSecurity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BasicHttpRelayMessageSecurity" />
  <TypeSignature Language="F#" Value="type BasicHttpRelayMessageSecurity = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>メッセージ レベルのセキュリティ設定を構成するためのプロパティを提供<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AlgorithmSuite">
      <MemberSignature Language="C#" Value="public System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.ServiceModel.Security.SecurityAlgorithmSuite AlgorithmSuite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.AlgorithmSuite" />
      <MemberSignature Language="VB.NET" Value="Public Property AlgorithmSuite As SecurityAlgorithmSuite" />
      <MemberSignature Language="F#" Value="member this.AlgorithmSuite : System.ServiceModel.Security.SecurityAlgorithmSuite with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.AlgorithmSuite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.Security.SecurityAlgorithmSuite</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" /> で使用するアルゴリズム スイートを指定します。</summary>
        <value>返します、 <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />、対称暗号化アルゴリズムとして 256 ビット高度暗号化標準 (AES) を指定します。 既定値は、Base256 です。 このプロパティを null にすることはできません。</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">値<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ClientCredentialType">
      <MemberSignature Language="C#" Value="public System.ServiceModel.BasicHttpMessageCredentialType ClientCredentialType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.ServiceModel.BasicHttpMessageCredentialType ClientCredentialType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.ClientCredentialType" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCredentialType As BasicHttpMessageCredentialType" />
      <MemberSignature Language="F#" Value="member this.ClientCredentialType : System.ServiceModel.BasicHttpMessageCredentialType with get, set" Usage="Microsoft.ServiceBus.BasicHttpRelayMessageSecurity.ClientCredentialType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ServiceModel.BasicHttpMessageCredentialType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントが認証する資格情報の種類を指定します。</summary>
        <value>返します、<see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" />のメンバーを格納している、<see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" />列挙します。 ユーザー名を既定値には.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>