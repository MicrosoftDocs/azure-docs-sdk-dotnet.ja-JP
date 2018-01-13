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
            1 人のユーザーの情報が含まれています。 この情報はトークン キャッシュ参照の使用し、エンドポイントを承認 STS にユーザー セッションを強制します。
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
            UserPrincipalName (UPN) 形式で表示可能な値を取得します。 値は null でもかまいません。
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
            ユーザー id に強力なハンドルとして、ライブラリと、サービスによって使用されるユーザーの識別子を取得します。 null にすることはできません。
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
            サービスによって返される場合は、id プロバイダーを取得します。 それ以外の場合は、値は null です。
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
            サービスによって提供される場合は、ユーザーの姓名の名を取得します。 それ以外の場合は、値は null です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>