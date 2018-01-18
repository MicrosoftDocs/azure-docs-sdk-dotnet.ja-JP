<Type Name="IssuerCredentials" FullName="Microsoft.Azure.KeyVault.Models.IssuerCredentials">
  <TypeSignature Language="C#" Value="public class IssuerCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerCredentials" />
  <TypeSignature Language="F#" Value="type IssuerCredentials = class" />
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
            <span data-ttu-id="ef252-101">証明書の発行者を使用する資格情報です。</span><span class="sxs-lookup"><span data-stu-id="ef252-101">The credentials to be used for the certificate issuer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ef252-102">IssuerCredentials クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ef252-102">Initializes a new instance of the IssuerCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerCredentials (string accountId = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountId, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountId As String = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerCredentials : string * string -&gt; Microsoft.Azure.KeyVault.Models.IssuerCredentials" Usage="new Microsoft.Azure.KeyVault.Models.IssuerCredentials (accountId, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountId" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountId"><span data-ttu-id="ef252-103">ユーザー名/アカウント名とアカウントの id。</span><span class="sxs-lookup"><span data-stu-id="ef252-103">The user name/account name/account id.</span></span></param>
        <param name="password"><span data-ttu-id="ef252-104">アカウント/パスワード/シークレット キー。</span><span class="sxs-lookup"><span data-stu-id="ef252-104">The password/secret/account key.</span></span></param>
        <summary>
            <span data-ttu-id="ef252-105">IssuerCredentials クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ef252-105">Initializes a new instance of the IssuerCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public string AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerCredentials.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As String" />
      <MemberSignature Language="F#" Value="member this.AccountId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerCredentials.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="account_id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef252-106">取得またはユーザー名/アカウント名とアカウント id を設定します。</span><span class="sxs-lookup"><span data-stu-id="ef252-106">Gets or sets the user name/account name/account id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerCredentials.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerCredentials.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pwd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ef252-107">取得またはアカウント/パスワード/シークレット キーを設定します。</span><span class="sxs-lookup"><span data-stu-id="ef252-107">Gets or sets the password/secret/account key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>