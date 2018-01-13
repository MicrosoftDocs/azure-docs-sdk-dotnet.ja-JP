<Type Name="PrivateRegistryCredentials" FullName="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials">
  <TypeSignature Language="C#" Value="public class PrivateRegistryCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PrivateRegistryCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class PrivateRegistryCredentials" />
  <TypeSignature Language="F#" Value="type PrivateRegistryCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            プライベート リポジトリにコンテナー イメージにアクセスする資格情報。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            PrivateRegistryCredentials クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PrivateRegistryCredentials (string username, string password = null, Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string username, string password, class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference passwordSecretReference) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (username As String, Optional password As String = null, Optional passwordSecretReference As KeyVaultSecretReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials : string * string * Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference -&gt; Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials" Usage="new Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials (username, password, passwordSecretReference)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="passwordSecretReference" Type="Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference" />
      </Parameters>
      <Docs>
        <param name="username">ログインするユーザー名。</param>
        <param name="password">ログインのパスワード。</param>
        <param name="passwordSecretReference">Key Vault シークレットのパスワードの場所を指定します。</param>
        <summary>
            PrivateRegistryCredentials クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはログインにパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            パスワードまたは passwordSecretReference のいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordSecretReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference PasswordSecretReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberSignature Language="VB.NET" Value="Public Property PasswordSecretReference As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.PasswordSecretReference : Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.PasswordSecretReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="passwordSecretReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、Key Vault シークレットであると、パスワードの場所を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ユーザーが KeyVault と統合するバッチ AI サービスに渡すし、Azure KeyVault でそのシークレットを格納できます。 パスワードまたは passwordSecretReference のいずれかを指定する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはログインにユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.PrivateRegistryCredentials.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="privateRegistryCredentials.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>