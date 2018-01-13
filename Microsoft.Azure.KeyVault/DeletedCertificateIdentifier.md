<Type Name="DeletedCertificateIdentifier" FullName="Microsoft.Azure.KeyVault.DeletedCertificateIdentifier">
  <TypeSignature Language="C#" Value="public sealed class DeletedCertificateIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletedCertificateIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletedCertificateIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type DeletedCertificateIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Key Vault では、証明書識別子を削除します。 別名の recoveryId します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier : string -&gt; Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">証明書が削除用の識別子。 別名が削除されないように、recoveryId を返します。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedCertificateIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.DeletedCertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedCertificateIdentifier (vaultBaseUrl, name)" />
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
        <param name="vaultBaseUrl"> 資格情報コンテナーのベース URL</param>
        <param name="name">削除済みの証明書の名前</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeletedCertificateIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsDeletedCertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDeletedCertificateIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.IsDeletedCertificateIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsDeletedCertificateIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDeletedCertificateIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.DeletedCertificateIdentifier.IsDeletedCertificateIdentifier identifier" />
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
        <param name="identifier">資格情報コンテナーの証明書識別子です。</param>
        <summary>
            識別子が削除された KeyVault 証明書の有効な識別子であるかどうかを確認します。
            </summary>
        <returns>識別子は有効な場合は true。 KeyVault は、証明書を削除します。 False それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>