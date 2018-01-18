<Type Name="UserIdentifierType" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType">
  <TypeSignature Language="C#" Value="public enum UserIdentifierType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UserIdentifierType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType" />
  <TypeSignature Language="VB.NET" Value="Public Enum UserIdentifierType" />
  <TypeSignature Language="F#" Value="type UserIdentifierType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="5b6d5-101">型を示します<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /></span><span class="sxs-lookup"><span data-stu-id="5b6d5-101">Indicates the type of <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OptionalDisplayableId">
      <MemberSignature Language="C#" Value="OptionalDisplayableId" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType OptionalDisplayableId = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.OptionalDisplayableId" />
      <MemberSignature Language="VB.NET" Value="OptionalDisplayableId" />
      <MemberSignature Language="F#" Value="OptionalDisplayableId = 1" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.OptionalDisplayableId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b6d5-102">ときに、<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />このトークンの取得操作で渡される型、操作が指定された値に一致するキャッシュを制限し、認証エクスペリエンスでヒントとして挿入します。</span><span class="sxs-lookup"><span data-stu-id="5b6d5-102">When a <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /> of this type is passed in a token acquisition operation, the operation restricts cache matches to the value provided and injects it as a hint in the authentication experience.</span></span> <span data-ttu-id="5b6d5-103">ただし、エンドユーザーが上書き、その値に指定した別のアカウントに発行されるトークンでその結果、<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />で入力します。</span><span class="sxs-lookup"><span data-stu-id="5b6d5-103">However the end user could overwrite that value, resulting in a token issued to a different account than the one specified in the <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /> in input.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RequiredDisplayableId">
      <MemberSignature Language="C#" Value="RequiredDisplayableId" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType RequiredDisplayableId = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.RequiredDisplayableId" />
      <MemberSignature Language="VB.NET" Value="RequiredDisplayableId" />
      <MemberSignature Language="F#" Value="RequiredDisplayableId = 2" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.RequiredDisplayableId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b6d5-104">ときに、<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />このトークンの取得操作で渡される型は、操作は保証を対応するを持つユーザーに対して発行されたトークンを返す<see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier.DisplayableId" />(UPN または電子メール) または失敗します。</span><span class="sxs-lookup"><span data-stu-id="5b6d5-104">When a <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /> of this type is passed in a token acquisition operation, the operation is guaranteed to return a token issued for the user with corresponding <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier.DisplayableId" /> (UPN or email) or fail</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UniqueId">
      <MemberSignature Language="C#" Value="UniqueId" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType UniqueId = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.UniqueId" />
      <MemberSignature Language="VB.NET" Value="UniqueId" />
      <MemberSignature Language="F#" Value="UniqueId = 0" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType.UniqueId" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifierType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="5b6d5-105">ときに、<see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />このトークンの取得操作で渡される型は、操作は保証を対応するを持つユーザーに対して発行されたトークンを返す<see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier.UniqueId" />と失敗します。</span><span class="sxs-lookup"><span data-stu-id="5b6d5-105">When a <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" /> of this type is passed in a token acquisition operation, the operation is guaranteed to return a token issued for the user with corresponding <see cref="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier.UniqueId" /> or fail.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>