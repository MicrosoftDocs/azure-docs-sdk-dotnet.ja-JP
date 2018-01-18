<Type Name="IAppServiceTokenHandler" FullName="Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler">
  <TypeSignature Language="C#" Value="public interface IAppServiceTokenHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceTokenHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceTokenHandler" />
  <TypeSignature Language="F#" Value="type IAppServiceTokenHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="17e66-101">セキュリティ トークンを処理するための抽象化を提供します。</span><span class="sxs-lookup"><span data-stu-id="17e66-101">Provides an abstraction for handling security tokens.</span></span> <span data-ttu-id="17e66-102">セキュリティ トークンを検証およびを作成するためにこのアブストラクションを使用できます<see cref="T:System.Security.Claims.ClaimsPrincipal" />インスタンス。</span><span class="sxs-lookup"><span data-stu-id="17e66-102">This abstraction can be used for validating security tokens and creating <see cref="T:System.Security.Claims.ClaimsPrincipal" /> instances.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateUserId">
      <MemberSignature Language="C#" Value="public string CreateUserId (string providerName, string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CreateUserId(string providerName, string providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.CreateUserId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserId (providerName As String, providerUserId As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CreateUserId : string * string -&gt; string" Usage="iAppServiceTokenHandler.CreateUserId (providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="providerName" Type="System.String" />
        <Parameter Name="providerUserId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="providerName"><span data-ttu-id="17e66-103">プロバイダーのログイン名。</span><span class="sxs-lookup"><span data-stu-id="17e66-103">The login provider name.</span></span></param>
        <param name="providerUserId"><span data-ttu-id="17e66-104">プロバイダーの特定のユーザー id。</span><span class="sxs-lookup"><span data-stu-id="17e66-104">The provider specific user id.</span></span></param>
        <summary>
            <span data-ttu-id="17e66-105">含まれるユーザー id 値を作成、<see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />です。</span><span class="sxs-lookup"><span data-stu-id="17e66-105">Creates a user id value contained within a <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />.</span></span> <span data-ttu-id="17e66-106">形式は、ユーザー id <c>ProviderName:ProviderId</c>場所、 <c>ProviderName</c>ログイン プロバイダーの一意の識別子は、および<c>ProviderId</c>プロバイダー特定ユーザーの id を指定します。</span><span class="sxs-lookup"><span data-stu-id="17e66-106">The user id is of the form <c>ProviderName:ProviderId</c> where the <c>ProviderName</c> is the unique identifier for the login provider and the <c>ProviderId</c> is the provider specific id for a given user.</span></span>
            </summary>
        <returns><span data-ttu-id="17e66-107">書式設定された<see cref="T:System.String" />結果として得られる値を表すです。</span><span class="sxs-lookup"><span data-stu-id="17e66-107">A formatted <see cref="T:System.String" /> representing the resulting value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParseUserId">
      <MemberSignature Language="C#" Value="public bool TryParseUserId (string userId, out string providerName, out string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryParseUserId(string userId, [out] string&amp; providerName, [out] string&amp; providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryParseUserId(System.String,System.String@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryParseUserId (userId As String, ByRef providerName As String, ByRef providerUserId As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryParseUserId : string *  *  -&gt; bool" Usage="iAppServiceTokenHandler.TryParseUserId (userId, providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="This is not unreasonable for this API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="providerName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="providerUserId" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="17e66-108">解析する入力値。</span><span class="sxs-lookup"><span data-stu-id="17e66-108">The input value to parse.</span></span></param>
        <param name="providerName"><span data-ttu-id="17e66-109">プロバイダーのログイン名です。または<c>null</c>場合、<paramref name="userId" />が無効です。</span><span class="sxs-lookup"><span data-stu-id="17e66-109">The login provider name; or <c>null</c> if the <paramref name="userId" /> is not valid.</span></span></param>
        <param name="providerUserId"><span data-ttu-id="17e66-110">プロバイダーの特定のユーザー id です。または<c>null</c>は、<paramref name="userId" />が無効です。</span><span class="sxs-lookup"><span data-stu-id="17e66-110">The provider specific user id; or <c>null</c> is the <paramref name="userId" /> is not valid.</span></span></param>
        <summary>
            <span data-ttu-id="17e66-111">その 2 つのコンポーネントにユーザー id を解析して: <c>ProviderName</c>ログイン プロバイダーを一意に識別して、 <c>ProviderId</c>特定のユーザーに対してプロバイダー固有の id を識別します。</span><span class="sxs-lookup"><span data-stu-id="17e66-111">Parses a user id into its two components: a <c>ProviderName</c> which uniquely identifies the login provider and the <c>ProviderId</c> which identifies the provider specific id for a given user.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="17e66-112"><c>true</c>場合<paramref name="userId" />それ以外の有効な<c>false</c>/</span><span class="sxs-lookup"><span data-stu-id="17e66-112"><c>true</c> if <paramref name="userId" /> is valid; otherwise <c>false</c>/</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryValidateLoginToken">
      <MemberSignature Language="C#" Value="public bool TryValidateLoginToken (string token, string signingKey, System.Collections.Generic.IEnumerable&lt;string&gt; validAudiences, System.Collections.Generic.IEnumerable&lt;string&gt; validIssuers, out System.Security.Claims.ClaimsPrincipal claimsPrincipal);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryValidateLoginToken(string token, string signingKey, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validAudiences, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validIssuers, [out] class System.Security.Claims.ClaimsPrincipal&amp; claimsPrincipal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryValidateLoginToken(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.Security.Claims.ClaimsPrincipal@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryValidateLoginToken (token As String, signingKey As String, validAudiences As IEnumerable(Of String), validIssuers As IEnumerable(Of String), ByRef claimsPrincipal As ClaimsPrincipal) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryValidateLoginToken : string * string * seq&lt;string&gt; * seq&lt;string&gt; *  -&gt; bool" Usage="iAppServiceTokenHandler.TryValidateLoginToken (token, signingKey, validAudiences, validIssuers, claimsPrincipal)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="signingKey" Type="System.String" />
        <Parameter Name="validAudiences" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="validIssuers" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="claimsPrincipal" Type="System.Security.Claims.ClaimsPrincipal&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="17e66-113">A<see cref="T:System.String" />を検証する認証トークンの表現。</span><span class="sxs-lookup"><span data-stu-id="17e66-113">A <see cref="T:System.String" /> representation of the authentication token to validate.</span></span></param>
        <param name="signingKey"><span data-ttu-id="17e66-114">トークンが署名されたときのシークレット キー。</span><span class="sxs-lookup"><span data-stu-id="17e66-114">The secret key with which the token has been signed.</span></span></param>
        <param name="validAudiences"><span data-ttu-id="17e66-115">トークンの検証にそのまま使用する有効な対象ユーザー。</span><span class="sxs-lookup"><span data-stu-id="17e66-115">The valid audiences to accept in token validation.</span></span></param>
        <param name="validIssuers"><span data-ttu-id="17e66-116">有効な発行者の同意にトークンを検証します。</span><span class="sxs-lookup"><span data-stu-id="17e66-116">The valid issuers to accept in token validation.</span></span></param>
        <param name="claimsPrincipal"><span data-ttu-id="17e66-117">その結果、<see cref="T:System.Security.Claims.ClaimsPrincipal" />トークンが無効である場合は null それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="17e66-117">The resulting <see cref="T:System.Security.Claims.ClaimsPrincipal" /> if the token is valid; null otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="17e66-118">ユーザー要求の認証に使用するモバイル サービス認証トークンの文字列形式を検証します。</span><span class="sxs-lookup"><span data-stu-id="17e66-118">Validates a string representation of a mobile service authentication token used to authenticate a user request.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="17e66-119"><c>true</c>場合<paramref name="token" />それ以外の有効な<c>false</c>/</span><span class="sxs-lookup"><span data-stu-id="17e66-119"><c>true</c> if <paramref name="token" /> is valid; otherwise <c>false</c>/</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>