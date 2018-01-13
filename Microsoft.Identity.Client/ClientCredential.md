<Type Name="ClientCredential" FullName="Microsoft.Identity.Client.ClientCredential">
  <TypeSignature Language="C#" Value="public sealed class ClientCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ClientCredential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientCredential" />
  <TypeSignature Language="F#" Value="type ClientCredential = class" />
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
            秘密のクライアント アプリケーションでは使用するためのものです。 開発者はクライアント シークレットまたはそのアプリケーションのクライアント アサーションの証明書のいずれかを渡すにできます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCredential (Microsoft.Identity.Client.ClientAssertionCertificate certificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Identity.Client.ClientAssertionCertificate certificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientCredential.#ctor(Microsoft.Identity.Client.ClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (certificate As ClientAssertionCertificate)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientCredential : Microsoft.Identity.Client.ClientAssertionCertificate -&gt; Microsoft.Identity.Client.ClientCredential" Usage="new Microsoft.Identity.Client.ClientCredential certificate" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="certificate" Type="Microsoft.Identity.Client.ClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="certificate">トークンを要求したクライアントの証明書。</param>
        <summary>
            コンス トラクター クライアント アサーションを提供する証明書
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCredential (string secret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string secret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientCredential.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientCredential : string -&gt; Microsoft.Identity.Client.ClientCredential" Usage="new Microsoft.Identity.Client.ClientCredential secret" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="secret">トークンを要求したクライアントのシークレット。</param>
        <summary>
            クライアント シークレットを提供するコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>