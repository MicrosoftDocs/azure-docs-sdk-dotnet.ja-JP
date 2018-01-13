<Type Name="AuthenticationContextIntegratedAuthExtensions" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions">
  <TypeSignature Language="C#" Value="public static class AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AuthenticationContextIntegratedAuthExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="F#" Value="type AuthenticationContextIntegratedAuthExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ユーザー名/パスワードのフローをサポートする拡張クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (this Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext ctx, string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential userCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext ctx, string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential userCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions.AcquireTokenAsync(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential)" />
      <MemberSignature Language="F#" Value="static member AcquireTokenAsync : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions.AcquireTokenAsync (ctx, resource, clientId, userCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions/&lt;AcquireTokenAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ctx" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" RefType="this" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" />
      </Parameters>
      <Docs>
        <param name="ctx">認証コンテキストのインスタンス</param>
        <param name="resource">要求されたトークンの受信者は、ターゲット リソースの識別子。</param>
        <param name="clientId">トークンを要求したクライアントの識別子。</param>
        <param name="userCredential">トークンの取得に使用するユーザーの資格情報です。</param>
        <summary>
            機関からセキュリティ トークンを取得します。
            </summary>
        <returns>アクセス トークン、その有効期限、ユーザー情報が含まれています。</returns>
        <remarks>この機能は、Azure Active Directory と Windows 10 で Active Directory フェデレーション サービス (ADFS) に対してのみサポートされます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>