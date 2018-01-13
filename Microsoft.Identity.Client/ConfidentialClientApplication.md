<Type Name="ConfidentialClientApplication" FullName="Microsoft.Identity.Client.ConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public sealed class ConfidentialClientApplication : Microsoft.Identity.Client.ClientApplicationBase, Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfidentialClientApplication extends Microsoft.Identity.Client.ClientApplicationBase implements class Microsoft.Identity.Client.IClientApplicationBase, class Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfidentialClientApplication&#xA;Inherits ClientApplicationBase&#xA;Implements IConfidentialClientApplication" />
  <TypeSignature Language="F#" Value="type ConfidentialClientApplication = class&#xA;    inherit ClientApplicationBase&#xA;    interface IConfidentialClientApplication&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Identity.Client.ClientApplicationBase</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IConfidentialClientApplication</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            秘密のクライアント アプリケーションのように Web アプリ/API を使用するクラスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId">アプリケーションのクライアント Id。 REQUIRED. (必須。)</param>
        <param name="redirectUri">アプリケーションのリダイレクト URI。 REQUIRED. (必須。)</param>
        <param name="clientCredential">アプリケーションのクライアント資格情報です。 証明書またはシークレットがあります。 REQUIRED. (必須。)</param>
        <param name="userTokenCache">ユーザー トークンを保存するためのトークン キャッシュします。 OPTIONAL. (省略可能。)</param>
        <param name="appTokenCache">アプリケーション/クライアント トークンを保存するためのトークン キャッシュします。 OPTIONAL. (省略可能。)</param>
        <summary>
            クラスのインスタンスを作成するコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfidentialClientApplication (string clientId, string authority, string redirectUri, Microsoft.Identity.Client.ClientCredential clientCredential, Microsoft.Identity.Client.TokenCache userTokenCache, Microsoft.Identity.Client.TokenCache appTokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, class Microsoft.Identity.Client.ClientCredential clientCredential, class Microsoft.Identity.Client.TokenCache userTokenCache, class Microsoft.Identity.Client.TokenCache appTokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.#ctor(System.String,System.String,System.String,Microsoft.Identity.Client.ClientCredential,Microsoft.Identity.Client.TokenCache,Microsoft.Identity.Client.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ConfidentialClientApplication : string * string * string * Microsoft.Identity.Client.ClientCredential * Microsoft.Identity.Client.TokenCache * Microsoft.Identity.Client.TokenCache -&gt; Microsoft.Identity.Client.ConfidentialClientApplication" Usage="new Microsoft.Identity.Client.ConfidentialClientApplication (clientId, authority, redirectUri, clientCredential, userTokenCache, appTokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.Identity.Client.ClientCredential" />
        <Parameter Name="userTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
        <Parameter Name="appTokenCache" Type="Microsoft.Identity.Client.TokenCache" />
      </Parameters>
      <Docs>
        <param name="clientId">アプリケーションのクライアント Id。 REQUIRED. (必須。)</param>
        <param name="authority">クライアント アプリケーションに使用する機関です。 REQUIRED. (必須。)</param>
        <param name="redirectUri">アプリケーションのリダイレクト URI。 REQUIRED. (必須。)</param>
        <param name="clientCredential">アプリケーションのクライアント資格情報です。 証明書またはシークレットがあります。 REQUIRED. (必須。)</param>
        <param name="userTokenCache">ユーザー トークンを保存するためのトークン キャッシュします。 OPTIONAL. (省略可能。)</param>
        <param name="appTokenCache">アプリケーション/クライアント トークンを保存するためのトークン キャッシュします。 OPTIONAL. (省略可能。)</param>
        <summary>
            クラスのインスタンスを作成するコンス トラクター
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">サービスの認証エンドポイントから受信した認証コードです。</param>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <summary>
            以前に受信した認証コードを使用して、機関からセキュリティ トークンを取得します。
            このメソッドは、トークンのキャッシュを参照できませんが、結果を格納し、それを検索できますなどの他のメソッドを使用して、<see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />です。
            </summary>
        <returns>要求されたスコープのユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync scopes" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <summary>
            秘密のクライアントのサービスからのトークンを取得します。 このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。
            </summary>
        <returns>要求されたスコープのアプリケーションのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenForClientAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="forceRefresh">TRUE の場合、API は、キャッシュにアクセス トークンを無視して、クライアントの資格情報を使用して新しいアクセス トークンを取得しようとしています。</param>
        <summary>
            秘密のクライアントのサービスからのトークンを取得します。 このメソッドは、キャッシュ内の有効なアクセス トークンを検索しようとします。
            </summary>
        <returns>要求されたスコープのアプリケーションのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="userAssertion">ユーザーを含む UserAssertion のインスタンスのトークン。</param>
        <summary>
            取得の代理として-のフローを使用してトークンです。
            </summary>
        <returns>要求されたスコープのユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="confidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;AcquireTokenOnBehalfOfAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="userAssertion">ユーザーを含む UserAssertion のインスタンスのトークン。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <summary>
            取得の代理として-のフローを使用してトークンです。
            </summary>
        <returns>要求されたスコープのユーザーのトークンを含む認証の結果</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <summary>
            クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。
            </summary>
        <returns>クエリ パラメーターを含む authorize エンドポイントの URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;&#xA;override this.GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="confidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ConfidentialClientApplication/&lt;GetAuthorizationRequestUrlAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">リソースに対して要求されたスコープの配列</param>
        <param name="redirectUri">機関からの応答を受信したときに戻るにはアドレスです。</param>
        <param name="loginHint">ユーザーの識別子です。 通常は UPN です。</param>
        <param name="extraQueryParameters">証明機関に HTTP 認証要求のクエリ文字列には、このパラメーターが追加されます。 パラメーターを null にすることができます。</param>
        <param name="extraScopesToConsent">開発者があらかじめ同意を要求できますスコープの配列です。</param>
        <param name="authority">トークンの要求対象となる特定の機関です。 構成されているよりも、別の値を渡すことは、構成済みの値を変更しません。</param>
        <summary>
            クエリ パラメーターを含む、authorize エンドポイントの URL を取得します。
            </summary>
        <returns>クエリ パラメーターを含む authorize エンドポイントの URL です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>