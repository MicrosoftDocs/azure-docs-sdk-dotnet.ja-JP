<Type Name="IConfidentialClientApplication" FullName="Microsoft.Identity.Client.IConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public interface IConfidentialClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfidentialClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfidentialClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IConfidentialClientApplication = interface&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IClientApplicationBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            秘密のクライアント アプリケーションのように Web アプリ/API を使用するコンポーネントです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync scopes" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
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