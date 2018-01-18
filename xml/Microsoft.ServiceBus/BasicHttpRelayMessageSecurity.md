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
    <summary><span data-ttu-id="1c6c4-101">メッセージ レベルのセキュリティ設定を構成するためのプロパティを提供<see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />です。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-101">Provides properties used to configure message-level security settings for <see cref="T:Microsoft.ServiceBus.BasicHttpRelayBinding" />.</span></span>
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
        <summary><span data-ttu-id="1c6c4-102"><see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" /> で使用するアルゴリズム スイートを指定します。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-102">Specifies the algorithm suite to use with <see cref="T:Microsoft.ServiceBus.BasicHttpRelayMessageSecurity" />.</span></span></summary>
        <value><span data-ttu-id="1c6c4-103">返します、 <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />、対称暗号化アルゴリズムとして 256 ビット高度暗号化標準 (AES) を指定します。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-103">Returns a <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />, which specifies 256-bit Advanced Encryption Standard (AES) as the symmetric encryption algorithm.</span></span> <span data-ttu-id="1c6c4-104">既定値は、Base256 です。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-104">The default value is Base256.</span></span> <span data-ttu-id="1c6c4-105">このプロパティを null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-105">This property cannot be null.</span></span></value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="1c6c4-106">値<see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" />が null です。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-106">The value of <see cref="T:System.ServiceModel.Security.SecurityAlgorithmSuite" /> is null.</span></span></exception>
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
        <summary><span data-ttu-id="1c6c4-107">クライアントが認証する資格情報の種類を指定します。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-107">Specifies the type of credential with which the client authenticates.</span></span></summary>
        <value><span data-ttu-id="1c6c4-108">返します、<see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" />のメンバーを格納している、<see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" />列挙します。</span><span class="sxs-lookup"><span data-stu-id="1c6c4-108">Returns a <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> that contains a member of the <see cref="T:System.ServiceModel.BasicHttpMessageCredentialType" /> enumeration.</span></span> <span data-ttu-id="1c6c4-109">ユーザー名を既定値には.</span><span class="sxs-lookup"><span data-stu-id="1c6c4-109">The default value is UserName..</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>