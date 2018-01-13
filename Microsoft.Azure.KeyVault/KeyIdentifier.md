<Type Name="KeyIdentifier" FullName="Microsoft.Azure.KeyVault.KeyIdentifier">
  <TypeSignature Language="C#" Value="public sealed class KeyIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type KeyIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Key Vault のキー識別子。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyIdentifier : string -&gt; Microsoft.Azure.KeyVault.KeyIdentifier" Usage="new Microsoft.Azure.KeyVault.KeyIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">キー オブジェクトの識別子</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyIdentifier (string vaultBaseUrl, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.KeyIdentifier" Usage="new Microsoft.Azure.KeyVault.KeyIdentifier (vaultBaseUrl, name, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> 資格情報コンテナーのベース URL</param>
        <param name="name"> キーの名前です。 </param>
        <param name="version"> キーのバージョン。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsKeyIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsKeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsKeyIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.IsKeyIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsKeyIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsKeyIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.KeyIdentifier.IsKeyIdentifier identifier" />
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
        <param name="identifier">資格情報コンテナーのキー識別子。</param>
        <summary>
            資格情報コンテナー キー識別子が属しているかどうかを確認します。
            </summary>
        <returns>識別子が、キー コンテナー キーに属している場合は true。 False それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>