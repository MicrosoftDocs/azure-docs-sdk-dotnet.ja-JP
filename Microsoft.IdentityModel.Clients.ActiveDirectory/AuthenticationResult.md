<Type Name="AuthenticationResult" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationResult" />
  <TypeSignature Language="F#" Value="type AuthenticationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="00b55-101">1 つのトークンの取得操作の結果が含まれています。</span><span class="sxs-lookup"><span data-stu-id="00b55-101">Contains the results of one token acquisition operation.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public string AccessToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessToken As String" />
      <MemberSignature Language="F#" Value="member this.AccessToken : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-102">要求されたアクセス トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="00b55-102">Gets the Access Token requested.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTokenType">
      <MemberSignature Language="C#" Value="public string AccessTokenType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessTokenType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessTokenType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTokenType As String" />
      <MemberSignature Language="F#" Value="member this.AccessTokenType : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.AccessTokenType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-103">返されるアクセス トークンの種類を取得します。</span><span class="sxs-lookup"><span data-stu-id="00b55-103">Gets the type of the Access Token returned.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthorizationHeader">
      <MemberSignature Language="C#" Value="public string CreateAuthorizationHeader ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string CreateAuthorizationHeader() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.CreateAuthorizationHeader" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateAuthorizationHeader () As String" />
      <MemberSignature Language="F#" Value="member this.CreateAuthorizationHeader : unit -&gt; string" Usage="authenticationResult.CreateAuthorizationHeader " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00b55-104">認証の結果から authorization ヘッダーを作成します。</span><span class="sxs-lookup"><span data-stu-id="00b55-104">Creates authorization header from authentication result.</span></span>
            </summary>
        <returns><span data-ttu-id="00b55-105">作成した承認ヘッダー</span><span class="sxs-lookup"><span data-stu-id="00b55-105">Created authorization header</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public DateTimeOffset ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresOn As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTimeOffset" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-106">AccessToken プロパティで返されるアクセス トークンが終了する有効な期間の点を取得します。</span><span class="sxs-lookup"><span data-stu-id="00b55-106">Gets the point in time in which the Access Token returned in the AccessToken property ceases to be valid.</span></span>
            <span data-ttu-id="00b55-107">この値は、ローカルで計測された現在の UTC 時間で、サービスから受信した値 expiresIn に基づいて計算されます。</span><span class="sxs-lookup"><span data-stu-id="00b55-107">This value is calculated based on current UTC time measured locally and the value expiresIn received from the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedLifeTimeToken">
      <MemberSignature Language="C#" Value="public bool ExtendedLifeTimeToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExtendedLifeTimeToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExtendedLifeTimeToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExtendedLifeTimeToken As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExtendedLifeTimeToken : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.ExtendedLifeTimeToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-108">返されたトークンが通常または拡張の有効期間中にあるかどうかは、開発者にについてを説明します。</span><span class="sxs-lookup"><span data-stu-id="00b55-108">Gives information to the developer whether token returned is during normal or extended lifetime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdToken">
      <MemberSignature Language="C#" Value="public string IdToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.IdToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdToken As String" />
      <MemberSignature Language="F#" Value="member this.IdToken : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.IdToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-109">Id トークンが返されない場合、サービスまたは null で返される場合は、全体 Id トークンを取得します。</span><span class="sxs-lookup"><span data-stu-id="00b55-109">Gets the entire Id Token if returned by the service or null if no Id Token is returned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-110">トークンがから取得されたテナントの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="00b55-110">Gets an identifier for the tenant the token was acquired from.</span></span> <span data-ttu-id="00b55-111">このプロパティは、テナントの情報がサービスによって返されない場合は null になります。</span><span class="sxs-lookup"><span data-stu-id="00b55-111">This property will be null if tenant information is not returned by the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserInfo">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo UserInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo UserInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.UserInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserInfo As UserInfo" />
      <MemberSignature Language="F#" Value="member this.UserInfo : Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult.UserInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00b55-112">ユーザー id を含むユーザー情報を取得します。ユーザー情報の一部の要素が null の場合は、サービスによって返されない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="00b55-112">Gets user information including user Id. Some elements in UserInfo might be null if not returned by the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>