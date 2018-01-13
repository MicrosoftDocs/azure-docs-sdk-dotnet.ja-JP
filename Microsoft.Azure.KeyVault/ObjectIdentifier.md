<Type Name="ObjectIdentifier" FullName="Microsoft.Azure.KeyVault.ObjectIdentifier">
  <TypeSignature Language="C#" Value="public class ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ObjectIdentifier extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public Class ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type ObjectIdentifier = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Key Vault のオブジェクト識別子です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier (string collection, string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string collection, string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (collection As String, identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.ObjectIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.ObjectIdentifier" Usage="new Microsoft.Azure.KeyVault.ObjectIdentifier (collection, identifier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="collection">オブジェクト コレクション例: 'keys'、'シークレット' と '証明書'。</param>
        <param name="identifier">資格情報コンテナー オブジェクトの識別子です。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ObjectIdentifier (string vaultBaseUrl, string collection, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string collection, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (vaultBaseUrl As String, collection As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.ObjectIdentifier : string * string * string * string -&gt; Microsoft.Azure.KeyVault.ObjectIdentifier" Usage="new Microsoft.Azure.KeyVault.ObjectIdentifier (vaultBaseUrl, collection, name, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> 資格情報コンテナーのベース URL</param>
        <param name="collection">オブジェクト コレクション例: 'keys'、'シークレット' と '証明書'。</param>
        <param name="name">オブジェクト名。</param>
        <param name="version"> オブジェクトのバージョン。</param>
        <summary>
            コンストラクターです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseIdentifier">
      <MemberSignature Language="C#" Value="public string BaseIdentifier { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.BaseIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseIdentifier As String" />
      <MemberSignature Language="F#" Value="member this.BaseIdentifier : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.BaseIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトの基本識別子では、オブジェクトのバージョンは含まれません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトの識別子には、オブジェクトのバージョンが含まれています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsObjectIdentifier">
      <MemberSignature Language="C#" Value="protected static bool IsObjectIdentifier (string collection, string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig bool IsObjectIdentifier(string collection, string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.IsObjectIdentifier(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function IsObjectIdentifier (collection As String, identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsObjectIdentifier : string * string -&gt; bool" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.IsObjectIdentifier (collection, identifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="collection" Type="System.String" />
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="collection">オブジェクト コレクション例: 'keys'、'シークレット' と '証明書'。</param>
        <param name="identifier">資格情報コンテナー オブジェクトの識別子です。</param>
        <summary>
            識別子が、資格情報コンテナー オブジェクトに属するかどうかを確認します。
            </summary>
        <returns>資格情報コンテナー オブジェクトに識別子が属している場合は true。 False それ以外の場合。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトの名前。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.ObjectIdentifier.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="objectIdentifier.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Vault">
      <MemberSignature Language="C#" Value="public string Vault { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Vault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Vault" />
      <MemberSignature Language="VB.NET" Value="Public Property Vault As String" />
      <MemberSignature Language="F#" Value="member this.Vault : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Vault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトが含まれる資格情報コンテナー
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VaultWithoutScheme">
      <MemberSignature Language="C#" Value="public string VaultWithoutScheme { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultWithoutScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.VaultWithoutScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultWithoutScheme As String" />
      <MemberSignature Language="F#" Value="member this.VaultWithoutScheme : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.VaultWithoutScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            スキームのない資格情報コンテナーの URL
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.ObjectIdentifier.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.KeyVault.ObjectIdentifier.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            オブジェクトのバージョン。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>