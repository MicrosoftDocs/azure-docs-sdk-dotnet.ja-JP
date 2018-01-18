<Type Name="UserContext" FullName="Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext">
  <TypeSignature Language="C#" Value="public sealed class UserContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UserContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UserContext" />
  <TypeSignature Language="F#" Value="type UserContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8389e-101">アプリケーションを使用して、ユーザーに関する情報をカプセル化します。</span><span class="sxs-lookup"><span data-stu-id="8389e-101">Encapsulates information about a user using an application.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public string AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As String" />
      <MemberSignature Language="F#" Value="member this.AccountId : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8389e-102">取得またはユーザーに関連付けられているアプリケーション定義のアカウントの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="8389e-102">Gets or sets the ID of an application-defined account associated with the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticatedUserId">
      <MemberSignature Language="C#" Value="public string AuthenticatedUserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthenticatedUserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.AuthenticatedUserId" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticatedUserId As String" />
      <MemberSignature Language="F#" Value="member this.AuthenticatedUserId : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.AuthenticatedUserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8389e-103">取得または認証されたユーザー id を設定します。認証されたユーザー id は、アプリケーションまたはサービスで認証されたユーザーごとに一意に表す永続的な文字列である必要があります。</span><span class="sxs-lookup"><span data-stu-id="8389e-103">Gets or sets the authenticated user id. Authenticated user id should be a persistent string that uniquely represents each authenticated user in the application or service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8389e-104">取得またはアプリケーションにアクセスするユーザーの ID を設定します。</span><span class="sxs-lookup"><span data-stu-id="8389e-104">Gets or sets the ID of user accessing the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8389e-105">一意のユーザー ID が自動的に生成 Application Insights の構成では既定の。</span><span class="sxs-lookup"><span data-stu-id="8389e-105">Unique user ID is automatically generated in default Application Insights configuration.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgent">
      <MemberSignature Language="C#" Value="public string UserAgent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.UserAgent" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgent As String" />
      <MemberSignature Language="F#" Value="member this.UserAgent : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.Implementation.UserContext.UserAgent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8389e-106">取得またはユーザーに関連付けられているアプリケーション定義のアカウントの UserAgent を設定します。</span><span class="sxs-lookup"><span data-stu-id="8389e-106">Gets or sets the UserAgent of an application-defined account associated with the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>