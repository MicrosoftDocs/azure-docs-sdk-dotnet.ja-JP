<Type Name="UserPasswordCredential" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential">
  <TypeSignature Language="C#" Value="public sealed class UserPasswordCredential : Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UserPasswordCredential extends Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UserPasswordCredential&#xA;Inherits UserCredential" />
  <TypeSignature Language="F#" Value="type UserPasswordCredential = class&#xA;    inherit UserCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e11a2-101">ユーザー名/パスワード認証に使用される資格情報です。</span><span class="sxs-lookup"><span data-stu-id="e11a2-101">Credential used for username/password authentication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserPasswordCredential (string userName, System.Security.SecureString securePassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, class System.Security.SecureString securePassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential.#ctor(System.String,System.Security.SecureString)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String, securePassword As SecureString)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential : string * System.Security.SecureString -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential (userName, securePassword)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="securePassword" Type="System.Security.SecureString" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="e11a2-102">ユーザー アプリケーションの識別子は、代わりにトークンを要求します。</span><span class="sxs-lookup"><span data-stu-id="e11a2-102">Identifier of the user application requests token on behalf.</span></span></param>
        <param name="securePassword"><span data-ttu-id="e11a2-103">ユーザー パスワードです。</span><span class="sxs-lookup"><span data-stu-id="e11a2-103">User password.</span></span></param>
        <summary>
            <span data-ttu-id="e11a2-104">ユーザー名とパスワード資格情報を作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e11a2-104">Constructor to create credential with username and password</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserPasswordCredential (string userName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String, password As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserPasswordCredential (userName, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="e11a2-105">ユーザー アプリケーションの識別子は、代わりにトークンを要求します。</span><span class="sxs-lookup"><span data-stu-id="e11a2-105">Identifier of the user application requests token on behalf.</span></span></param>
        <param name="password"><span data-ttu-id="e11a2-106">ユーザー パスワードです。</span><span class="sxs-lookup"><span data-stu-id="e11a2-106">User password.</span></span></param>
        <summary>
            <span data-ttu-id="e11a2-107">ユーザー名とパスワード資格情報を作成するコンス トラクター</span><span class="sxs-lookup"><span data-stu-id="e11a2-107">Constructor to create credential with username and password</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>