<Type Name="UserInfo" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo">
  <TypeSignature Language="C#" Value="public sealed class UserInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UserInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UserInfo" />
  <TypeSignature Language="F#" Value="type UserInfo = class" />
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
            <span data-ttu-id="5c4f5-101">1 人のユーザーの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-101">Contains information of a single user.</span></span> <span data-ttu-id="5c4f5-102">この情報は、トークンのキャッシュ参照に使用されます。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-102">This information is used for token cache lookup.</span></span> <span data-ttu-id="5c4f5-103">また login_hint が受け入れられたときに、ユーザー Id をサービスに送信されるユーザー Id で作成されている場合。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-103">Also if created with userId, userId is sent to the service when login_hint is accepted.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c4f5-104">トークンのキャッシュ参照のユーザー情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-104">Create user information for token cache lookup</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserInfo (Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.#ctor(Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As UserInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo : Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo" />
      </Parameters>
      <Docs>
        <param name="other">To be added.</param>
        <summary>
            <span data-ttu-id="5c4f5-105">別のユーザー情報オブジェクトからコピーされたユーザー情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-105">Create user information copied from another UserInfo object</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayableId">
      <MemberSignature Language="C#" Value="public string DisplayableId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.DisplayableId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayableId As String" />
      <MemberSignature Language="F#" Value="member this.DisplayableId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.DisplayableId" />
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
            <span data-ttu-id="5c4f5-106">UserPrincipalName (UPN) 形式で表示可能な値を取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-106">Gets a displayable value in UserPrincipalName (UPN) format.</span></span> <span data-ttu-id="5c4f5-107">値は null でもかまいません。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-107">The value can be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FamilyName">
      <MemberSignature Language="C#" Value="public string FamilyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FamilyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.FamilyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FamilyName As String" />
      <MemberSignature Language="F#" Value="member this.FamilyName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.FamilyName" />
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
            <span data-ttu-id="5c4f5-108">サービスによって提供される場合は、ユーザーの姓を取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-108">Gets family name of the user if provided by the service.</span></span> <span data-ttu-id="5c4f5-109">それ以外の場合は、値は null です。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-109">If not, the value is null.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GivenName">
      <MemberSignature Language="C#" Value="public string GivenName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GivenName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.GivenName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GivenName As String" />
      <MemberSignature Language="F#" Value="member this.GivenName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.GivenName" />
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
            <span data-ttu-id="5c4f5-110">サービスによって提供される場合は、ユーザーの姓名の名を取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-110">Gets given name of the user if provided by the service.</span></span> <span data-ttu-id="5c4f5-111">それ以外の場合は、値は null です。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-111">If not, the value is null.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentityProvider">
      <MemberSignature Language="C#" Value="public string IdentityProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdentityProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.IdentityProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdentityProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdentityProvider : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.IdentityProvider" />
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
            <span data-ttu-id="5c4f5-112">サービスによって返される場合は、id プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-112">Gets identity provider if returned by the service.</span></span> <span data-ttu-id="5c4f5-113">それ以外の場合は、値は null です。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-113">If not, the value is null.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordChangeUrl">
      <MemberSignature Language="C#" Value="public Uri PasswordChangeUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri PasswordChangeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordChangeUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PasswordChangeUrl As Uri" />
      <MemberSignature Language="F#" Value="member this.PasswordChangeUrl : Uri" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordChangeUrl" />
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
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c4f5-114">Url を取得、ユーザーが変更できる期限切れのパスワード。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-114">Gets the url where the user can change the expiring password.</span></span> <span data-ttu-id="5c4f5-115">値は null でもかまいません。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-115">The value can be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PasswordExpiresOn">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; PasswordExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; PasswordExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PasswordExpiresOn As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.PasswordExpiresOn : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.PasswordExpiresOn" />
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
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c4f5-116">パスワードの有効期限が切れる時刻を取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-116">Gets the time when the password expires.</span></span> <span data-ttu-id="5c4f5-117">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-117">Default value is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueId">
      <MemberSignature Language="C#" Value="public string UniqueId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UniqueId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.UniqueId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UniqueId As String" />
      <MemberSignature Language="F#" Value="member this.UniqueId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserInfo.UniqueId" />
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
            <span data-ttu-id="5c4f5-118">トークンの取得中に認証されたユーザーの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="5c4f5-118">Gets identifier of the user authenticated during token acquisition.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>