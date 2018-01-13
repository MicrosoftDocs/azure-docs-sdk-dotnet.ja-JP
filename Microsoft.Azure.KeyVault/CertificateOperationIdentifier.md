<Type Name="CertificateOperationIdentifier" FullName="Microsoft.Azure.KeyVault.CertificateOperationIdentifier">
  <TypeSignature Language="C#" Value="public sealed class CertificateOperationIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CertificateOperationIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.CertificateOperationIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CertificateOperationIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type CertificateOperationIdentifier = class&#xA;    inherit ObjectIdentifier" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.ObjectIdentifier</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key Vault の証明書操作の識別子。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier : string -&gt; Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">証明書の操作の識別子の識別子。 </param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateOperationIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.CertificateOperationIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateOperationIdentifier (vaultBaseUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> 資格情報コンテナーの基本 url です。 </param>
        <param name="name">証明書の名前。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCertificateOperationIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsCertificateOperationIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsCertificateOperationIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateOperationIdentifier.IsCertificateOperationIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsCertificateOperationIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsCertificateOperationIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.CertificateOperationIdentifier.IsCertificateOperationIdentifier identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">資格情報コンテナー証明書の操作の識別子。</param>
        <summary>
            資格情報コンテナー証明書の操作に識別子が属しているかどうかを確認します。
            </summary>
        <returns>資格情報コンテナー証明書の操作に識別子が属している場合は true。 False それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>