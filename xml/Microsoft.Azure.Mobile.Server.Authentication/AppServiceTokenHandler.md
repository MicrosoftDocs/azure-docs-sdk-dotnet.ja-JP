<Type Name="AppServiceTokenHandler" FullName="Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler">
  <TypeSignature Language="C#" Value="public class AppServiceTokenHandler : Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceTokenHandler extends System.Object implements class Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceTokenHandler&#xA;Implements IAppServiceTokenHandler" />
  <TypeSignature Language="F#" Value="type AppServiceTokenHandler = class&#xA;    interface IAppServiceTokenHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="b1dd1-101">既定の実装を提供、<see cref="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-101">Provides a default implementation of the <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" /> interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceTokenHandler (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.#ctor(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler : System.Web.Http.HttpConfiguration -&gt; Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler" Usage="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler config" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config"><span data-ttu-id="b1dd1-102">このインスタンスの <see cref="T:System.Web.Http.HttpConfiguration" />。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-102">The <see cref="T:System.Web.Http.HttpConfiguration" /> for this instance.</span></span></param>
        <summary>
            <span data-ttu-id="b1dd1-103"><see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUserId">
      <MemberSignature Language="C#" Value="public virtual string CreateUserId (string providerName, string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CreateUserId(string providerName, string providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.CreateUserId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateUserId (providerName As String, providerUserId As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CreateUserId : string * string -&gt; string&#xA;override this.CreateUserId : string * string -&gt; string" Usage="appServiceTokenHandler.CreateUserId (providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.CreateUserId(System.String,System.String)</InterfaceMember>
      </Implements>
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
        <param name="providerName">To be added.</param>
        <param name="providerUserId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="TryParseUserId">
      <MemberSignature Language="C#" Value="public virtual bool TryParseUserId (string userId, out string providerName, out string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryParseUserId(string userId, [out] string&amp; providerName, [out] string&amp; providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.TryParseUserId(System.String,System.String@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function TryParseUserId (userId As String, ByRef providerName As String, ByRef providerUserId As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryParseUserId : string *  *  -&gt; bool&#xA;override this.TryParseUserId : string *  *  -&gt; bool" Usage="appServiceTokenHandler.TryParseUserId (userId, providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryParseUserId(System.String,System.String@,System.String@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="providerName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="providerUserId" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="userId">To be added.</param>
        <param name="providerName">To be added.</param>
        <param name="providerUserId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="TryValidateLoginToken">
      <MemberSignature Language="C#" Value="public virtual bool TryValidateLoginToken (string token, string signingKey, System.Collections.Generic.IEnumerable&lt;string&gt; validAudiences, System.Collections.Generic.IEnumerable&lt;string&gt; validIssuers, out System.Security.Claims.ClaimsPrincipal claimsPrincipal);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryValidateLoginToken(string token, string signingKey, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validAudiences, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validIssuers, [out] class System.Security.Claims.ClaimsPrincipal&amp; claimsPrincipal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.TryValidateLoginToken(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.Security.Claims.ClaimsPrincipal@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function TryValidateLoginToken (token As String, signingKey As String, validAudiences As IEnumerable(Of String), validIssuers As IEnumerable(Of String), ByRef claimsPrincipal As ClaimsPrincipal) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryValidateLoginToken : string * string * seq&lt;string&gt; * seq&lt;string&gt; *  -&gt; bool&#xA;override this.TryValidateLoginToken : string * string * seq&lt;string&gt; * seq&lt;string&gt; *  -&gt; bool" Usage="appServiceTokenHandler.TryValidateLoginToken (token, signingKey, validAudiences, validIssuers, claimsPrincipal)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryValidateLoginToken(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.Security.Claims.ClaimsPrincipal@)</InterfaceMember>
      </Implements>
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
        <param name="token">To be added.</param>
        <param name="signingKey">To be added.</param>
        <param name="validAudiences">To be added.</param>
        <param name="validIssuers">To be added.</param>
        <param name="claimsPrincipal">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="TryValidateToken">
      <MemberSignature Language="C#" Value="public static bool TryValidateToken (System.IdentityModel.Tokens.TokenValidationParameters validationParameters, string tokenValue, string secretKey, out System.Security.Claims.ClaimsPrincipal claimsPrincipal);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryValidateToken(class System.IdentityModel.Tokens.TokenValidationParameters validationParameters, string tokenValue, string secretKey, [out] class System.Security.Claims.ClaimsPrincipal&amp; claimsPrincipal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.TryValidateToken(System.IdentityModel.Tokens.TokenValidationParameters,System.String,System.String,System.Security.Claims.ClaimsPrincipal@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryValidateToken (validationParameters As TokenValidationParameters, tokenValue As String, secretKey As String, ByRef claimsPrincipal As ClaimsPrincipal) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryValidateToken : System.IdentityModel.Tokens.TokenValidationParameters * string * string *  -&gt; bool" Usage="Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.TryValidateToken (validationParameters, tokenValue, secretKey, claimsPrincipal)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.CLSCompliant(false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="validationParameters" Type="System.IdentityModel.Tokens.TokenValidationParameters" />
        <Parameter Name="tokenValue" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
        <Parameter Name="claimsPrincipal" Type="System.Security.Claims.ClaimsPrincipal&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="validationParameters">To be added.</param>
        <param name="tokenValue">To be added.</param>
        <param name="secretKey">To be added.</param>
        <param name="claimsPrincipal">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateToken">
      <MemberSignature Language="C#" Value="public static void ValidateToken (string token, string secretKey, string audience, string issuer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateToken(string token, string secretKey, string audience, string issuer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.ValidateToken(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub ValidateToken (token As String, secretKey As String, audience As String, issuer As String)" />
      <MemberSignature Language="F#" Value="static member ValidateToken : string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Mobile.Server.Authentication.AppServiceTokenHandler.ValidateToken (token, secretKey, audience, issuer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="secretKey" Type="System.String" />
        <Parameter Name="audience" Type="System.String" />
        <Parameter Name="issuer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="b1dd1-104">JWT トークン文字列を検証します。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-104">The JWT token string to validate.</span></span></param>
        <param name="secretKey"><span data-ttu-id="b1dd1-105">検証に使用するキー。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-105">The key to use in the validation.</span></span></param>
        <param name="audience"><span data-ttu-id="b1dd1-106">検証で使用する対象ユーザーです。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-106">The audience to use in validation.</span></span></param>
        <param name="issuer"><span data-ttu-id="b1dd1-107">検証で使用する発行者。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-107">The issuer to use in validation.</span></span></param>
        <summary>
            <span data-ttu-id="b1dd1-108">指定した秘密キーに対して指定された JWT トークンの文字列を検証します。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-108">Validates the specified JWT token string against the specified secret key.</span></span> <span data-ttu-id="b1dd1-109">検証メソッドによってスローされた例外はキャッチされません。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-109">Exceptions thrown by the validation method are not caught.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="b1dd1-110">JWT トークンの形式が正しくない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-110">Thrown if the JWT token is malformed.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="b1dd1-111">メソッドのパラメーターのいずれかが null または空の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-111">Thrown if one of the method parameters are null or empty.</span></span></exception>
        <exception cref="T:System.IdentityModel.Tokens.SecurityTokenValidationException"><span data-ttu-id="b1dd1-112">JWT トークンが検証に失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-112">Thrown if the JWT token fails validation.</span></span></exception>
        <exception cref="T:System.IdentityModel.Tokens.SecurityTokenExpiredException"><span data-ttu-id="b1dd1-113">JWT トークンの有効期限が切れる場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-113">Thrown if the JWT token is expired.</span></span></exception>
        <exception cref="T:System.IdentityModel.Tokens.SecurityTokenNotYetValidException"><span data-ttu-id="b1dd1-114">JWT トークンがまだ有効でない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b1dd1-114">Thrown if the JWT token is not yet valid.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>