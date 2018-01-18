<Type Name="IUser" FullName="Microsoft.Identity.Client.IUser">
  <TypeSignature Language="C#" Value="public interface IUser" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUser" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IUser" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUser" />
  <TypeSignature Language="F#" Value="type IUser = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2cbe1-101">1 人のユーザーの情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-101">Contains information of a single user.</span></span> <span data-ttu-id="2cbe1-102">この情報はトークン キャッシュ参照の使用し、エンドポイントを承認 STS にユーザー セッションを強制します。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-102">This information is used for token cache lookup and enforcing the user session on STS authorize endpont.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisplayableId">
      <MemberSignature Language="C#" Value="public string DisplayableId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.DisplayableId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayableId As String" />
      <MemberSignature Language="F#" Value="member this.DisplayableId : string" Usage="Microsoft.Identity.Client.IUser.DisplayableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cbe1-103">UserPrincipalName (UPN) 形式で表示可能な値を取得します。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-103">Gets a displayable value in UserPrincipalName (UPN) format.</span></span> <span data-ttu-id="2cbe1-104">値は null でもかまいません。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-104">The value can be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.Identity.Client.IUser.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cbe1-105">ユーザー id に強力なハンドルとして、ライブラリと、サービスによって使用されるユーザーの識別子を取得します。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-105">Gets an identifier for the user that is used by the library and the service as a strong handle to user identity.</span></span> <span data-ttu-id="2cbe1-106">null にすることはできません。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-106">Cannot be null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentityProvider">
      <MemberSignature Language="C#" Value="public string IdentityProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdentityProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.IdentityProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdentityProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdentityProvider : string" Usage="Microsoft.Identity.Client.IUser.IdentityProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cbe1-107">サービスによって返される場合は、id プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-107">Gets identity provider if returned by the service.</span></span> <span data-ttu-id="2cbe1-108">それ以外の場合は、値は null です。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-108">If not, the value is null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Identity.Client.IUser.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cbe1-109">サービスによって提供される場合は、ユーザーの姓名の名を取得します。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-109">Gets given name of the user if provided by the service.</span></span> <span data-ttu-id="2cbe1-110">それ以外の場合は、値は null です。</span><span class="sxs-lookup"><span data-stu-id="2cbe1-110">If not, the value is null.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>