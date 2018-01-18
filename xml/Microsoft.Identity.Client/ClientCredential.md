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
            <span data-ttu-id="c978d-101">秘密のクライアント アプリケーションでは使用するためのものです。</span><span class="sxs-lookup"><span data-stu-id="c978d-101">Meant to be used in confidential client applications.</span></span> <span data-ttu-id="c978d-102">開発者はクライアント シークレットまたはそのアプリケーションのクライアント アサーションの証明書のいずれかを渡すにできます。</span><span class="sxs-lookup"><span data-stu-id="c978d-102">Allows developers to pass either client secret or client assertion certificate of their application.</span></span>
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
        <param name="certificate"><span data-ttu-id="c978d-103">トークンを要求したクライアントの証明書。</span><span class="sxs-lookup"><span data-stu-id="c978d-103">certificate of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="c978d-104">コンス トラクター クライアント アサーションを提供する証明書</span><span class="sxs-lookup"><span data-stu-id="c978d-104">Constructor provide client assertion certificate</span></span>
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
        <param name="secret"><span data-ttu-id="c978d-105">トークンを要求したクライアントのシークレット。</span><span class="sxs-lookup"><span data-stu-id="c978d-105">Secret of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="c978d-106">クライアント シークレットを提供するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="c978d-106">Constructor to provide client secret</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>