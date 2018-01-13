<Type Name="IClientApplicationBase" FullName="Microsoft.Identity.Client.IClientApplicationBase">
  <TypeSignature Language="C#" Value="public interface IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IClientApplicationBase = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            共通の検証メソッドを含むコンポーネント
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">トークンが要求されるユーザー。 <see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <summary>
            キャッシュからアクセス トークンを取得しようとしています。 要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。
            つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。 アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iClientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="user">ユーザー トークンが要求されます。<see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <param name="forceRefresh">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、使用可能な場合は、更新トークンを使用して新しいアクセス トークンを取得しようとしています。</param>
        <summary>
            キャッシュからアクセス トークンを取得しようとしています。 要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。
            つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。 アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <Summary>
            ライブラリで使用される開発者または既定の機関から提供される証明機関。
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.IClientApplicationBase.ClientId" />
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
            既定値になります。 開発者によってオーバーライドできます。 一度設定したら、アプリケーションは、クライアント id。 にバインドされます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.Component" />
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
            使用 MSAL、およびそのコンポーネントの識別子はライブラリ/Sdk MSAL を消費するものです。 これは、アプリ vs MSAL による使用量のコンポーネント ライブラリによる使用率が MSAL 間のあいまいさが許可されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="iClientApplicationBase.GetUser identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.IUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">ユーザーの識別子</param>
        <summary>
            キャッシュ内に、識別子によって使用可能なユーザーからのユーザーを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectUri">
      <MemberSignature Language="C#" Value="public string RedirectUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.RedirectUri" />
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
            ポータルで構成された Uri にリダイレクトします。 既定値になります。 開発者が、既定のクライアント id。 を使用するかどうかは必要ありません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="iClientApplicationBase.Remove user" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="user">削除する必要があるユーザーのインスタンス</param>
        <summary>
            指定したユーザーのすべてのキャッシュされたトークンを削除します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceParameters">
      <MemberSignature Language="C#" Value="public string SliceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.IClientApplicationBase.SliceParameters" />
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
            設定またはドッグフード テストを STS に送信される、カスタム クエリ パラメーターを取得します。 このパラメーターは、アプリケーションに悪影響を与えるを与える可能性があります、開発者によっては設定しないでください。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Identity.Client.IUser&gt; Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.IClientApplicationBase.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            キャッシュの使用可能なすべてのユーザーの一覧を提供する、キャッシュ経由でユーザー中心のビューを返します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.Identity.Client.IClientApplicationBase.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            アドレスの検証は有効になっているかどうか、または無効化を示す値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>