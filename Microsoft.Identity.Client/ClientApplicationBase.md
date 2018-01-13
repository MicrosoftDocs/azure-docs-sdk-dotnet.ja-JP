<Type Name="ClientApplicationBase" FullName="Microsoft.Identity.Client.ClientApplicationBase">
  <TypeSignature Language="C#" Value="public abstract class ClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ClientApplicationBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ClientApplicationBase" />
  <TypeSignature Language="F#" Value="type ClientApplicationBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
    <Summary>
            一般的な API のメソッドとプロパティを含む抽象クラスです。 PublicClientApplication と ConfidentialClientApplication の両方は、このクラスを拡張します。
            </Summary>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ClientApplicationBase (string clientId, string authority, string redirectUri, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.#ctor(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (clientId As String, authority As String, redirectUri As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientApplicationBase : string * string * string * bool -&gt; Microsoft.Identity.Client.ClientApplicationBase" Usage="new Microsoft.Identity.Client.ClientApplicationBase (clientId, authority, redirectUri, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <param name="authority"></param>
        <param name="redirectUri"></param>
        <param name="validateAuthority"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
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
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
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
        <param name="user">ユーザー トークンが要求されます。<see cref="T:Microsoft.Identity.Client.User" /></param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <param name="forceRefresh">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、使用可能な場合は、更新トークンを使用して新しいアクセス トークンを取得しようとしています。</param>
        <summary>
            キャッシュからアクセス トークンを取得しようとしています。 要求されたすべてのスコープには、少なくとも含まれている場合、アクセス トークンは、一致と見なされます。
            つまり、要求したよりも詳細のスコープを持つアクセス トークンをも返される可能性があります。 アクセス トークンが期限切れまたは間もなく有効期限 (5 分以内)、更新トークン (使用可能な場合) はネットワーク呼び出しを行うことによって、新しいアクセス トークンの取得に使用されます。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.Authority" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.Component" />
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
    <Member MemberName="DefaultAuthority">
      <MemberSignature Language="C#" Value="protected const string DefaultAuthority;" />
      <MemberSignature Language="ILAsm" Value=".field family static literal string DefaultAuthority" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberSignature Language="VB.NET" Value="Protected Const DefaultAuthority As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultAuthority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <Summary>
            既定の機関が対話型の呼び出しに使用します。
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser&#xA;override this.GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="clientApplicationBase.GetUser identifier" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
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
            アプリの登録ポータルで構成されている Uri にリダイレクトします。 PublicClientApplication は、urn:ietf:wg:oauth:2.0:oob の既定値があります。ライブラリがシステム webview の認証を利用する必要があると、この既定値は iOS および Android には適用されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit&#xA;override this.Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="clientApplicationBase.Remove user" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.ClientApplicationBase.Users" />
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
            アプリケーションのキャッシュで利用可能なすべてのユーザーの一覧を提供する、キャッシュ経由でユーザー中心のビューを返します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
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
            取得/設定を示す値機関検証は有効になっているかどうか、または無効化します。 値は既定では true です。 B2C アプリケーション deveopers で false に設定する必要があります。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>