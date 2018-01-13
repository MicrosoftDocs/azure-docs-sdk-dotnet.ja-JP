<Type Name="AuthenticationResult" FullName="Microsoft.Identity.Client.AuthenticationResult">
  <TypeSignature Language="C#" Value="public class AuthenticationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthenticationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.AuthenticationResult" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthenticationResult" />
  <TypeSignature Language="F#" Value="type AuthenticationResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            1 つのトークンの取得操作の結果が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public virtual string AccessToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property AccessToken As String" />
      <MemberSignature Language="F#" Value="member this.AccessToken : string" Usage="Microsoft.Identity.Client.AuthenticationResult.AccessToken" />
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
            要求されたアクセス トークンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthorizationHeader">
      <MemberSignature Language="C#" Value="public virtual string CreateAuthorizationHeader ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CreateAuthorizationHeader() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.AuthenticationResult.CreateAuthorizationHeader" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAuthorizationHeader () As String" />
      <MemberSignature Language="F#" Value="abstract member CreateAuthorizationHeader : unit -&gt; string&#xA;override this.CreateAuthorizationHeader : unit -&gt; string" Usage="authenticationResult.CreateAuthorizationHeader " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            認証の結果から authorization ヘッダーを作成します。
            </summary>
        <returns>作成した承認ヘッダー</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiresOn">
      <MemberSignature Language="C#" Value="public virtual DateTimeOffset ExpiresOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset ExpiresOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.ExpiresOn" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ExpiresOn As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.ExpiresOn : DateTimeOffset" Usage="Microsoft.Identity.Client.AuthenticationResult.ExpiresOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            トークン プロパティで返されるアクセス トークンを停止すると有効期間の点を取得します。
            この値は、ローカルで計測された現在の UTC 時間で、サービスから受信した値 expiresIn に基づいて計算されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdToken">
      <MemberSignature Language="C#" Value="public virtual string IdToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.IdToken" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property IdToken As String" />
      <MemberSignature Language="F#" Value="member this.IdToken : string" Usage="Microsoft.Identity.Client.AuthenticationResult.IdToken" />
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
            Id トークンが返されない場合、サービスまたは null で返される場合は、全体 Id トークンを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scopes">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; Scopes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; Scopes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.Scopes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Scopes As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.Scopes : seq&lt;string&gt;" Usage="Microsoft.Identity.Client.AuthenticationResult.Scopes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスから返されたスコープの値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public virtual string TenantId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string" Usage="Microsoft.Identity.Client.AuthenticationResult.TenantId" />
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
            トークンがから取得されたテナントの識別子を取得します。 このプロパティは、テナントの情報がサービスによって返されない場合は null になります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UniqueId">
      <MemberSignature Language="C#" Value="public virtual string UniqueId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UniqueId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.UniqueId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property UniqueId As String" />
      <MemberSignature Language="F#" Value="member this.UniqueId : string" Usage="Microsoft.Identity.Client.AuthenticationResult.UniqueId" />
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
            ユーザーの一意の Id を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="User">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Identity.Client.IUser User { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Identity.Client.IUser User" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.AuthenticationResult.User" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property User As IUser" />
      <MemberSignature Language="F#" Value="member this.User : Microsoft.Identity.Client.IUser" Usage="Microsoft.Identity.Client.AuthenticationResult.User" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.IUser</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ユーザー オブジェクトを取得します。 ユーザーの一部の要素が null の場合は、サービスによって返されない可能性があります。 これは、一部 API のオーバー ロードを使用するどのユーザーを識別に渡されることができます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>