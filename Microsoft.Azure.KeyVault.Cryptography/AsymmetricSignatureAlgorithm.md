<Type Name="AsymmetricSignatureAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class AsymmetricSignatureAlgorithm : Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AsymmetricSignatureAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AsymmetricSignatureAlgorithm&#xA;Inherits SignatureAlgorithm" />
  <TypeSignature Language="F#" Value="type AsymmetricSignatureAlgorithm = class&#xA;    inherit SignatureAlgorithm" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.SignatureAlgorithm</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            抽象非対称署名アルゴリズム
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AsymmetricSignatureAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSignatureTransform">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform (System.Security.Cryptography.AsymmetricAlgorithm key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform CreateSignatureTransform(class System.Security.Cryptography.AsymmetricAlgorithm key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricSignatureAlgorithm.CreateSignatureTransform(System.Security.Cryptography.AsymmetricAlgorithm)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateSignatureTransform (key As AsymmetricAlgorithm) As ISignatureTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateSignatureTransform : System.Security.Cryptography.AsymmetricAlgorithm -&gt; Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform" Usage="asymmetricSignatureAlgorithm.CreateSignatureTransform key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Cryptography.ISignatureTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Security.Cryptography.AsymmetricAlgorithm" />
      </Parameters>
      <Docs>
        <param name="key">使用する非対称キー。</param>
        <summary>
            署名するかを確認するために使用する署名変換の実装を作成します。
            </summary>
        <returns>ISignatureTransform 実装します。</returns>
        <remarks>トランス フォーム実装では、「そのまま利用」指定された AsymmetricAlgorithm です。呼び出し元呼び出さないでください。 Dispose、AsymmetricAlgorithm にトランス フォームの実装の使用が完了するまでです。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>