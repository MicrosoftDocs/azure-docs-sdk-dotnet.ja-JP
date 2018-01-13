<Type Name="ClientAssertionCertificate" FullName="Microsoft.Identity.Client.ClientAssertionCertificate">
  <TypeSignature Language="C#" Value="public sealed class ClientAssertionCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientAssertionCertificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ClientAssertionCertificate" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientAssertionCertificate" />
  <TypeSignature Language="F#" Value="type ClientAssertionCertificate = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クライアントのアサーションを作成するために使用する証明書を含むです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientAssertionCertificate (System.Security.Cryptography.X509Certificates.X509Certificate2 certificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientAssertionCertificate.#ctor(System.Security.Cryptography.X509Certificates.X509Certificate2)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificate As X509Certificate2)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientAssertionCertificate : System.Security.Cryptography.X509Certificates.X509Certificate2 -&gt; Microsoft.Identity.Client.ClientAssertionCertificate" Usage="new Microsoft.Identity.Client.ClientAssertionCertificate certificate" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificate" Type="System.Security.Cryptography.X509Certificates.X509Certificate2" />
      </Parameters>
      <Docs>
        <param name="certificate">資格情報として使用する証明書。</param>
        <summary>
            証明書を使用して資格情報を作成するコンス トラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientAssertionCertificate.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificate As X509Certificate2" />
      <MemberSignature Language="F#" Value="member this.Certificate : System.Security.Cryptography.X509Certificates.X509Certificate2" Usage="Microsoft.Identity.Client.ClientAssertionCertificate.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509Certificate2</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            資格情報として使用する証明書を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinKeySizeInBits">
      <MemberSignature Language="C#" Value="public static int MinKeySizeInBits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property int32 MinKeySizeInBits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientAssertionCertificate.MinKeySizeInBits" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property MinKeySizeInBits As Integer" />
      <MemberSignature Language="F#" Value="member this.MinKeySizeInBits : int" Usage="Microsoft.Identity.Client.ClientAssertionCertificate.MinKeySizeInBits" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ビット単位で取得最小 X509 証明書のキー サイズ
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>