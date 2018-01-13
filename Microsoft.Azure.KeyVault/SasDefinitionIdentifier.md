<Type Name="SasDefinitionIdentifier" FullName="Microsoft.Azure.KeyVault.SasDefinitionIdentifier">
  <TypeSignature Language="C#" Value="public sealed class SasDefinitionIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SasDefinitionIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.SasDefinitionIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SasDefinitionIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type SasDefinitionIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Key Vault ストレージの SAS 定義識別子です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier : string -&gt; Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">記憶域 SAS の資格情報コンテナー定義識別子です。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SasDefinitionIdentifier (string vaultBaseUrl, string storageAccountName, string sasDefinitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string storageAccountName, string sasDefinitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, storageAccountName As String, sasDefinitionName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.SasDefinitionIdentifier" Usage="new Microsoft.Azure.KeyVault.SasDefinitionIdentifier (vaultBaseUrl, storageAccountName, sasDefinitionName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">資格情報コンテナーの基本 URL です。</param>
        <param name="storageAccountName">ストレージ アカウントの名前。</param>
        <param name="sasDefinitionName">記憶域の SAS の定義の名前。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSasDefinitionIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsSasDefinitionIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsSasDefinitionIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.IsSasDefinitionIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsSasDefinitionIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsSasDefinitionIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.SasDefinitionIdentifier.IsSasDefinitionIdentifier identifier" />
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
        <param name="identifier">記憶域 SAS の資格情報コンテナー定義識別子です。</param>
        <summary>
            資格情報コンテナーのキー記憶域 SAS 定義に識別子が属しているかどうかを確認します。
            </summary>
        <returns>資格情報コンテナーのキー記憶域 SAS 定義に識別子が属している場合は true。 False それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccount">
      <MemberSignature Language="C#" Value="public string StorageAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.SasDefinitionIdentifier.StorageAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccount As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccount : string with get, set" Usage="Microsoft.Azure.KeyVault.SasDefinitionIdentifier.StorageAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>